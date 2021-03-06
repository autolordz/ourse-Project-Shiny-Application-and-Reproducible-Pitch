Digits Manipulating of Shiny Project
========================================================
author: Autoz
date: 2018-7-22
autosize: true

Introduction
========================================================

> Coursera-Course-Project-Shiny-Application-and-Reproducible-Pitch

- This Repo contains R codes and Markdown files for Shiny Project of
Coursera Developing Data Products course. 

- The application contain three part of malipulating and tuning MNIST Digits image data.

- The images were refered to their original IDX format from
<http://yann.lecun.com/exdb/mnist/>. Dataset is from [`mldata`](http://mldata.org/). It is a public repository for machine learning data, supported by the PASCAL network.Fetch [`MNIST DATA`](mnist-original.mat) from but mldata seens can not access so redirect to another links.

- Project Shiny App on ShinyApp.io please visit [`PROJECT LINK`](https://autolordz.shinyapps.io/DigitsManipulate/).

Outline
========================================================

- Statistics of the distance of two Digits of certain n umber.
- Comparing with PCA compressed and PCA high dimentions compressed.
- Show the most similar images of Digits with certain Digit.

Shiny App R Codes and Guide on  github please visit [`GITHUB REPO`](https://github.com/autolordz/Course-Project-Shiny-Application-and-Reproducible-Pitch).

Shiny files
========================================================

- `app.R`
    - `show_compared_img func`
    - `show_compress_img func`
    - `show_recommend_img func`
    - `ui func`
    - `server func`
    - `others func`
- `ShinyDigitSliders.Rpres`

Display Compared Images
========================================================

Display screenshots about Compared Images and Plot summaries distances between two certain Digit numbers.

![](ComparedDigits.png)

Display PCA Compress Images
========================================================

Display screenshots about Compared Images or summary distance between two certain Digit numbers. You can choose PCA (if n > p)and PCA high dimension (if p >> n) method to compress.

![](PCADigits.png)

Display Similar Images
========================================================

Display screenshots about Similar Images with certain Digit numbers. It can select different certain Digit numbers and sample range for illustrating how similar with current Digit.

![](SimilarDigits.png)

**END**
