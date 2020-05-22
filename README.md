# Project Slide Design

## Introduction

If the goal of your presentationn is to convince an employer of your credability, you do not want anything distracting from your work. Design aspects can be distracting, particularly:
- inconsistencies in style
- heavy text & clutter
- messy visualizations

## Learning goals

In this lesson, you will:
- identify what slide components count as "style"
- to describe the impact of a slide template
- declutter slides by removing excessive text and redundant visualizations
- define the characteristics of a "complete" visualization

## Identify what slide components count as "style"

The goal of your presentation is to convey a _professional_ **style**. A _professional_ presentation style demonstrates that you pay attention to detail and are aware how the _design_ of your slides will impact the viewer as much a _content_. Font choices, font consistency, font size consistency, choice of colors, and choice of graphics all contribute to the design and style of your presentation. Your **choices** and **consistency** can either enhance or distract from your material. 

### The messy example
The two slides below have a few examples of inconsistent style. 

[numbered picture]

1. Font choice
2. Excessive colors
3. Inconsistent choices

A simple solution is to use a _slide template_. There are great websites such as [SlideCarnival](https://www.slidescarnival.com/), that provide professional-quality [templates](https://www.slidescarnival.com/thaliard-free-presentation-template/2189) made by designers.  A good template keeps the font, sizes, and color schemes consistent. Since few data scientists also have a degree in design, using the right template saves your presentation from lookinng unprofessional.


## Declutter slides by removing excessive text and redundant visualizations
Challenges: Visualizations are a mess
Solution: Checklist of things to think about, Python GraphViz link

## Define the characteristics of a "complete" visualization

### Slide review:

[Lindsey - review text below]

On the slide [X] of the messy presentation[or maybe just "in this sample visualization from the messy presentation and show image], there are 4 aspects that if fixed, would enhance the credibility of this presentation. Take a moment to see if you can identify what is missing from this visualization.

### The identified issues

As you can see in the numbered picture, the visualization(s) has the following issues:

[visual, with at least these issues]

- using the default seaborn rainbow colow-scheme. Color should be informative and a labeled bar chart is not enhanced with colors. A  proper use of color would be to use it  to highlight *one* bar to differentiate it from the rest.
- the y-axis is in scientific notation and not interpretable
- axis labels are either missing or the raw-variable names rather than a nice label

[Visual A] was created using the following code:
```

example code
```

### What every visual should have

David McCandless, from the website [Information is Beautiful](https://www.informationisbeautiful.net/), in his 2014 book [Knowledge is Beautiful](https://informationisbeautiful.net/books/) that a quality visualization contains four ellements: information, function, visual form, and story.

![quall-viz](https://infobeautiful4.s3.amazonaws.com/2015/05/2552_What-Makes-a-Good-Infoviz-frame01.png)

[Lore - how else do i need to cite this?]

every visualization should have:

- [ ] A point. The visualization is relevant to the analysis and fits into the narrative of the presentation. The most **important** part of the visualization should be highlighted. Is this one group different from the others? Where does this model _not_ perform well?
- [ ] Everything appropriately labeled. Each axis, a legend, a title, they should all be identified and labelled appropriately.
- [ ] Axis numbers and scales that people can understand. Dolllars should have a $ in front of them. Percents should be formated as 50% rather than 0.5. Scientific notation has no business on 99% of data visualizations produced by Flatiron School graduates
- [ ] Readable text. Text is not too small and does not overlap with other text. All text is _meanginful_, so am axis labe; should read "House Sale Price" rather than "salesprice."
- [ ] Been saved as a png or jpeg and then inserted into your presentation. Using a screenshot can produce fuzzy and grainy resolution if the image needs to scaled.

[Lindsey, did I miss anything?]

* For further reading on what makes a great data visualization, David McCandless also provides a great [recommended reading list](https://informationisbeautiful.net/visualizations/dataviz-books/) of data visualization books.

### Enhancing the viualization

The [Python Graph Gallery](https://python-graph-gallery.com/) is a great resource for finding the exact code to enhance a visualization created using matplotlib or seaborn. The [matplotlib documentation](https://matplotlib.org/) also has plenty of code examples and the [seaborn graph gallery](https://seaborn.pydata.org/examples/index.html) is also a useful resource.

Compare the updated visualization code used to enhance Visual A to create Visual B.

```
more code
```
[Visual B]

## Summary:

Small changes can have a big impact on the profesional quality of your slide design. There are many resources out there to help your slides be more consistent, polished, and informative.
