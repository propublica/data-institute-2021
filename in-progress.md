# Data Institute 2021
For students of https://projects.propublica.org/graphics/ida-propublica-data-institute

Here are all of the materials we used to teach the 2021 Data Institute: slides, exercises, links, and homework.

Want to use our slides? Our teaching materials fall under the [same Creative Commons license](https://creativecommons.org/licenses/by-nc-nd/3.0/us/) we use across our site. [Get more details here.](https://www.propublica.org/steal-our-stories/)

# Curriculum

## Table of Contents
Click to jump directly to:
- [Install Party](#welcome-reception--install-party)

TKTK
- [Day 1: Intro to Data Journalism, Spreadsheets, Best Practices](#day-1)
- [Day 2: Evaluating data, Summarizing data](#day-2)
- [Day 3: Intro to Design, Github, and Data Visualization](#day-3)
- [Day 4: Intro to Code, How Websites Work, HTML, CSS](#day-4)
- [Day 5: Javascript, Preparing for the Future, Class Presentations](#day-5)

## What you'll need installed

Before class begins on Monday, you'll need to have signed up for the following accounts, and installed the following software on your computer.

**ACCOUNTS**

Go to each of these links and sign up for an account:

- **<a href="https://github.com/join?source=header-home">Github.com</a>**<br>After signing up, make sure to confirm your e-mail address too, otherwise you won't be able to use the account. Github is the site we'll be using to share code and teach you how to publish your own webiste.
- **<a href="https://accounts.google.com/SignUp?service=wise&amp;continue=https%3A%2F%2Fdrive.google.com%2F%23&amp;ltmpl=drive">Google.com</a>**<br>You probably already have Google account (if you have a gmail account, you're good). We'll be using Google Sheets the most, which you'll have access to from any Google account.

**SOFTWARE**

Go to each link and download the app onto your computer:

- <a href="https://www.google.com/chrome/browser/desktop/">**Google Chrome**</a>
  <br/>Everything we'll be teaching you about previewing and testing code will work in other browsers like Firefox, Safari, and Internet Explorer, but each browser designs how it works a little differently. Since we'll be demoing everything in Chrome, it'll be easiest for you to follow along.
- **Slack** (<a href="https://itunes.apple.com/app/slack/id803453959?ls=1&amp;mt=12">Mac</a>, <a href="https://slack.com/ssb/download-win">Windows</a>)
  <br/> All of you should have received an invite to join the Data Institute Slack. If you've never used Slack before, it's basically a place where you can message with a group of people. You need both an account (which you should be able to set up based on your email invitation) and we want you to download the desktop app (which you can do by clicking on the Mac or Windows link above).
- **Sublime Text** (<a href="https://download.sublimetext.com/Sublime%20Text%20Build%203114.dmg">Mac</a>, <a href="https://download.sublimetext.com/Sublime%20Text%20Build%203114%20x64%20Setup.exe">Windows</a>)
  <br/> This app is where we're going to be writing all our code. It's completely free, and will occassionally ask you if you'd like to pay, but payment is not required. For both beginners and experts, Sublime is one of the best apps for coding.

**OPTIONAL**

We won't be teaching these tools during class, but we highly recommend them and we want you to have easy access to them in case you need them in the near future. Your instructors will also be providing demo videos for how to use some of these tools.

- <a href="https://app.datawrapper.de/signin">**Datawrapper**</a>
  <br/> A great website for creating data visualizations without needing to code.
- **Tabula** (<a href="https://github.com/tabulapdf/tabula/releases/download/v1.2.1/tabula-mac-1.2.1.zip">Mac</a>, <a href="https://github.com/tabulapdf/tabula/releases/download/v1.2.1/tabula-win-1.2.1.zip">Windows</a>)
  <br/> Your best friend for when you have a huge stack of data tables in PDF format and need to turn it into actual data you can use.
- **Open Refine** (<a href="https://github.com/OpenRefine/OpenRefine/releases/download/3.4.1/openrefine-mac-3.4.1.dmg">Mac</a>, <a href="https://github.com/OpenRefine/OpenRefine/releases/download/3.4.1/openrefine-win-3.4.1.zip">Windows</a>)
  <br/> A great tool to help you clean data (ex: it can recognize that "Saint Paul" and "St. Paul" maybe refer to the same city in Minnesota)
	- If you're on a Mac, and you get the error that Google/Open Refine is damaged, [follow these instructions](open-refine-troubleshooting.md).


<hr/>

## Day 1
Monday, July 12

### Intro to Data Journalism
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/intro-to-data.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/intro-to-data.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/intro-to-spreadsheets.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/intro-to-spreadsheets.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/finding-data.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/finding-data.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/loading-data.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/loading-data.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/best-practices.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/best-practices.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/string-functions.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2021/string-functions.jpg"></a>


**Exercises**
- Learning how to sort with [PPP loan applications](https://docs.google.com/spreadsheets/d/1FMktt0503CZqShEfsm2z8m1AiVZmyrIgfzqkTgeFTJU/edit?usp=sharing)
- [Tabula](https://tabula.technology/)
- Advanced Spreadsheets: Pivot Tables with [child support data](https://drive.google.com/file/d/0Bw5Mt7QIQlsgc2tLdFlpQ2QwTXM/view)

**No Homework!**

## Day 2
Tuesday, July 13

### Analyzing Data

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/evaluating-data.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/evaluating-data.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/data-integrity.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/data-integrity.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/open-refine.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/open-refine.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/one-var.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/one-var.jpg"></a>


**Exercises**
- Evaluating data with [PPP loan applications](https://docs.google.com/spreadsheets/d/1FMktt0503CZqShEfsm2z8m1AiVZmyrIgfzqkTgeFTJU/edit?usp=sharing)
- Analyzing one variable with [school reportcards](https://docs.google.com/spreadsheets/d/1t6xnKivbM1l67vCWj4Aw_ickHmYG9yJmSliByMUlCoY/edit?usp=sharing)
- Advanced Spreadsheets: Combining Two Sheets with VLOOKUP, using [child support data](https://docs.google.com/spreadsheets/d/1cC_6Y6oV8YWHGtp_Fb6nDYQNYFJ-8Y0O7nnIZjBVvmc/edit?usp=sharing)

**No Homework!**


## Day 3
Wednesday, July 24

### Analyzing Data, continued

- [John Snow's map](http://matrix.msu.edu/~johnsnow/images/online_companion/chapter_images/fig12-5.jpg)
- [Census Geocoder](https://geocoding.geo.census.gov/geocoder/locations/addressbatch?form)
- [Bill de Blasio donors](https://docs.google.com/spreadsheets/d/17NlwDllhkKCDLa1cnKJDelQhcAjt4yRS2YJeQnGG-ao/edit#gid=0)
- [Datawrapper](https://www.datawrapper.de/)

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/HISTOGRAM-vs-BAR-CHART.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/HISTOGRAM-vs-BAR-CHART.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/mms.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/mms.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/two-vars.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/two-vars.jpg"></a>

<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/analysis-grab-bag.pdf"><img width="300" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2019/analysis-grab-bag.jpg"></a>


**Resources**
- [Numbers in the Newsroom: Using Math and Statistics in News](https://store.ire.org/products/numbers-in-the-newsroom-using-math-and-statistics-in-news-second-edition-e-version) by Sarah Cohen
- [Precision Journalism: A Reporter's Introduction to Social Science Methods](https://www.amazon.com/Precision-Journalism-Reporters-Introduction-Science/dp/0742510883) by Philip Meyer
- [Google Sheets Tutorials](https://training.npr.org/visual/what-to-do-with-a-big-pile-of-data/)






## Day 3
### Wednesday, July 14

### Intro to Design
<p>
<a href="https://lenagroeger.com/design_workshop" target="_blank">
  <img src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/design_intro.jpg">
</a>
</p>

**Lecture**
<ul>
  <li>What's Design Anyways?</li>
  <li>Design Principles: The Only 4 Rules You Gotta Know</li>
</ul>

**Exercises**
<ul>
  <li>Align This!</li>
  <li>Resume Redesign</li>
</ul>


### Type, Layout & Color
<p>
<a href="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/lectures/TypeLayoutColor.pdf" target="_blank"><img width="500" src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/type.jpg"></a>
</p>

**Lecture**
<ul>
  <li>Letter: The Many Faces of Type</li>
  <li>Text: How to Deal with Words</li>
  <li>The Grid: Putting the Pieces Together</li>
  <li>Colors &amp; How to Pick 'Em </li>
</ul>



**Exercises**
<ul>
  <li>Name that Font!</li>
  <li>Type Crimes</li>
</ul>


### Let's make a webpage!

<p>
<a target="_blank" href="http://lenagroeger.com/makeawebsite/"><img width="500" src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/online_portfolio.jpg"></a>
</p>

**Exercises**       
<ul>
  <li><a target="_blank" href="http://lenagroeger.com/makeawebsite/">Making a website</a></li>
  <li>Getting your portfolio on the internet!</li>
  <li>Using the GitHub Desktop app</li>
</ul>

### Visualizing Data
<p>
  <a target="_blank" href="https://lenagroeger.com/visualizing-data/"><img width="500" src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/visualizing_data.jpg"></a>
</p>

**Lecture**
<ul>
  <li>Bars</li>
  <li>Lines</li>
  <li>Scatterplots, Small Multiples, and More!</li>
</ul>


### Let's Make Some Charts & Maps!

<p>
  <a href="https://lenagroeger.com/datawrapper/"><img width="500" src="https://propublica.s3.amazonaws.com/projects/datainstitute/lena/imgs/datawrapper.jpg">
  </a>
</p>

**In-Class Demos**  
<ul>
  <li>From data to charts in Google Sheets &amp; Data Wrapper</li>
</ul>



### Homework
<ul>
  <li>Using the principles we discussed today, redesign your resume. Email the before and after version to <a href="mailto:lena.groeger@propublica.org">lena.groeger@propublica.org</a>.</li>
  <li>Using everything you've learned about design, type & layout, keep working on your portfolio HTML page. Then, since you've learned how to make a working webpage on the internet, upload your page to Github.</li>
  <li>Here's <a target="_blank" href="http://lenagroeger.com/resources/">Lena's big list of resources</a> that may come in handy next week.</li>
</ul>




## Day 4
### Thursday, July 25

### Intro to Code
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/intro-to-code.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/intro-to-code.jpg"></a>

**In-Class Demos**
- What coding languages have you heard of?
- Using the web inspector

### How Websites Work
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/how-websites-work.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/how-websites-work.jpg"></a>

**In-Class Demos**
- How the Internet passes websites around
- What HTML, CSS and Javascript contribute to a webpage

**Exercises**
- Drawing a Website

### HTML
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/html.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/html.jpg"></a>

**In-Class Demos**
- How to create your first HTML file
- Shortcut to the basic HTML template
- How to use:
  - `<h1>`
  - `<h2>`
  - `<h3>`
  - `<p>`
  - `<img>`
  - `<a>`
  - `<ul>`

**Exercises**
<ul>
  <li>Copy and paste <a href="https://codepen.io/sisiwei/pen/KzLezJ?editors=1000">this code</a> and follow the instructions inside to format the page.</li>
  <li>Can you fix this <a href="https://codepen.io/sisiwei/pen/PNvaeB?editors=1000">broken code</a>? </li>
</ul>

### Basic CSS
<a href="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/css.pdf"><img width="500" src="https://projects.propublica.org/graphics/images/data-institute/presentations/2017/css.jpg"></a>

**In-Class Demos**
<ul>
  <li>How to create your first CSS file</li>
  <li>Shortcut to linking to your CSS file</li>
  <li>How CSS styles work</li>
</ul>

**Exercises**
<ul>
  <li>Using your practice HTML file from before, add CSS styles to it such you change the:
    <ul>
      <li>color</li>
      <li>font-family</li>
      <li>font-size</li>
    </ul>
  </li>
  <li>On your own, look up how to do the following in CSS, and add it to your HTML file as well:
    <ul>
      <li>underline text</li>
      <li>bold text</li>
      <li>italicize text</li>
    </ul>
  </li>
  <li>Going back to the Supreme Court article you formatted earlier, do the following using CSS:
    <ul>
      <li>Make the main headline dark red.</li>
      <li>Use the font family "Georgia" for the main headline and the subheadline.</li>
      <li>Center the text of the main headline and the subheadline.</li>
      <li>Give the paragraphs a line height of 19 pixels.</li>
      <li>Remove the underline from the links.</li>
      <li>Make the "Related articles" label all uppercase.</li>
      <li>Bonus: Make an underline appear when you hover over a link.</li>
    </ul>
  </li>
</ul>

### CSS Classes

**In-Class Demos**
<ul>
  <li>How to write your own CSS Class</li>
  <li>How CSS deals with conflict</li>
</ul>

### Optional Homework

Only for those of you who have time and are looking for an extra challenge.
<ul>
  <li>Save <a href="https://codepen.io/sisiwei/pen/bpXwMB?editors=1000">this HTML</a> onto your computer. Link to a new CSS file that you create. Write CSS to make the end result look like <a href="http://projects.propublica.org/graphics/images/data-institute/presentations/mars.jpg">this image</a>. You may only write CSS. You cannot edit the HTML file.</li>
</ul>





## Day 5
### Monday, July 29

### Javascript and JQuery

**Review**  
- Making a Website with Cards ♠️

**In-Class Demos**  
- How to setup Javascript
- How to add jQuery, set it up, and use it ([A good place to review what we're learning](https://www.w3schools.com/jquery/jquery_intro.asp))
- Ida Demo: [Starting with this HTML and CSS](https://codepen.io/sisiwei/pen/ZWdXGw), let's build the JS together.
