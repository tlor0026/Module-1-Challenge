# 01 HTML, CSS, and Git: Code Refactor

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
THEN I find semantic HTML elements - Restructred some elements on the HTML. It was all DIV's, after looking through the HTML i was able to identify which areas should be "sections" (Sementic HTML Element) and replaced them in the HTML. I also added the header area along with changing the lists to NAV.

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning - I went through the CSS style sheet and moved things around to where i belive it should be to make things easier to read. i belive they should follow in order in terms of how its set in the HTML.

WHEN I view the icon and image elements
THEN I find accessible alt attributes - Went over the HTML and added alt texts to all the img elements.

WHEN I view the heading attributes
THEN I find that they fall in sequential order - went in and put in "ID" for search engine optimization so that the headers nav list item will go to it went clicked/used. Also redid the header and changed it to NAV so that it could be read as navigation. Made changes to the CSS sheet in order to make the NAV area look appropiate.

WHEN I view the title element
THEN I find a concise, descriptive title - I changed the title over to Horiseon.
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a professional README describing the project.

- - -
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
