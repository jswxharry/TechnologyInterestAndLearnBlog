
# HORIZONTAL RULES
Each of the following lines will produce a horizontal rule:
* * *

***

*****

- - -


#Header testing(use #)

# header 1
## header 2
### header 3

***
#List testing (use -, 1./2./3.)
- list 1
- list 2
- list 3

1.a --> this is not a list format without adding a space
1. a
2. b
3. c

***
# testing Block quote (use  > and a space)
at
> quotes a word
without a space line it seems will be kept in quote format

return to the normal text(with a empty line added)

> test nested block quote -> 
>> hi this is the nesteded block quote with double >>

***
# testing link & image link
[baidu](www.baidu.com)
![Mou Icon](http://25.io/mou/Mou_128.png)
Click able link with <link url>: <http://baidu.com/>

***
#Testing Blod
**Bold**
*another*
\*this text is surrounded by literal asterisks\*
\*\*this is good as well \*\*
\~\~ remove the word\~\~: ~~remove the word~~

  
***
#Code Block
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab.

4 spaces:

     string a= "a"; -- this is a code block with 4 blanks

1 tab(seems don't works):

  string a="a";

Here is an example:

    tell application "Foo"
        beep
    end tell

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

***
## Code
set a code part in word`printf()`

##To include a literal backtick character within a code span
``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``
A backtick-delimited string in a code span: `` `foo` ``

***
# Table
-  Test simple Table

Let's|Make |a table
---|---|---
a|b|c

-  Test aesthetic, output the same, but the source code is better looking

|Let's | Make | a table|
|---|---|---|
|a|b|c|

- Test we don't need to indent well in our source markdown code

|Name|Description|
|---|---|
|Help | Display the help window.|
| Close | Closes a window |

- Test **inline Markdown** such as links, bold, italics, or strikethrough

| Name | Description |
| ------------- | ----------- |
| Help | ~~Display the~~ help window.|
| **Bold** | *Italic1*, *Italic2* |

|default is left|left-aligned|right-aligned|cetered|
|---|:---|---:|:---:|
|a|b|c|d|
| col 1,2 is | some wordy text | $1600 |aa|
| col 4 is | centered | $12 |bb|
| zebra stripes | are neat | $1 |cc|


