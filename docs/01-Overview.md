# Overview




Before we get busy downloading and installing the actual software, here is the big picture.



## R vs. R Studio

First time users often confuse by all the different uses of the letter "R". 

| $R$ | $R Studio$ |
|:---:|:-----------:|
| Engine | Dashboard |
| Install and Ignore | Interact with Constantly | 
| ![](images/car_engine.jpg){width=500px} | ![](images/car_dashboard.jpg){width=500px} |


More precisely, $R$ is a *programming language* that runs computations while $R Studio$ is an *integrated development environment (IDE)* that provides an interface by adding many convenient features and tools. So the way of having access to a speedometer, rearview mirrors, and a navigation system makes driving much easier, using $RStudio’s$ interface makes using $R$ much easier as well.  - [Chester Ismay and Albert Y. Kim](https://ismayc.github.io/moderndive/index.html)




<div class="rmdlink">
<p>For a more in-depth discussion on the difference between <span class="math inline">\(R\)</span> and <span class="math inline">\(R Studio\)</span> IDE, watch this <a href="https://campus.datacamp.com/courses/working-with-the-rstudio-ide-part-1/orientation?ex=1">DataCamp video (2m52s)</a>.</p>
</div>



## R Markdown vs. R Notebook



<div class="rmdconstruct">
<p><strong>ADD SECTION:</strong> need a diagram built</p>
</div>





## The Magic of Knit'ing

$R Markdown$ is a file with the file extension `.Rmd`, the `knitr` package will then transform the file into a *Markdown* file with the extension `.md.` Then $R Studio$ can [@xie2015]:

  * Use $LaTeX$ to transform the file into a `.pdf` 
    
  * Load another package called $markdown$ to transform the file into `.html`   
    
  * Use Pandoc to even convert to file to a `Word` document (ugly)

![](images/processRStudio.png)



<div class="rmdlink">
<p>The professionals ar <span class="math inline">\(R Studio\)</span> show it better at their <a href="https://rmarkdown.rstudio.com/index.html">website</a>.</p>
</div>



![](images/hex/rmarkdown-200x232.png){width=100px}

 
$R Markdown$ documents are fully reproducible. Use a productive **notebook** interface to weave together narrative text and code to produce elegantly formatted output. Use multiple languages including $R$, $Python$, and $SQL$ [@R-rmarkdown].


![](images/hex/knitr-200x232.png){width=100px}


`knitr` is an engine for dynamic report generation with $R$. It is a package in the statistical programming language $R$ that enables integration of **R code** into $LaTeX$, $LyX$, $HTML$, $Markdown$, $AsciiDoc$, and $text$s documents [@R-knitr].



<div class="rmdlink">
<p>Helpful Website: <a href="https://www.statmethods.net/stats/index.html">Quick R: Basic Statistics</a></p>
</div>



-------------

## Additional FAQs 



### What is R ? {-}

> $R$ is a language and environment for statistical computing and graphics. [@R-base]

$R$ provides a wide variety of **statistical** *(linear and nonlinear modelling, classical statistical tests, time-series analysis, classification, clustering, ...)* and **graphical** techniques, and is highly extensible. The $S$ language is often the vehicle of choice for research in statistical methodology, and $R$ provides an Open Source route to participation in that activity.

One of $R$’s strengths is the ease with which well-designed publication-quality plots can be produced, including mathematical symbols and formulae where needed. Great care has been taken over the defaults for the minor design choices in graphics, but the user retains full control.



### What is R Markdown ? {-}

According to [R Studio](www.rstudio.com):

> "R Markdown is a format that enables easy authoring of reproducible web reports from R. It combines the core syntax of Markdown (an easy-to-write *plain text* format for web content) with embedded *$R$ code chunks* that are run so their output can be included in the final document".





### What is Dynamic Reporting? {-}

From [Penn State Statistics](https://onlinecourses.science.psu.edu/statprogram/markdown): 

The traditional way to write a report:

1. Run your analysis in software, like SPSS or R and manually save our output
    * *i.e. saving the ANOVA table or using `pdf()` to save the graphs*  


2. Type your your description and interpretation in a text editor like *Word*
    * *either drag/drop tables and figures, or worse copy-paste and retype all the numbers*


A report written in this way can be problematic.  For instance, imagine your *Mentor/collaborator/journal reviewer*  telling you that they want to use a sub-sample instead of the entire sample. Or to include a nother variable.  You would have to redo all of your work!! 

Therefore, in this way **dynamic also means reproducible**, in the sense that people who get the file from you can reproduce the entire work in the report.






### Is this a popular method for creating reports? {-}

YES!

<div class="rmdlink">
<p>Check out <a href="http://rpubs.com/">Rpubs</a>. This website shares lots of documents written in the way we will introduce below.</p>
</div>




