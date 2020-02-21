# Table of Contents

removed the 871 link

another test here February 21, 2020 10:56 AM 


[2017_Charts_header](http://mvigoda.github.io/datasets/2017_Charts_header.md)

## 2017 Charts of Interest

<br>
<div style="text-align: center;"> <IMG class="plain" SRC="/datasets/Discharges/Top_Discharges_2017.svg"  style="background:none; border:none; box-shadow:none;"  width="900" height="800" ALT="image">
<em></em></div>


 

<div style="text-align: center;"> <IMG class="plain" SRC="/datasets/Discharges/Top_Payments_2017.svg"  style="background:none; border:none; box-shadow:none;"  width="900" height="800" ALT="image">
<em></em></div>
<br>

   

<br>
<div style="text-align: center;"> <IMG class="plain" SRC="/datasets/Discharges/Sepsis_cumulative.svg"  style="background:none; border:none; box-shadow:none;"  width="900" height="800" ALT="image">
<em></em></div>
<br>






[10 378 chart](http://mvigoda.github.io/datasets/Discharges/10_378_Chart.html)

Here's the table of contents:

1. TOC
{:toc}

## Basic setup

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-filename.md`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `filename` is whatever file name you choose, to remind yourself what this post is about. `.md` is the file extension for markdown files.

The first line of the file should start with a single hash character, then a space, then your title. This is how you create a "*level 1 heading*" in markdown. Then you can create level 2, 3, etc headings as you wish but repeating the hash character, such as you see in the line `## File names` above.

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). Here's a footnote [^1]. Here's a horizontal rule:

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![](/images/logo.png "fast.ai's logo")

## Code

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |

## Footnotes

[^1]: This is the footnote.

