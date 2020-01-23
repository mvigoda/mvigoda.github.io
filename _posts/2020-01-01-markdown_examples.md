# Basic Markdown

Here's the table of contents:

1. TOC
{:toc}

## Latex  
### Examples of Latex  

[Latex cheatsheet](#https://www.caam.rice.edu/~heinken/latex/symbols.pdf)  


\begin{markdown}
Inline math equations go in like so: $\omega = d\phi / dt$. 
Displaymath can be written as:
 
\begin{equation}
I = \int \rho R^{2} dV
\end{equation}
 
You can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.
\end{markdown}


$\sum_n (x)$  

$$
\sum_n (x)
$$


α β χ δ ε η γ ι
$\alpha $
\beta λ \chi μ \delta ν \epsilon o \eta ω \gamma φ \iota π
\kappa ψ \lambda ρ \mu σ \nu τ oθ \omega υ \phi ξ \pi 


  
Are $a, b \in \mathbb{R}, then  applies:  
(a+b)^{2} = a^{2} + ab + b^{2} $ \better \ 
are $a, b \in \mathbb{R}, \textrm{then apply} \, (a+b)^{2 } = a^{2 } + ab + b^{2}$\


\left( \begin{array}{cc} 2\tau & 7\phi-frac5{12} \\ 3\psi & \frac{\pi}8 \end{array} \right) \left( \begin{array}{c} x \\ y \end{array} \right)
\mbox{~and~} \left[ \begin{array}{cc|r}
3 & 4 & 5 \\ 1 & 3 & 729 \end{array} \right]



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







[Blogging Advice] https://www.fast.ai/2019/05/13/blogging-advice

[link text itself]: http://www.reddit.com  




[Follow up Post] https://www.fast.ai/2020/01/16/fast_template/
