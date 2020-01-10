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

1.  And the third and this one has a sub-list
    1. This is a sublist
    1. Another item in my sublist. This is `inline code`.  I really like this rather than having to put code markers.  However, the sublist still uses arabic numbers.  It would be nice to be able to change.


#### Defintion Lists - Heading 4

I really like using definition lists. However, I don't think they are allowed.  Let's see:

First Term
: Definition of the first term

Second Term
: Defintion of the second term

Unfortunately that didn't result in a HTML <dl> being created


#### Emphasis

We can use backticks to do `inline code` and we can use _underscores_ or asterisks to to do emphasis. One translates to emphasis in italics, two of either translates to __bold__ or **strong** in HTML terms.


### Try out some linking

So 

#### Headings

All headings seem to look exactly the same, which is a bit crap.

#### Let's try linking

Now let's have a go at linking:

[link to bbc] (http://www.bbc.co.uk)

[link to bbc] [bbc]
[link to google] [google]


We could then have a list of links at the bottom of the page:

[bbc] (http://www.bbc.co.uk)
[google] (http://www.google.co.uk)


### What about Tables

I've copied this from https://guides.github.com/features/mastering-markdown/

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

That worked OK.  Transforms to a HTML table.

However, what if I want to create a complex table.  I guess I could use a HTML table generator and paste the results in here.

<table class="tg">
  <tr>
    <th class="tg-0pky" colspan="2"></th>
    <th class="tg-0lax"></th>
    <th class="tg-0lax"></th>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax" rowspan="2"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
</table>

