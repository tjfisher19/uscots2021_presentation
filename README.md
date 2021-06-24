var createDownloadLink = require('create-download-link');

var opt = {
    data: 'Here is the content of the file',
    title: 'Click to download your file',
    filename: 'example.txt'
};

var anchor = createDownloadLink(opt);

# uscots2021_presentation
Materials for the USCOTS 2021 Breakout Session

## A second course in statistics: Bridging data science and statistical modeling

Materials for the USCOTS 2021 breakout session, "A second course in statistics: Bridging data science and statistical modeling," will be made available here.

## Materials for Session

* Viewing access to the slides
* Participants are highly encouraged to download the Markdown file <a href="data:application/octet-stream,DATA" download="https://raw.githubusercontent.com/tjfisher19/uscots2021_presentation/main/uscots_assignment_starter.rmd">Tom</a>
* 
* <a id="raw-url"  href="https://raw.githubusercontent.com/tjfisher19/uscots2021_presentation/main/uscots_assignment_starter.rmd" download="uscots_assignment_starter.Rmd">uscots_assignment_starter.rmd</a> and participate in the session.
* A fully worked out (solution set) version of the assignment is available for <a id="raw-url"  href="https://raw.githubusercontent.com/tjfisher19/uscots2021_presentation/main/uscots_assignment_completed.html">download</a>.

## Schedule of our session

**<i>2:30-2:33</I>** - Presenter introductions

*2:33-2:50* - **Class time!** - We will present some materials using an RMarkdown file. The materials are chosen to reasonably mimic a typical class.



*2:50-3:15* - Class structure discussion. We will overview the history of the class including its recent increase in enrollment and the adoption of pseudo-inverted classroom design.

*3:15-3:35* - Back to class, participants will go to Zoom Breakout rooms to have the opportunity to work on the "in-class assignment". The three presenters will work as faculty hopping around breakout rooms to help and discuss.

*3:35-3:45* - Open discussion of all that is covered. 


## Software needed

In this session we will be using the R language for Statistical program and RStudio. Specifically we will be working with RMarkdown. For those interested in participating please install:

* R from https://cran.r-project.org/
* RStudio from https://rstudio.com/

### R Packages

In addition to the base language of R, we will use the following add-on packages

* tidyverse
* ggfortify
* GGally
* knitr

You can install all these packages in R/RStudio with the comment `install.packages(c("tidyverse", "ggfortify", "GGally", "knitr") )`.  If asked to install from source, selected No.

## Textbook

The course that will be discussed in this Breakout session, STA 363, uses this <a href="http://users.miamioh.edu/fishert4/sta363/">online text</a> authored by two of the presenters. 

