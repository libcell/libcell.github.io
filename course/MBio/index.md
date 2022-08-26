--- 
title: "rstudio4edu"
subtitle: "A Handbook for Teaching and Learning with R and RStudio"
author: 
- Desirée De Leon^[RStudio, https://desiree.rbind.io/]
- Alison Hill^[RStudio, https://alison.rbind.io/]
date: "2022-08-26"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
cover-image: images/logo/logo-rstudio4edu.png
github-repo: "rstudio4edu/rstudio4edu-book"
description: "A work-in-progress"
favicon: "images/favicon/favicon.ico"
always_allow_html: yes
url: 'https\://rstudio4edu.github.io/rstudio4edu-book/'
---

# Preface {-}



<center>![](images/illos/index-hi.jpg){width=60%}</center>


Welcome! If you do educational work and use tools in the data science ecosystem, you may have seen a great tutorial made with R Markdown, or attended a streamlined workshop where learning the content was front-and-center and all the headaches around installation and setup were absent. Or maybe you have stumbled upon a polished workshop, book, or course website and thought: __"I want to make that too!"__ So that is what we have set out to do: make a handbook that will fill in those gaps for educators to create educational materials that engage learners, inspire other educators, and most importantly save you time and make it more fun for you to teach.

This handbook was inspired by the [Handbook for Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/)- a book written by and for educators who teach data science. It is a thoughtful and inspiring resource for all educators, with a focus on the Python ecosystem. We aimed to create a similar resource for educators working with the R and RStudio ecosystem. 

If you find our materials useful, give us a shout-out on Twitter using `#rstudio4edu`. We hope you do! If you have ideas for ways to improve them, please consider contributing to the project.


## Why `rstudio4edu`? {-}

Educators from a range of fields use R and RStudio in the "classroom." But the definition of the "classroom" is changing. 

The classroom can be an actual one that includes real-time interaction with learners, as in school and university settings. 

Or the classroom can be a virtual one, where learners interact asynchronously with educational materials. For example, learners on their own time can peruse an online tutorial, or they can attend a remote webinar-style workshop where real-time interactions simply aren't part of the education experience.

Finally, there are temporary classrooms- those that pop up like food truck pods. Learners pick a truck to decide what they want to learn, they get served up some educational materials and enjoy it in real-time with an instructor and other learners. The hope is that they pack up some knowledge "to go boxes" that they will put into practice when the instructor is long gone.

We know that [this is the case for] people in fields like ecology, sociology, digital history, psychology, biology, genetics, neuroscience, pharmacology, and bioinformatics for education- not just those who teach data science or statistics.

Other answers to "why":

1. Better aesthetics, better engagement (draw attention vs distract)

1. Build up modern educator toolbox with relevant materials (in general, be a bad-ass educator :)

1. Empowering to own your content, and therefore own your learners' experience


## Philosophy {-}

<img src="images/illos/index-welcome.jpg" width="70%" style="display: block; margin: auto;" />

Paraphrasing from Jenny Bryan and Jim Hester's ["What They Forgot to Teach You About R"](https://whattheyforgot.org/index.html):

> *"We focus on building holistic and project-oriented workflows that address the most common sources of friction in creating educational materials, __outside of doing the teaching itself__."*


1. **Just in time learning:** we aimed to show educators how to use tools that you need, as you need them. We encourage you to take an "à la carte" approach to this handbook- skim the table of contents, take what you need when you need it, and skip what you don't need (until you decide that you do!).

1. [**Eat cake first**](https://bit.ly/let-eat-cake): we try to show you the quickest, simplest way to do something you need to do right off the bat. Some of the time, there is a better but more complex workflow that you *could* adopt later, so we have tried to point you in that direction too. But in general, we aim for starting with "good enough" practices instead of "perfect." 

1. **Get your hands dirty:** we want you to be able to make everything we show you. So we've built a lot of different ways for you to get your hands dirty right away, like demo repositories you can clone and deploy "out of the box", templates you can customize, and lots of example content. We hope these will inspire you to experiment, play, and create.



## Who are you? {-}

<img src="images/illos/index-who-are-you.jpg" width="80%" style="display: block; margin: auto;" />

Who did we make this handbook for? We envision that this handbook is for all end-user teachers: teaching may or may not be part of your formal job description, you may not have formal training in how to teach, and you may teach in a formal classroom setting, but you may also teach virtually (via webinars or online tutorials), or perhaps you teach in short but intense bursts like in-person workshops and small-group trainings. 

In short, if you are a person who needs or wants to create educational materials using R / RStudio, then we hope you'll find this handbook useful- it is definitely for you.

1. **Lucy:** Lucy is a professor of neuropsychology who also teaches stats to first year graduate students. She is comfortable using R in her research but experiences imposter syndrome when in conversation with colleagues who have had formal training in computer science. She'd like to learn how to use R in her course in a way that won't overcomplicate things for students and will maximize instruction time (and minimize set up time). Lucy is juggling half a dozen responsibilities at work, and doesn’t have a lot of time to learn or test out many new systems for delivering her teaching content. 

1. **Willis:** Willis Workshopper is a senior data scientist and is responsible for training his (remote) company's team and occasionally leads in-person workshops. Willis considers himself an experienced programmer. He uses R all the time for analysis, but needs a platform that will allow him to create and organize one-time training materials-- he'd like all materials to be easily implemented by users in both remote (work team) and in-person (workshop) contexts. He can be particular about his material's aesthetics and layout and wants the ability to customize everything. 

1. **Ona**: Ona heads a team that assists researchers and organizations design and track their project progress. She needs to train up her team of employess who have different R skill levels (sometimes none). Ona knows R but would not call herself a programmer, and she essentially knows nothing about web development. She has been emailing R files back-and-forth with team members as a means of sharing results and analysis, but she knows there has to be a better way to do this. When she tries to dive into resources to learn once and for all how to create a better system, she feels overwhelmed and lost. Additionally, her team is limited in budget and time and does not have have the energy to absorb longform manuals.


## What is in this handbook? {-}

Some high-level organizational highlights, like:

+ The first section "For all educators" includes blah. 

+ The next section on "Creating educational content" goes deeper into the R Markdown package, including complementary packages, tools, and worflows, for making new educational content using R and RStudio.

+ In "Creating educational projects", we provide a roadmap for navigating some of the R Markdown extension packages that are designed for projects with collections of R Markdown documents (as opposed to a single document). We offer some perspectives specific to educators to help you decide which projects work when. 
    + Note: we provide step-by-step guidance for how to actually use these packages in the "Cookbooks" sections later in the book.
  
...

+ The last sections of the book are our cookbooks for educators. Although learning materials for many of these recipes already exist in various palaces, they are often difficult to discover and not designed with educators in mind. We aimed to highlight the most useful features, using input from R and RStudio educators with years of teaching experience.

Finally, we want to point out a few pragmatic features (could include a diagram here to help aid usability?):

1. For every chapter you can download the `.Rmd` source file that created it by clicking on the download button <i class="fa fa-download"></i> in the upper toolbar. 

1. The button to the left <i class ="fa fa-edit"></i> allows you to edit (say more about how this works). 

1. Clicking on the GitHub icon <i class = "fa fa-github"></i> on the far right takes you to the source repository for this book. 

1. How to search within this book: https://github.com/rstudio/bookdown/issues/216. You can click on the <i class="fa fa-info"></i> see the instructions.

## What did we leave out? {-}

on purpose

* Shiny

* Pedagogy- we think this is very well covered in other resources. In particular, we recommend [*Teaching Tech Together*](http://teachtogether.tech/) by [Greg Wilson](http://third-bit.com/), as well as his "What to Read Instead" [book recommendations](http://teachtogether.tech/#s:intro-instead). [Software Carpentry](https://carpentries.github.io/instructor-training/) also has a very popular and effective two-day instructor training workshop that we highly recommend.

https://openlearning.mit.edu/mit-faculty/research-based-learning-findings


## Who are we? {-}

This 

## Contributing {-}

I love this resource: https://edav.info/contribute.html

:::rstudio-tip
Through the book, we highlight specific ways that RStudio can expedite your package development workflow, in specially formatted sections like this.
:::

:::tip
RStudio exposes `load_all()` in the *Build* menu, in the *Build* pane via *More > Load All*, and in keyboard shortcuts Ctrl + Shift + L (Windows & Linux) or Cmd + Shift + L (macOS).
:::

:::gotcha
Watch out for "gotchas" along the way. We try our best to point out the tricky bits of a workflow.
:::

:::design
In tip boxes like this one, we'll point out design tips, to help you keep your page looking looking ✨fresh ✨.
:::

:::hat
These tips highlight advice and tricks from community members.
:::

