This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

`echo 'Hello World'`{{execute}}

### This is a Heading 3

Here is an inline piece of code using quotes 'inline quote'

> Here is a bit of blockquoting
> it needs you to put a greater than symbol at the start of
> each line

Now let's try some lists.  Markdown is supposed to support a number of list styles:

- this
- style
- using dashes

And this:
* style
* using asterisks
* like this

and you can even use +:
+ plus
+ signs
+ like this

Now for ordered lists you can use numbers:

1. You can use any number
1. But I think it would look odd in a document
1. If you try to get the numbering right

The _daringfireball guide_ says to always start them at 1 in case numbering restart is allowed in the future.

One of the issues in mediawiki is that the numbering often restarts and you need to use #: to keep it going. But if you insert a figure it will restart, so you end up having to revert to:

1. Here is a list with a second paragraph indented by 4 spaces

    This is the second paragraph of my list.  It seems to wrap automatically in my editor, which is nice

    <this is a codeblock within my list>

1.  Here is the second item in my list.

1.  And the third



I really like using definition lists. However, I don't think they are allowed.  Let's see:

First Term
: Definition of the first term

Second Term
: Defintion of the second term

Unfortunately that didn't result in a HTML <dl> being created

Now let's have a go at linking:

[link to bbc] [bbc]
[link to google] [google]


We could then have a list of links at the bottom of the page:

[bbc] (http://www.bbc.co.uk)
[google] (http://www.google.co.uk)