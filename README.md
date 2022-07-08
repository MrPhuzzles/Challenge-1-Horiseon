# Challenge 1 - Horiseon


## James' Notes on Challenge 1
This weeks challenge looked a little overwhelming at first. But once a few classes were under my belt it was ready to be tackled!

I started by implementing semantic tags in the index.html file where necessary. i.e. header at the top, footer at the bottom. I put a nav tag inside the header so it was clear there was a difference to the other elements inside. 
I replaced some div tags with section tags to make the blocks of code easier to follow and separated. 
I thought about replacing the div tags inside each section with article tags, but there wasn't a lot of contents in them so it didn't seem too pertinent or beneficial in this particular scenario.
I also noticed at this time that one of the nav bar links was not functioning correctly. The div it pointed to had no ID attribute, so I added one of those in.

Next I took a look at what I was dealing with when it came to the css file controlling the styles. 
On first approach I noticed a lot of the same styles applied to different sections but in separate blocks of code written multiple times. So I grouped those up and added comments in as I went. Doing this altered the class name of said style, so I went back into the index.html file and altered the classes as needed.
I also needed to alter the image to be a little bigger in height. I adjusted it to 1300px which seemed to be close to what was asked of. 

Once this was changed I verified that everything was still in working order compared to the original files provided and we were good to go. Before submitting I added some comments into the index.html file so that everything was noticeable and easy to read, and I noticed the title was very generic, so I changed it to state the company's name.

Before deploying I decided to select the header and footer in css using type selector instead of class to follow a more semantic structure. I left the header and footer classes in the html however, just in case the company decides to add pages later.

After that it was all ready to be deployed [here](https://mrphuzzles.github.io/James-Tietjen-Challenge1/). 

This is what it looks like if you don't necessarily want to follow that link! ^^^

![Horiseon screenshot](./Screenshots/Horiseon%20Screenshot.png)
![Horiseon screenshot 2](./Screenshots/Horiseon%20Screenshot%202.png)



## 01 HTML, CSS, and Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities and/or socio-economic restrictions have access to their website. Accessible websites are better optimized for search engines, and help companies avoid litigation.

For this week's Challenge, your task is to refactor an existing webpage to make it accessible and to improve SEO. It's important to follow the Scout Rule when working with an existing codebase: Always leave the code a little cleaner than you found it. 

To impress the imaginary client for this Challenge, you should go the extra mile and improve their codebase for long-term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, such as by consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Remember when working with a client, it is essential to read the acceptance criteria for guidance and clarity on what the client expects, especially when asked to make a judgment call, such as when an icon needs an accessible alt tag and when it is okay to leave it blank. 

To successfully complete this week's Challenge, all acceptance criteria must be fully addressed!

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a professional README describing the project.

- - -
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
