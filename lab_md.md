---
title: Markdown
subtitle: "Workshop-Template-Rmd"
author: NBIS
---

# Text formatting   

Headings can be defined as shown below.  

```
## Level 2 heading  
### Level 3 heading  
#### Level 4 heading  
##### Level 5 heading  
###### Level 6 heading
```

## Level 2 heading  
### Level 3 heading  
#### Level 4 heading  
##### Level 5 heading  
###### Level 6 heading

Six custom classes are defined for text scaling. This can be defined inside a paragraph (`<p>`) or `<span>`.

```
<span class="largest">Largest text.</span>   
<span class="larger">Larger text.</span>  
<span class="large">Large text.</span>  
Normal text.  
<span class="small">Small text.</span>  
<span class="smaller">Smaller text.</span>  
<span class="smallest">Smallest text.</span>  
```

<span class="largest">Largest text.</span>   
<span class="larger">Larger text.</span>  
<span class="large">Large text.</span>  
Normal text.  
<span class="small">Small text.</span>  
<span class="smaller">Smaller text.</span>  
<span class="smallest">Smallest text.</span>  

A horizontal line can be created using three or more `*` or `-`.

`***`

***

`This is __Bold text__` This is __Bold text__  
`This is _Italic text_` This is _Italic text_  
`~~Strikethrough~~ text` ~~Strikethrough~~ text   
This is Subscript `H~2~O` displayed as H~2~O  
This is Superscript `2^10^` displayed as 2^10^  
`This is a [link](r-project.org)` This is a [link](r-project.org)  
An example of footnote reference [^note1]   

[^note1]: That reference refers to this footnote.  

```
> This is a block quote. This
> paragraph has two lines.
>
> 1. This is a list inside a block quote.
> 2. Second item.
```

> This is a block quote. This
> paragraph has two lines.
>
> 1. This is a list inside a block quote.
> 2. Second item.

Icons from [FontAwesome](https://fontawesome.com/v5.0.13/icons?d=gallery) can be displayed using the HTML `<i>` tag. Note that not all icons may work.

`Here is a <i class='fa fa-calendar'></i> calendar and a <i class='fa fa-couch'></i> couch.`

Here is a <i class='fa fa-calendar'></i> calendar and a <i class='fa fa-couch'></i> couch.

# Code formatting

Code can be defined inline where `` `this` `` looks like `this`. Code can also be defined inside code blocks.

<pre>
```
This is code
```
</pre>

```
This is code
```

Code formatting can also be achieved by four spaces

<pre>
    This is code
</pre>

    This is code


# Lists  
## Bulleted List  

Unordered lists are created using asterisks.

* Bullet 1  
* Bullet 2  
    + Sub-bullet 2.1  
    + Sub-bullet 2.2  
* Bullet 3

Ordered lists are created using numbers.

1. Point 1
2. Point 2
3. Point 3

# Images  
## Using Markdown  

Using regular markdown.  

```
![](assets/landing.png)
```

![](assets/landing.png)

The dimensions are based on image and/or fill up the entire available space. You can control the dimension as shown below.

```
![](assets/landing.png){width=30%}  
```


![](assets/landing.png){width=30%}   

This image above is now 30% of it's original width.

## Using HTML

This image below is 30% size.  
`<img src="assets/landing.png" style="width:30%;"/>`  

<img src="assets/landing.png" style="width:30%;"/>  

This image below is 30% size, has shadow and corners rounded.  
`<img src="assets/landing.png" style="width:30%;" class="fancyimage"/>`  

<img src="assets/landing.png" style="width:30%;" class="fancyimage"/>  

# Tables

Simple tables can be created using markdown. Below is an example of a table.

<pre>
|Sepal.Length|Sepal.Width|Petal.Length|Petal.Width|Species|
|---|---|---|---|---|
|5.1|3.5|1.4|0.2|setosa|
|4.9|3.0|1.4|0.2|setosa|
|4.7|3.2|1.3|0.2|setosa|
</pre>

which renders into an HTML table

|Sepal.Length|Sepal.Width|Petal.Length|Petal.Width|Species|
|---|---|---|---|---|
|5.1|3.5|1.4|0.2|setosa|
|4.9|3.0|1.4|0.2|setosa|
|4.7|3.2|1.3|0.2|setosa|


**End of document.**
