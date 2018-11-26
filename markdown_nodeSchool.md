[Node School Curriculum](https://nodeschool.io/)

[How to markdown](https://github.com/workshopper/how-to-markdown)

# Launch

CLI: npm install -g how-to-markdown

# Play

CLI: how-to-markdown

# What's inside

   1. HELLO WORLD                                                
   2. HEADINGS                                                                 
   3. EMPHASIS                                                                 
   4. LISTS                                                                    
   5. LINKS                                                                    
   6. IMAGES                                                                   
   7. BLOCKQUOTES                                                              
   8. CODE                                                                     
   9. TABLES                                                                   
   10. HORIZONTAL RULES                                                         
   11. HTML                                                                     
   12. GFM                                                      

---
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CREDITS                                                                    
   CHECK FOR UPDATE                                                           
   EXIT  
   
---
# 1.Hello World (Exercice 1 of 12)
Welcome to how-to-markdown!  
   
### What is Markdown?  

First things first, let's consider what Markdown actually is.  

**Markdown - is a lightweight, easy-to-read, easy-to-write plain text format for styling all forms of writing around the Internet. Markdown helps to control the display of the document: formatting words as bold or italic, adding images, creating lists and so on.**

Markdown was made by [John Gruber](http://daringfireball.net/) in 2004, with significant collaboration from [Aaron Swartz](http://www.aaronsw.com/).  

Markdown can be written in a basic text editor. It's an easy way to write text that easily translates into HTML. **When you write in Markdown, you have to save the document with the .md or .markdown extensions**.  

We can use Markdown almost everywhere:  

» **StackOverflow** uses Markdown for posts and comments.                         
» **GitHub** uses Markdown for discussions in issues and pull requests.           
» **Reddit** uses Markdown for formatting comments.                               
» **Slack, Gitter and other IM** use Markdown for formatting messages.            
» **Jekyll, Octopress, Hexo and other static site tools** use Markdown.           
» **GitBook** uses Markdown for writing books.                                    
» Many people prefer to use Markdown for writing their **blogs**.                 
» **Documentations for many open source project** are written in Markdown.        
» how-to-markdown also uses Markdown for formatting exercises.                

So, knowledge of Markdown is an important skill for modern developers. That's why you have to learn it.  

### How to get Markdown?  

**There is no clearly defined Markdown standard. Markdown is just common rules on how to write readable and formatted text.** 

While Markdown is a minimal markup language and is easily read and edited with a normal text editor, there's no need in specially designed editors for writing files in Markdown. However, there are a few editors that preview the files with styles.  
Implementations of Markdown are available for over a dozen programming languages (JavaScript, Ruby, Python, PHP, Perl, etc). In addition, many platforms and frameworks support Markdown out of the box. For example, Markdown plugins exist for every major blogging platform.  

### How to use this workshopper?  

It's easy to use this workshopper. In most cases, it's enough to use these three commands for interacting with this workshopper:  

» how-to-markdown run file.md will serve a local server at http://localhost:3000/ with a preview of file.md.                   
» how-to-markdown verify file.md will verify your file.                       
» how-to-markdown help shows a help message.                                  

## THE CHALLENGE  

You first challenge is pretty simple. Just create a new file (for example using touch) and add a single line:  

"Hello, world!"

If you already did this, run how-to-markdown verify to verify your solution or how-to-markdown run to run your file in the browser.  

## Here's the **official solution** in case you want to compare notes:

_The result:_

Hello, world!

_The Markdown:_

      Hello, world!

## You did it!

Congratulations! You wrote your first paragraph in Markdown! Quite simple, isn't it?

If you are already familiar with **HTML**, you may guess that your solution will be rendered in such markup:

      ```html
      <p>Hello, world!</p>
      ```

**Paragraphs are separated by a blank line**, so if you need to create two or more paragraphs, you have to write something like this:

I am the first paragraph.

I am the second one.

And get:

      I am the first paragraph.

      I am the second one.

In the next exercise we will take a look at headings in Markdown.

You have 11 challenges left.

# 2.HEADINGS (Exercise 2 of 12)  

It's important to categorize information. That's when headings help.  

If you need to add a heading, just type a # sign at the beginning of the line. The number of # is a heading level. For example:  

        # Heading 1  
        ## Heading 2  
        ### Heading 3  
        #### Heading 4  
        ##### Heading 5  
        ###### Heading 6
        
And it will look like:

# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6

**As in HTML, there are 6 levels of headings**. These headings will be transformed into \<h1>-\<h6> tags accordingly.  

There are **aliases for first and second-level headings**. You will get a first-level heading if you type three = signs on the following line. You can type three - on the following line to create a second-level heading.  
For example:  

        Heading 1  
        ===  

        Heading 2  
        ---  

gives you:

Heading 1
===

Heading 2
---

## THE CHALLENGE  

Please create a first-level heading with "Markdown is awesome!" and then verify your solution.  

## Here's the **official solution** in case you want to compare notes:

_The result:_

# Markdown is awesome!

_The Markdown:_

      # Markdown is awesome!

## Success!

There's nothing strange, right? Everything is obvious.

In all of the next exercises you will have to add headings with the name of the current exercise.

In the next exercise we will take a look at emphasis in Markdown.

You have 10 challenges left.

# 3.EMPHASIS (Exercise 3 of 12)  

It's easy to mark text as italic, bold, combined and strikethrough. There are a few ways to make emphasis in Markdown and each of those is readable.  

To get emphasis just wrap some text in single, double or triple asterisks (*) or underscores (_). Here are some examples:  

      Italics with *asterisks* and _underscores_.  

will give: Italics with *asterisks* and _underscores_.  

     Bold with **asterisks** or __underscores__  

will give: Bold with **asterisks** or __underscores__  

     Combined emphasis with **asterisks and _underscores_**.  

will give: Combined emphasis with **asterisks and _underscores_**.  

Sometimes you need to **draw line through the text**. To get strikethrough wrap the text in two tildes (~) like so:  

     ~~Scratch this line.~~  

will give: ~~Scratch this line.~~

## THE CHALLENGE  

Create a new file and add a first-level heading at the top of your file. This heading should contain "Emphasis" as text.  

Below the heading, add this text: "It's very easy to use italic, bold and combined emphasis in Markdown!"  

Please, mark italic, bold and combined using relevant styles. 

## Here's the **official solution** in case you want to compare notes:

_The result:_

# Emphasis
It's very easy to use _italic_, **bold** and **_combined emphasis-** in Markdown!

_The Markdown:_

      # Emphasis
      It's very easy to use _italic_, **bold** and **_combined emphasis_** in Markdown!

## Nice job!

Now you know how you can easily mark important parts in Markdown.

**We suggest to use different notations for italic and bold**, for example:

1. Single underscore for _italic_ and double asterisks for **bold** as in
   ```plain
   1. Single underscore for _italic_ and double asterisks for **bold**
   ```
         
2. Single asterisk for *italic* and double underscores for __bold__ as in
   ```plain
   2. Single asterisk for *italic* and double underscores for __bold__
   ```

**This approach helps to recognize different styles faster**. For combined you may mix styles such as _**combined**_ or *__combined__* as well, as in
   ```plain 
   For combined you may mix styles such as _**combined**_ or *__combined__* as well
   ```

In the next exercise we will take a look at lists in Markdown.

You have 9 challenges left.

# 4.LISTS (Exercise 4 of 12)  
   
**Lists are important for structured information**. There is nothing hard in the creation of lists in Markdown. Just insert an asterisk (*) or a dash (-) before each item for an unordered list or a number with a dot for an ordered one (e.g., 1., 2., 3.).  

### Unordered lists  

Here is an example of an unordered list:  
```plain
* item1  
* item2  
* item3  
```
   
And it will be transformed to something like this:  
* item1                                                                       
* item2                                                                       
* item3                                                                       
   
Dashes work as well:  
```plain
- first item with dash  
- second item with dash  
```  
   
Goes to:  
- first item with dash                                                        
- second item with dash                                                       
   
 ### Ordered lists  
   
Here is an example of a simple ordered list:  
```plain
1. item1  
2. item2  
3. item3
```
   
Which will be transformed into:  
1. item1  
2. item2  
3. item3  
   
As you may see, this notation is very intuitive and readable.  
   
 ### Nested lists  
   
There is nothing hard about making a nested list. Just add a tab, or spaces for nested elements such as:  
```plain
- element 1  
   - element 1.1  
   - element 1.2  
- element 2  
   - element 2.1  
- element 3
```

As in:
- element 1
   - element 1.1
   - element 1.2
- element 2
   - element 2.1
- element 3
   
For lists with * and ordered lists it works as well.  
   
 ## THE CHALLENGE  
   
In the new file add a first-level heading with "Lists" as content.  

Try to write your own list. Please create a new file and create an unordered list in it:  
   * One   
      * 1.1                                                                        
      * 1.2                                                             
   * Two   
      * 2.1                                                                        
      * 2.2            
   * Three                                                                       
   * Four                                                                        
   * Five                                                                        
   
When you are done, please verify your solution.  
   
## My solution

        # Lists

        - One
            - 1.1
            - 1.2
        - Two
            - 2.1
            - 2.2
        - Three
        - Four
        - Five

## Here's the **official solution** in case you want to compare notes:

_The result:_

# Lists
- One
   - 1.1                                                                      
   - 1.2                                                               
- Two
   - 2.1                                                                      
   - 2.2                                                               
- Three                                                                     
- Four                                                                      
- Five                                                                      

_The Markdown:_

 ```plain
# Lists

  * One
   * 1.1
   * 1.2
  * Two    
   * 2.1
   * 2.2
  * Three                                                                     
  * Four                                                                      
  * Five                                                                      
 ```

## Great!

There is one more thing. **You may have any order of numbers in your ordered lists**. For example this notation works well:

```plain
0. only zeros
0. only zeros
0. only zeros

10. any order
5. any order
2. any order
7. any order
```
gives:

1. only zeros
2. only zeros
3. only zeros

1. any order
2. any order
3. any order
4. any order

**Markdown parser is pretty clever in creating the correct order**. This approach may be very useful for supporting big ordered lists.

In the next exercise we will take a look at references in Markdown.

You have 8 challenges left.

# 5.LINKS (Exercise 5 of 12)  
   
We often need to make a reference for something. There are two ways to create links: **inline-style** and **reference-style**.

By the way, the easiest way to create a link is to just paste the link into a Markdown file. **URLs and URLs in angle brackets will automatically get turned into links**:  
   
     http://www.example.com or <http://www.example.com>  
   
  gives: (http://www.example.com) or <http://www.example.com>  
   
### Inline style  
   
Links in Markdown have this format:  
   
      [text](href "alt")  
   
Above, text is text that will be a link, href is your reference to the resource (similar to href attribute in HTML), alt is an alternative text for link (similar to alt attribute in HTML). Text in a link may have any formatting, which means you are able to use emphasis in your links, if needed.  

Here are more real world examples:  

      [Google](https://www.google.com)  
      [Google Homepage](https://www.google.com "Google Homepage")  
   
 ### Reference style  
   
Sometimes you have to **use the same link in different places**, so it would be **convenient to use one reference for all of these links**. So you may do this like so:  
   
     [NodeSchool Site][ref]  
     [GitHub][1]  
     [Remark parser]  
       
 Some text to show that the reference links can follow later:  
       
     [ref]: http://www.nodeschool.io  
     [1]: https://github.com/  
     [Remark parser]: http://remark.js.org/  
   
As you may notice above, references are case-insensitive and you are free to use numbers for creating references or use link text itself as its reference.  
   
## THE CHALLENGE  
   
At the top of the file, add a first-level heading with "Links" text.  

Here you have some text: "how-to-markdown is a workshopper that teaches you how to write Markdown".  
   
Please, copy this text to the new file and mark 'how-to-markdown' phrase as reference-style link with reference to itself. Below in your file, add a relevant reference which will reference to the //git.io/how-to-markdown.  

When you are done, please, verify your solution.  

## My solution

      # Links

      [how-to-markdown] is a workshopper that teaches you how to write Markdown.
      [how-to-markdown]: //git.io/how-to-markdown
        
## Here's the official solution in case you want to compare notes:

_The result:_
# Links

[how-to-markdown] is a workshopper that teaches you how to write Markdown.

[how-to-markdown]: //git.io/how-to-markdown


_The Markdown:_

 ```plain
# Links
[how-to-markdown] is a workshopper that teaches you how to write Markdown.
[how-to-markdown]: //git.io/how-to-markdown
 ```

## Amazing!

**References are very handy in cases when you have to write a big document**, such as documentation for your project. If you have a lot of links and you want to easily manage them, you can create a section at the bottom of your file and leave all your references there. For example:

    A lot of text. Many [useful] and [important] information here.
    
    <!-- My References -->
    [useful]: http://useful.site
    [important]: https://important.site

Above, <!-- My References --> is an HTML-comment that will be omit. You can skip this comment, but actually it helps to recognize a section with references. This approach helps you to keep track of all of your links.

By the way, **references also work for images as well!**

In the next exercise we will take a look at images in Markdown.

You have 7 challenges left.

# 6.IMAGES (Exercise 6 of 12)  

The embedding of images is very similar to insertion of links. To embed an image you have to use this syntax:  
   
     ![alt text](url)  
   
As you may see, the only difference is that you have to add an exclamation mark before squared brackets. 
- "alt text" is an alternate text for an image (similar to alt attribute in HTML)
- "url" is the URL of an image (similar to src attribute in HTML)

The reference style also works for images. You can do something like this:  
   
     ![reference style][logo]  
       
     [logo]: ./logo.png  
   
## THE CHALLENGE  

Add a first-level heading with "Images" text inside.  

Let's say we have a Markdown logo on this URL: http://bit.do/how-to-markdown  

Below, you should create a inline-style image with "Markdown logo" as alternate text and http://bit.do/how-to-markdown as URL.  

## Here's the official solution in case you want to compare notes:

_The result:_

# Images
![Markdown logo](http://bit.do/how-to-markdown)

_The Markdown:_

      # Images
      ![Markdown logo](http://bit.do/how-to-markdown)

## Cool!

Now you learned how to add an image in Markdown. This is a common style for images, but **some parsers provide additional tools for alignment, adding classes and other styles**.

In the next exercise we will take a look at blockquotes in Markdown.

You have 6 challenges left.

# 7.BLOCKQUOTES (Exercise 7 of 12)  

Sometimes we need to quote someone's words. In that case, blockquotes are exactly what we need.  

The syntax of blockquotes is simple:  
   
     > This is my blockquote.  
     > This line is part of the same quote.  
   
This will look like this:  
   
> This is my blockquote. This line is part of the same quote.  
   
As you have seen, **the line-break doesn't break a block of quote. To separate a few quotes just add an empty line between them.**

And this:

      > This is my blockquote

      > This is an other quote
   
will look like this:
> This is my blockquote.  

> This is an other quote.   

You are able to put Markdown into a blockquote, therefore this will work as well:  
   
     > **Markdown** is a _lightweight markup language_ with plain text formatting syntax designed so 
     > that it can be converted to **HTML** and many other formats.  
     > - from [Wikipedia](https://en.wikipedia.org/wiki/Markdown)  
     
This will look like this:
> **Markdown** is a _lightweight markup language_ with plain text formatting syntax designed so 
> that it can be converted to **HTML** and many other formats.  
> - from [Wikipedia](https://en.wikipedia.org/wiki/Markdown)
   
## THE CHALLENGE  

Start the new file with "Blockquotes" as heading.  

Add a quote from William Shakespeare's play Hamlet: "To be, or not to be, that is the question."

And add an original author to the quote right on the next line after this quote. When you are done, verify your solution.  

## Here's the official solution in case you want to compare notes:

_The result:_

# Blockquotes
> To be, or not to be, that is the question.  
> William Shakespeare

_The Markdown:_

      # Blockquotes
      > To be, or not to be, that is the question.  
      > William Shakespeare

## Neat!

You made a great quote from a great play! Blockquotes are useful and handy in email to emulate reply text. They are often used in conversation at GitHub for replies to specific comments.

In the next exercise we will take a look at code in Markdown.

You have 5 challenges left.

# 8.CODE (Exercise 8 of 12)  

Code is a part of Markdown spec. There are **two ways to add code in your document: inline code and blocks of code.**  

### Inline code  

**To mark a part of text as code, just wrap it in back-ticks (  \` ).**
Here is an example:  
   
     Inline code transforms into `<code>` html-tag.  
   
Inline code transforms into `<code>` html-tag.  
   
### Blocks of code  
   
**Blocks of code** are either **fenced by lines with three back-ticks (   \`\`\`)**, or are **indented with four spaces**.  

Syntax highlighting isn't part Markdown's spec. However, **many renderers support syntax highlighting.** Which languages are supported and how those language names should be written will vary from renderer to renderer.  
   
     ```js  
     console.log('This is JavaScript syntax highlighting!');  
     ```  
       
     ```  
     No language indicated, so no syntax highlighting.  
     ```  
       
         Block of code with indentation.  
   
These two blocks will be rendered like so:  

```js
console.log('This is JavaScript syntax highlighting!'); 
```
```
No language indicated, so no syntax highlighting.  
```

    Block of code with indentation.  
   
**We recommend to use the fenced code blocks** instead of blocks with indentation, **because they support syntax highlighting.**  
   
## THE CHALLENGE  

Add  "Code" as the first-level heading in your file.  

Add this JavaScript code with relevant syntax highlighting: "const add = (a, b) => a + b;"

Don't forget to verify your solution.  
   
##  Here's the official solution in case you want to compare notes:

_The result:_

# Code
```js
const add = (a, b) => a + b;
```

_The Markdown:_

    # Code
    ```js
    const add = (a, b) => a + b;
     ```

## Awesome!

**Now you can embed code snippets into Markdown documents.** That is yet another thing that is used almost everywhere.

In the next exercise we will take a look at tables in Markdown.

You have 4 challenges left.

# 9.TABLES (Exercise 9 of 12)  
   
Tables are **not a part of Markdown spec, but a lot of parsers support them.** Especially **GFM which are used on GitHub**.  

The creation of tables in Markdown looks exactly like **drawing using dashes (-) and pipes (|)**. Also, you may use colons to align columns. For example:  

     | Head         | of       | Table         |  
     | ------------ |:--------:| ------------ :|  
     | left-aligned | centered | right-aligned |  
     | left-aligned | centered | right-aligned |  
   
The table above will be rendered like this:  
   
 |Head        |    of    |Table          |
 |------------|:--------:| -------------:| 
 |left-aligned| centered |right-aligned  |
 |left-aligned| centered |right-aligned  |
   
There are a few **important things** here:  

 » There must be **at least 3 dashes separating each header cell**. Colons to align columns count as dashes.                   
 » The **outer pipes (|) are optional.**                                           
 » You can **use inline Markdown in cells.**                                       

That means you can do something like this:  
   
     Markdown | Less | Pretty  
     -----| ----- | ----- 
     *Still* | `renders` | **nicely**  
   
It doesn't looks so nice, but it works as expected:  
   
 Markdown | Less  |  Pretty  
 -------- ------- ------  
 *Still*  |  `renders`| **nicely**  
   
## THE CHALLENGE  

Add a first-level heading that contains the name of this exercise.  

Reproduce this table:  
   
 Year World population  
 ---- ----------------  
 1960 3 Billion  
 1980 4 Billion  
 2000 6 Billion  
   
The Year column should be centered.  
   
## My solution

        # Tables
        |Year|World population|
        |:--:|---------|
        |1960|3 Billion|
        |1980|4 Billion|
        |2000|6 Billion|

## Here's the official solution in case you want to compare notes:

# Tables

_The result:_

Year World population
---- ----------------
1960 3 Billion
1980 4 Billion
2000 6 Billion

_The Markdown:_

```plain
# Tables
Year World population
---- ----------------
1960 3 Billion
1980 4 Billion
2000 6 Billion
```

## Very well!

You did a cool table of the World population. Now do you realize how awesome tables in Markdown are? They are easy and readable, even in plain files.

In the next exercise we will take a look at horizontal rules in Markdown.

You have 3 challenges left.

# 10.HORIZONTAL RULES (Exercise 10 of 12)  
   
Sometimes we have to divide some information. In HTML we use the \<hr> tag, which means horizontal rule, and looks like <hr> 

There's nothing hard to make a horizontal rule in Markdown. Just type three or more dashes (-), asterisks (*) or underscores (_):  

     Dashes  
       
     ---  
       
     Asterisks  
       
     ***  
       
     Underscores  
       
     ___  
   
And it will turn into:  

Dashes  

---  
Asterisks  

***
Underscores  

___ 

As you may remember from the Headings exercise, **three dashes on the next line makes a second-level heading. To avoid this behavior, just add an empty line between text and these dashes**.  

## THE CHALLENGE  

Please add a Horizontal rules heading and add a horizontal rule right after this heading.  

That's it. Just verify your solution.  

## My solution

        # Horizontal rules
        
        ---

## Here's the official solution in case you want to compare notes:

_The result:_

# Horizontal rules

***

_The Markdown:_


```plain
# Horizontal rules

***
```

## Nice job!

It was a pretty easy exercise, but sometimes horizontal rules are very handy, so you should know how to create them.

In the next exercise we will take a look at inline HTML in Markdown.

You have 2 challenges left.

# 11.HTML (Exercise 11 of 12)  
   
If you want to style something more than is allowed in Markdown, you can use raw HTML in your Markdown and it'll work pretty well.  

   <p align="center">Centered text works well!</p>  

And you will get a centered paragraph.  

Sometimes it's helpful, but be careful! Markdown inside HTML won't be rendered! That means if you write something like this:  
   
     <span>Markdown **won't** work here!</span>  
   
It won't work.  

## THE CHALLENGE  

Add HTML as the first-level heading.  

Below, use HTML for centering this text: HTML in Markdown  
   
Verify your solution.  

## My solution

        # HTML
        <p align="center">HTML in Markdown</p>
        
## Here's the official solution in case you want to compare notes:

_The result:_

# HTML
<p align="center">HTML in Markdown</p>

_The Markdown:_

      # HTML
      <p align="center">HTML in Markdown</p>

## Works!

**You can use HTML for creating anything you want:** definition lists, embedding posts from social networks, embedding videos from YouTube, etc... Just **type HTML tags right in your Markdown document and see how it works.**

In the next exercise we will take a look at GFM in Markdown.

You have one challenge left.

# 12.GFM (Exercise 12 of 12)  

If you are a developer, then you have heard about GitHub. GitHub is an important part of the community. Why are we talking about it? That's because **GitHub is a big customer of Markdown**. Even more, **GitHub uses its own version of the Markdown syntax that provides an additional set of useful features**. This version of markdown is called **GitHub Flavored Markdown or simply GFM**.  

From previous exercises you are already familiar with syntax highlighting in blocks of code and tables. However, there are some other features which may be helpful for you.  

### Task lists  

To create a task list you should create an ordered or unordered list. Then you can use squared brackets that will be turned into checkboxes. An x between them makes the item marked as completed. Example:  
   
      - [x] [links](#), **formatting**, and <del>tags</del> supported  
      - [x] list syntax required (any unordered or ordered list supported)  
      - [x] this is a complete item  
      - [ ] this is an incomplete item  
   
gives:

- [x] [links](#), **formatting**, and <del>tags</del> supported                   
- [x] list syntax required (any unordered or ordered list supported)          
- [x] this is a complete item                                                 
- [ ] this is an incomplete item                                              
   
### SHA references  

Any reference to a commit’s SHA-1 hash will be automatically converted into a link to that commit on GitHub:  

   4ad0c921206dec4d1518f4aeead932e7617f934f  
   denysdovhan/how-to-markdowkn@4ad0c921206dec4d1518f4aeead932e7617f934f  

### Issue and Pull request references  

Any number that refers to an Issue or Pull Request will be automatically converted into a link:  
   
     #1  
     denysdovhan/how-to-markdowkn#1  
   
### Username @mentions  

Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called a @mention, because you’re mentioning the individual. You can also mention @teams within an organization.  
   
### Emoji  

It's a funny part, but it's still important. GFM also supports emoji!  

✨ 🐫 💥  

To see a list of every emoji that is supported, check out the [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/).  
   
## THE CHALLENGE  

Add a first-level heading that contains GFM.  

Please create a to-do list with these tasks: 
» hey                                                                         
» ho                                                                          
» let's go                                                                    

Then mark item ho as completed.  

Verify your solution.  

## My solution
        # GFM
        - [ ] hey
        - [x] ho
        - [ ] let's go

## Here's the official solution in case you want to compare notes:

_The result:_

# GFM
- [ ] hey                                                                   
- [x] ho                                                                    
- [ ] let's go                                                              

_The Markdown:_

      # GFM
      - [ ] hey                                                                   
      - [x] ho                                                                    
      - [ ] let's go                                                              

## Congratulations!

You finished this workshopper! Now you are familiar with Markdown and know how to write and read Markdown documents.

What should you **do next? Just write some Markdown.** Rewrite the README-file of your project in Markdown, start to write posts in your blog in Markdown, whatever.

Anyway, knowledge of Markdown is a very nice skill that will be useful.

Thank you for using this workshopper. Check out other workshoppers on [Node School](http://nodeschool.io).

You've finished all the challenges! Hooray!

---

<p align="center"><img src="https://media.giphy.com/media/SpuM90tcpfhN6/giphy.gif" alt="Let it roll")</p>
