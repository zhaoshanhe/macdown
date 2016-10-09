# add code block 
MPDocument.m
~~~
-(IBAction)insertCodeBlock:(id)sender
{
     [self.editor toggleForMarkupPrefix:@"~~~\n" suffix:@"\n~~~"];
}
~~~
