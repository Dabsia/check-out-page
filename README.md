<!-- Please update value in the {}  -->

<h1 align="center">{Your project name}</h1>

<div align="center">
   Solution for a challenge from  <a href="http://devchallenges.io" target="_blank">Devchallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="https://{your-demo-link.your-domain}">
      Demo
    </a>
    <span> | </span>
    <a href="https://{your-url-to-the-solution}">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenges/0J1NxxGhOUYVqihwegfO">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [Built With](#built-with)
- [Features](#features)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- OVERVIEW -->

## Overview

![screenshot](https://user-images.githubusercontent.com/16707738/92399059-5716eb00-f132-11ea-8b14-bcacdc8ec97b.png)

Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- Where can I see your demo?
- What was your experience?
- What have you learned/improved?
- Your wisdom? :)

### Built With

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- [React](https://reactjs.org/)
- [Vue.js](https://vuejs.org/)
- [Tailwind](https://tailwindcss.com/)

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges) challenge. The [challenge](https://devchallenges.io/challenges/0J1NxxGhOUYVqihwegfO) was to build an application to complete the given user stories.


## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/your-user-name/your-project-name

# Install dependencies
$ npm install

# Run the app
$ npm start
```

## Acknowledgements

<!-- This section should list any articles or add-ons/plugins that helps you to complete the project. This is optional but it will help you in the future. For exmpale -->

- [Steps to replicate a design with only HTML and CSS](https://devchallenges-blogs.web.app/how-to-replicate-design/)
- [Node.js](https://nodejs.org/)
- [Marked - a markdown parser](https://github.com/chjj/marked)

## Contact

- Website [your-website.com](https://{your-web-site-link})
- GitHub [@your-username](https://{github.com/your-usermame})
- Twitter [@your-twitter](https://{twitter.com/your-username})
:root{
    --bgColor: #f2f2f2;
    --h1Color: #4E5150;
}
body{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: Montserrat;
}
.wrapper{
    background-color: var(--bgColor);
    border-radius: 10px;
    margin: auto 13px auto 12px ;
    
}
img{
    width: 160.71px;
    border-radius: 20px;
    margin: 30px auto auto 20px;
}
h1{
    font-family: Montserrat;
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 29px;
    color: var(--h1Color);
    margin: 32px auto 21px 18px; 
}
.counter{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 122px;
    border: 1px solid #828282;
    border-radius:12px ;
    margin-right: 42px;
    margin-left: auto;
}
button{
    height: 20px;
    margin: auto;
    box-sizing: border-box;   
}
.item{
    display: flex;
}
.items-desc{
    margin-left: 20px;
    margin-top: 20px;
}
span{
    display: flex;
    margin-bottom: 18px;
    
}
.original-price{
    margin-right: 20px;
    color: #F2994A;
}
.discount{
    text-decoration: line-through;
    font-size: 10px;
    font-weight: 600;
    font-size: 10px;
    line-height: 12px;
    text-decoration-line: line-through;
}
