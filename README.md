HEADERS:
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alt-H1
======
Alt-H2
------

## EMPHASIS:

*Italics*  or  _Italics_ 

 **Bold** or __Bold__.
 
Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

## LISTS:

#### Ordered List:

1.List Item 1

2.List Item 2

#### Unordered List

* Unordered list can use asterisks
- Or minuses
+ Or pluses

## LINKS:

[I'm an inline-style link](https://www.google.com)

## IMAGES:

![image](https://user-images.githubusercontent.com/110591443/233267369-e33a2ef5-f865-43a2-9be7-637b934227eb.png)



Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.
Renders to:

rendered footnotes

## TABLES:

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |


Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
Colons can be used to align columns.

Tables	Are	Cool
col 3 is	right-aligned	$1600
col 2 is	centered	$12
zebra stripes	are neat	$1
There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown	Less	Pretty
Still	renders	nicely
1	2	3
Blockquotes
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.


Inline HTML
You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
Definition list
Is something people use sometimes.
Markdown in HTML
Does *not* work **very** well. Use HTML tags.
Horizontal Rule
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
Three or more...

Hyphens

Asterisks

Underscores

Line Breaks
My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.



(Technical note: Markdown Here uses GFM line breaks, so there's no need to use MD's two-space line breaks.)

YouTube Videos
They can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
Referencing a bug by #bugID in your git commit links it to the slip. For example #1.



