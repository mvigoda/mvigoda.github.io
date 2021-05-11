# Basic Markdown  


Last update : May 8, 2021   
[Markdown Guide](https://about.gitlab.com/handbook/markdown-guide/)



Here's the table of contents:

1. TOC
{:toc}


## Basic setup

Here's a footnote [^1]. Here it is in Basic Formatting. 

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-filename.md`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `filename` is whatever file name you choose, to remind yourself what this post is about. `.md` is the file extension for markdown files.

The first line of the file should start with a single hash character, then a space, then your title. This is how you create a "*level 1 heading*" in markdown. Then you can create level 2, 3, etc headings as you wish but repeating the hash character, such as you see in the line `## File names` above.

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). 

Here's a footnote [^1]. Second instance of footnote #1.

Here's a footnote [^2]. Here's a horizontal rule:

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2


## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |




## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}. 

{% include alert.html text="You can include a second alert box" %}

...and...

{% include info.html text="You can include info boxes" %}

 
## Horizontal lines
A sequence of three or more dashes will produce a horizontal line, but let's use always 4 as standard. Leave blank lines after and before it:

Text
<!-- blank line -->
----
<!-- blank line -->
Text



## Images

![](/images/logo.png "fast.ai's logo")

## Code

General preformatted text:

    # Do a thing
    do_thing()

### Python code and output:

```python
# Prints '2'
print(1+1)
```

    2



***


---




## Footnotes

[^1]: This is the footnote.
[^2]: Second footnote.


___


[Blogging Advice] https://www.fast.ai/2019/05/13/blogging-advice
[Blogging Advice from Fastai](https://www.fast.ai/2019/05/13/blogging-advice)

[link text itself]: http://www.reddit.com  

[Follow up Post] https://www.fast.ai/2020/01/16/fast_template/
