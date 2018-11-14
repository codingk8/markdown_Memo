[Node School Curriculum](https://nodeschool.io/)

[How to markdown](https://github.com/workshopper/how-to-markdown)

# Launch

npm install -g how-to-markdown

# Play

how-to-markdown

# What's inside

How To Markdown                                                            
Markdown is awesome!                                                       
────────────────────
  
   » HELLO WORLD                                                              
   » HEADINGS                                                                 
   » EMPHASIS                                                                 
   » LISTS                                                                    
   » LINKS                                                                    
   » IMAGES                                                                   
   » BLOCKQUOTES                                                              
   » CODE                                                                     
   » TABLES                                                                   
   » HORIZONTAL RULES                                                         
   » HTML                                                                     
   » GFM                                                                      
────────────────────
  
   HELP                                                                       
   CHOOSE LANGUAGE                                                            
   CREDITS                                                                    
   CHECK FOR UPDATE                                                           
   EXIT      
   
# Hello World
Welcome to how-to-markdown!  
   
### What is Markdown?  

First things first, let's consider what Markdown actually is.  

Markdown - is a lightweight, easy-to-read, easy-to-write plain text format  
for styling all forms of writing around the Internet. Markdown helps to  
control the display of the document: formatting words as bold or italic,  
adding images, creating lists and so on.  

Markdown was made by [John Gruber](http://daringfireball.net/) in 2004,  
with significant collaboration from [Aaron  
Swartz](http://www.aaronsw.com/).  

Markdown can be written in a basic text editor. It's an easy way to write  
text that easily translates into HTML. When you write in Markdown, you  
have to save the document with the .md or .markdown extensions.  

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

So, knowledge of Markdown is an important skill for modern developers.  
That's why you have to learn it.  

### How to get Markdown?  

There is no clearly defined Markdown standard. Markdown is just common  
rules on how to write readable and formatted text.  

While Markdown is a minimal markup language and is easily read and edited  
with a normal text editor, there's no need in specially designed editors  
for writing files in Markdown. However, there are a few editors that  
preview the files with styles.  

Implementations of Markdown are available for over a dozen programming  
languages (JavaScript, Ruby, Python, PHP, Perl, etc). In addition, many  
platforms and frameworks support Markdown out of the box. For example,  
Markdown plugins exist for every major blogging platform.  

### How to use this workshopper?  

It's easy to use this workshopper. In most cases, it's enough to use these  
three commands for interacting with this workshopper:  

» how-to-markdown run file.md will serve a local server at                                                                            
http://localhost:3000/ with a preview of file.md.                           
» how-to-markdown verify file.md will verify your file.                       
» how-to-markdown help shows a help message.                                  

## THE CHALLENGE  

You first challenge is pretty simple. Just create a new file (for example  
using touch) and add a single line:  

Hello, world!  

If you already did this, run how-to-markdown verify to verify your  
solution or how-to-markdown run to run your file in the browser.  


## Here's the **official solution** in case you want to compare notes:

Hello, world!

        ```plain Hello, world!```

## You did it!

Congratulations! You wrote your first paragraph in Markdown! Quite simple, isn't it?

If you are already familiar with HTML, you may guess that your solution will be rendered in such markup:

        ```html```
        <p>Hello, world!</p>

Paragraphs are separated by a blank line, so if you need to create two or more paragraphs, you have to write something like this:

        I am the first paragraph.

        I am the second one.

In the next exercise we will take a look at headings in Markdown.

You have 11 challenges left.


# HEADINGS (Exercise 2 of 12)  

It's important to categorize information. That's when headings help.  

If you need to add a heading, just type a # sign at the beginning of the  
line. The number of # is a heading level. For example:  

        # Heading 1  
        ## Heading 2  
        ### Heading 3  
        #### Heading 4  
        ##### Heading 5  
        ###### Heading 6  

As in HTML, there are 6 levels of headings. These headings will be  
transformed into \<h1>-\<h6> tags accordingly.  

There are aliases for first and second-level headings. You will get a  
first-level heading if you type three = signs on the following line. You  
can type three - on the following line to create a second-level heading.  
For example:  

        Heading 1  
        ===  

        Heading 2  
        ---  

## THE CHALLENGE  

Please create a first-level heading with Markdown is awesome! and then  
verify your solution.  

## Here's the **official solution** in case you want to compare notes:

# Markdown is awesome!

        ```plain
        # Markdown is awesome!
        ```

## Success!

There's nothing strange, right? Everything is obvious.

In all of the next exercises you will have to add headings with the name
of the current exercise.

In the next exercise we will take a look at emphasis in Markdown.

You have 10 challenges left.

# EMPHASIS (Exercise 3 of 12)  

It's easy to mark text as italic, bold, combined and strikethrough. There  
are a few ways to make emphasis in Markdown and each of those is readable.  

To get emphasis just wrap some text in single, double or triple asterisks  
(*) or underscores (_). Here are some examples:  

        Italics with *asterisks* and _underscores_.  

        |> Italics with asterisks and underscores.  

        Bold with **asterisks** or __underscores__  

        |> Bold with asterisks or underscores  

        Combined emphasis with **asterisks and _underscores_**.  

        |> Combined emphasis with asterisks and underscores.  

Sometimes you need to draw line through the text. To get strikethrough  
wrap the text in two tildes (~) like so:  

        ~~Scratch this line.~~  

        |> Scratch this line.  

## THE CHALLENGE  

Create a new file and add a first-level heading at the top of your file.  
This heading should contain Emphasis as text.  

Below the heading, add this text:  

It's very easy to use italic, bold and combined emphasis in Markdown!  

Please, mark italic, bold and combined using relevant styles. 

## Here's the **official solution** in case you want to compare notes:

# Emphasis
It's very easy to use italic, bold and combined emphasis in Markdown!

        ```plain
        # Emphasis
        It's very easy to use italic, bold and combined emphasis in Markdown!
        ```

## Nice job!

Now you know how you can easily mark important parts in Markdown.

**We suggest to use different notations for italic and bold**, for example:

1. Single underscore for _italic_ and double asterisks for **bold**
2. Single asterisk for *italic* and double underscores for __bold__

This approach helps to recognize different styles faster. For combined you
may mix styles such as _**combined**_ or *__combined__* as well.

In the next exercise we will take a look at lists in Markdown.

You have 9 challenges left.

# LISTS (Exercise 4 of 12)  
   
Lists are important for structured information. There is nothing hard in  
the creation of lists in Markdown. Just insert an asterisk (*) or a dash  
(-) before each item for an unordered list or a number with a dot for an  
ordered one (e.g., 1., 2., 3.).  

### Unordered lists  

Here is an example of an unordered list:  
   
     * item1  
     * item2  
     * item3  
   
And it will be transformed to something like this:  
   
   » item1                                                                       
   » item2                                                                       
   » item3                                                                       
   
Dashes work as well:  
   
     - first item with dash  
     - second item with dash  
   
Goes to:  
   
   » first item with dash                                                        
   » second item with dash                                                       
   
 ### Ordered lists  
   
Here is an example of a simple ordered list:  
   
     1. item1  
     2. item2  
     3. item3  
   
Which will be transformed into:  
   
   1. item1  
   2. item2  
   3. item3  
   
As you may see, this notation is very intuitive and readable.  
   
 ### Nested lists  
   
There is nothing hard about making a nested list. Just add a tab, or  
spaces for nested elements such as:  
   
     - element 1  
       - element 1.1  
       - element 1.2  
     - element 2  
       - element 2.1  
     - element 3  
   
For lists with * and ordered lists it works as well.  
   
 ## THE CHALLENGE  
   
In the new file add a first-level heading with Lists as content.  

Try to write your own list. Please create a new file and create an  
unordered list in it:  
   
   » One   » 1.1                                                                        
           » 1.2                                                                 
                                                                   
   » Two   » 2.1                                                                        
           » 2.2                                                                 
                                                                   
   » Three                                                                       
   » Four                                                                        
   » Five                                                                        
   
When you are done, please verify your solution.  
   
**Ma solution**

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

# Lists

  » One   » 1.1                                                                      
          » 1.2                                                               
                                                                
  » Two   » 2.1                                                                      
          » 2.2                                                               
                                                                
  » Three                                                                     
  » Four                                                                      
  » Five                                                                      

 ```plain
# Lists

  » One   » 1.1                                                                      
          » 1.2                                                               
                                                                
  » Two   » 2.1                                                                      
          » 2.2                                                               
                                                                
  » Three                                                                     
  » Four                                                                      
  » Five                                                                      
 ```

## Great!

There is one more thing. You may have any order of numbers in your ordered
lists. For example this notation works well:

    0. only zeros
    0. only zeros
    0. only zeros
    
    10. any order
    5. any order
    2. any order
    7. any order

  1. only zeros
  2. only zeros
  3. only zeros

  1. any order
  2. any order
  3. any order
  4. any order

Markdown parser is pretty clever in creating the correct order. This
approach may be very useful for supporting big ordered lists.

In the next exercise we will take a look at references in Markdown.

You have 8 challenges left.

