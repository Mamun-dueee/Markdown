# Syntax guide
I am learning markdown syntaxsssss..... 

## Headers

This is very simple. 

## Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered
* Item 1
* Item 2
	* Item 2a
	* Item 2b
	
### Ordered
1. Item 1
1. Item 2
1. Item 3
	1. Item 3a
	1. Item 3b
	
### Images
![Imgur](http://i.imgur.com/NhmmwFQ.png)

## Links
http://github.com - automatic!

[GitHub](http://github.com)

## Blockquotes

As Kanye West said:

> We're living the future so
> the present is our past.

## Inline code

I think you should use an `<addr` element here instead.

# GitHub Flavored Markdown

## Syntax highlighting

### javascript
```javascript
function fancyAlert(arg){
	if(arg) {
		$.facebox({div: '#foo'})
	}
}
```

## Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Tables

You can create tables by assembling a list of words and dividing them with
hyphens `-` (for the first row), and then separating each column with 
a pipe `| ` :

First Header | Second Header
-------------|--------------
   cell 1	 | cell 2
   Mamun 	 | Sumon 
   
## StrikeThrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

## Emoji 

Github supports emoji ! :smile: :stuck_out_tongue_winking_eye: :open_mouth:

## C Code
```c
#include<stdio.h>
void main()
{
    printf("Hey! This is syntax highlighting test for C code. ");
}
```
