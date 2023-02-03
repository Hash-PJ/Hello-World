# Markdown Language
- Created by John Gruber in 2004
- lightweight markup language
- text-to-xHTML conversion tool
- to add formatting elements to plaintext text documents
- Portable, Platform-Independent, future proof, easy to use & understand
- Extension: .md or .markdown
- Markdown applications use a Markdown processor (also commonly referred to as a “parser” or an “implementation”) for text-to-xHTML conversion

### What’s Markdown Good For?
- Websites
- Documents
- Notes
- Books
- Presentations
- Email
- Collaboration
- Documentation

Full documentation of Markdown's syntax: [Markdown](https://daringfireball.net/projects/markdown/)  
To Practice: [Practice](https://www.markdowntutorial.com/)  
To check .md to xhtml conversion: [Dillinger](https://dillinger.io/)


### Basic Syntax    
**Headings:**     

Heading level 1 or # Heading level 1
===============

Heading level 2 or ## Heading level 2
---------------

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6


**Paragraph**: Add 2 spaces or br tag in the end of paragraph lines for soft break while a blank line for hard break      
    Added spaces, so Next Line began here <br>
    checking line break by using br tag       

To Make lines bold, use *(Preferrable) or_ 2 times before & after the text Like:     
    **I'm Bold with aesterik** && __Now Bold with underscore__  

To Make lines Italics, use *(Preferrable) or_ 1 time before & after the text Like:      
      *I'm Italics with aesterik* &&  _Now Italics with underscore_ 

To use Bold & Italics at once:     
      ***Way1***, ___Way2___, __*Way3*__, **_Way4_**  


**BlockQuote**:
1. Single-Line:  
> Single-Line blockquote

2. Multiple-Line:
> Line1
> line2

3. Nested:
> Line1
>> Nested Line1

4. With other Elements:
> ### Heading3 in blockquote
> - UnOrderedListItem in blockquote
> 1. OrderedListItem in blockquote
> **Boldy** with *Italicized*


**Lists:**   
***UnOrdered List:***  
- ListItem1
+ ListItem2
* ListItem8               
      1. IndentedListItem1
      2. IndentedListItem2
- 13656\. ListItem3 to show * If you need to start an unordered list item with a number followed by a period, you can use a backslash (\) to escape the period. *

***Ordered List:***  
1. ListItem1
2. ListItem2    
        Adding paragraph here to show indented paragraph * (Indentation works with four spaces or one tab)*
        second line in para
8. ListItem8
9. ListItem9     
        1. IndentedListItem1            
        2. Indentedlistitem2
6. ListItem3 now to show * The numbers don’t have to be in numerical order, but the list should start with the number one *  
7. ListItem4


**Images**:         
1. ***Inline image link***:                              

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/350px-Markdown-mark.svg.png)

2. ***Reference***:

![Black cat][Black]

3. ***Add Title & link***:

[![Orange cat][Orange]](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg
[Orange]: <http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png> 'Orange Cat'

**Links**:
1. ***Inline link***:

[Inline link](https://www.google.com/)

***Add title to link*** will appear as a tooltip when the user hovers over the link.        

[Inline link with title](https://www.google.com "Title Added")

2. Reference:

[Reference Link][ref]

[ref]: <https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/350px-Markdown-mark.svg.png>

***URLs or emails to Links***: Enclose it wihin <>

<https://www.github.com>

<git@github.com>

**Code Block**: Indent 4 spaces or 1 tab or when in list, double the indentation

    <html>
        <head>
        <title>Test</title>
        </head>
    </html>

When in List:

1. list1
2. List2

        <html>
            <head>
            <title>Test</title>
            </head>
        </html>
        
**Code**: Use Backticks

`This is code`      

***Escaping Backticks***:       

``Here I'm using 2 `backticks` to show that i have used more than 1 `backtick` in 1 line ``     

***Escaping Characters***: Use backslash(\)

\* Using Backslash to escape *

**Horizontal Rule**: use *** , --- , _____________ in next line

HR
***
___
________
