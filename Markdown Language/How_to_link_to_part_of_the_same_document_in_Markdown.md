How to link to part of the same document in Markdown ?

Github automatically parses anchor tags out of your headers. So you can do the following:

[Custom foo description](#foo)

# Foo
In the above case, the Foo header has generated an anchor tag with the name foo

Note: just one # for all heading sizes, no space between # and anchor name, anchor tag names must be lowercase, and delimited by dashes if multi-word.

[click on this link](#my-multi-word-header)

### My Multi Word Header









# Contents
 - [Specification](#specification) 
 - [Dependencies Title](#dependencies-title) 

## Specification
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. 

## Dependencies Title
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. Example text blah. Example text blah. 
Example text blah. Example text blah. 