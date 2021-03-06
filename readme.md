## SOS - StackOverflow Search



<a href="https://www.npmjs.com/package/so-search">
    <img src="https://img.shields.io/npm/v/so-search.svg"
         alt="npm version">
</a>
<img src="https://img.shields.io/github/license/felipenmoura/sos-stackoverflow-search.svg"
         alt="License">
<img src="https://img.shields.io/travis/felipenmoura/sos-stackoverflow-search.svg"
         alt="Travis Build" style="float: left; margin-right: 5px;">
<a href="https://github.com/issues/felipenmoura/sos-stackoverflow-search/issues" style="float: left; margin-right: 5px;">
    <img src="https://img.shields.io/github/issues/felipenmoura/sos-stackoverflow-search.svg"
             alt="Open Issues">
</a>
<img src="https://api.codacy.com/project/badge/grade/96b7db1e3c5d49d98295b6f450050602"
             alt="Code quality">


This is a terminal tool for you to search for answers in [http://stackoverflow.com/](stackoverflow) never leaving your natural habitat!

#### How to use it

Just type `sos` and your question.<br/>
Let's say you are facing a problem rendering an HTML5 canvas!

`$ sos error rendering html5 canvas`

Anything you pass after the `sos` command, will be treated as your question.

![SOS Stackoverflow Search in terminal](https://raw.githubusercontent.com/felipenmoura/sos-stackoverflow-search/master/sos-screen-recording.gif)

#### Advantages

- straight in your terminal
- don't need to open another tab in your browser
- highlights code (valid javascript codes, css and html)
- takes in consideration italic, bold, links, lists and blockquotes
- shows only questions that have a correct answer
- shows the answer itself in the terminal
- adds a link for you to (ctrl/cmd)+click and open the page in your browser

#### Installing

To install it, simply install it globally:

`$ npm install -g so-search`

