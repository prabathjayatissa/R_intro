# Data analysis for beginners in R

Expert Skills Training the LBG Career Center

March 6, 13, 20 and 27, 2024, Wednesdays 10am-12pm

## Who am I?

My name is Hannah Metzler, and I am currently a PostDoc at MedUni Vienna and the Complexity Science Hub Vienna. I have a background in Psychology and Cognitive Neuroscience, and I currently do research in computational social science at the interface of Psychology and Data Science.

Email: metzler[at]csh.ac.at

Website: <https://hannahmetzler.eu>

## What is this course about?

This course will introduce you to coding your data analyses and data visualizations with the software R. It is geared for people who know the basics of statistics, but have never written code before. We will set up R, Rstudio and Git, learn how to wrangle and clean data, how to make pretty plots, and how to do basic statistics (descriptives, t-tests, ANOVAs, regressions etc.) in R.

If you have had doubts if you'd be able to write code, but secretly have been wanting to for a long time, this course is for you. In my experience, it seems more challenging and less fun initially than it later turns out to be! Coming from a social science background myself, I want to help others jump over the barrier of self-doubts and make it easy for you to start writing your own code.

## To do before the first class:

### 1. Download and install R

-   **R** is the data analysis program we will use: <https://cran.rstudio.com/>

-   Click "Download R for macOS" (or Ubuntu/Windows), then:

    -   Windows: click on **base**, then [Download R-4.3.2 for Windows](https://cran.rstudio.com/bin/windows/base/R-4.3.2-win.exe), then install
    -   For macOS 11 & higher: click on [R-4.3.2-arm64.pkg](https://cran.rstudio.com/bin/macosx/big-sur-arm64/base/R-4.3.2-arm64.pkg), for earlier versions: [R-4.3.2-x86_64.pkg](https://cran.rstudio.com/bin/macosx/big-sur-x86_64/base/R-4.3.2-x86_64.pkg), then install
    -   Ubuntu: follow the provided instructions (copy each code line into your Bash Terminal (=Console) & press enter, enter your Laptop log in password when prompted

### 2. Download and install Rstudio

-   Rstudio is the visual interface: <https://posit.co/download/rstudio-desktop/>

-   Choose version: Windows10/11, macOS12+, Ubuntu20, Ubuntu22

-   Install

    -   for Ubuntu: make sure the file is in your Downloads folder, then execute in your Terminal: sudo apt-get install \~/Downloads/RSTUDIO-2023.12.1-402-AMD64.DEB

-   Open Rstudio to see if it worked.

-   If you have trouble installing, write to me at metzler[at]csh.ac.at before 12pm on Tuesday March 5th

### 3. Configure Rstudio

-   Under the **Tools** menu, go to **Global Options...** and uncheck the box that says **Restore .RData into workspace at startup**, and set this to **Never**.
-   This ensures you always start with a clear workspace, instead of loading data from your last coding session.
-   More explanations on why this is useful in section 1.3.3 [here](https://psyteachr.github.io/reprores-v3/intro.html).


## Course materials

-  [Introduction slides](https://hannahmetzler.eu/R_intro/Course_overview/Overview.html)
-  [Lesson 1](https://hannahmetzler.eu/R_intro/Lesson_1/Lesson1.html) (Download [Quarto file](/Lesson_1/Lesson1.qmd))
- [Preparation for Lesson 2](https://hannahmetzler.eu/R_intro/Lesson_2/Install_Git_GitHub/Git_Github.html). Please follow this to setp up Git and GitHub before our next session. 

## License

This work is licensed under Creative Commons Attribution-ShareAlike 4.0 International License. ([CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)).

## Acknowledgement & Resources

This course is based on a free online course book:

Lisa DeBruine & Dale Barr. (2022). [Data Skills for Reproducible Research:](https://psyteachr.github.io/reprores-v3/index.html) (3.0) Zenodo. <doi:10.5281/zenodo.6527194>

You can use it to repeat lessons, understand something better, or catch up if you miss a class.

There are a variety of other free online classes on R, some including an introduction to statistics. You can find a list of courses I have found useful [here](https://github.com/hannahmetzler/R_intro/blob/main/Resources.md). If a course has not been updated recently, it is quite likely that some things have changed, as R and its packages are regularly updated. Most things will still work, however.
