# CSCI4800 Assignment 1

![Screenshot](img/smol-wink.svg)

**Names:** Tammy Husnetdinova and Alex Verkest<br>
<br>
**Class:** CSCI4800-E01 <br>
<br>
**Date:** 1/17/21 <br>
<br>
**Assignment:** 1 for Online Social Network <br>
<br>
**Scenario:** In the first step of building your final project web app, you’ve been asked to build static UIs for the web app and seek approval from an imaginary employer. The employer has a rough idea of the system they want, which they have already communicated with you, and you want first to build a blueprint of this web app to show it to them. The employer does not necessarily have a specific design in mind and has left that job to your team. You want to impress your employer with your design. <br>
<br>
**Learning objectives:** Our goal is to use our HTML5 and CSS3 skills to build a nice-looking UI that gives our employer an idea of the final website. Another goal in this class is not to learn one specific technology or a few commands or tags, but to use our knowledge to learn other concepts and put them into use as well. <br>
<br>
**Technologies used:** HTML5, CSS3, Javascript for code, Visual Studio Code for development and testing, Google Chrome browser for testing, Windows 10 OS <br>
<br>
**Justification in design choices:** Our social network site is heavily inspired by Reddit.com and its clean layout and user-friendly interface. Since Reddit is one of the standards of photo sharing sites it seemed like a great reference to start, but moving forward we'll start differentiating our design and create an identity for our social media site. Instead of different html pages we opted for modals for their clean design and more a more fluid experience when signing up and signing in, this approach while adding more moving pieces and being more of a challenge made for a more stylish sign in experience.  <br>
<br>
**Extra features:** Although it was not required, we decided to challenge ourselves by using bootstrap features that were new to both if us, such as modals for our sign in/sign up, pagination for search results, and dropdown menus for the homepage and search filtering. We decided to create links/references between our dummy/mockup pages, so clicking search will lead to the search results page, just like clicking on Settings in the main nav bar will lead to a settings page. With some extra time and momentum we picked up toward the due date, we also decided to start on some minimal javascript by adding a button that would allow for frictionless scrolling back to the top of the page. Bootstrap also came in handy there for styling the button itself. Finally, as another extra step, we created a separate directory for any images that will be used in this project. <br>
<br>
**Nu HTML Checker status:** Our html files pass the tests. There is one intended and known issue that comes up with the search button linking to the search results page. Since we do not yet have the javascript function to link to in the button like onclick="func()", we wrapped the button in a link reference to the search results page. We realize this is incorrect html, but we wanted to show off our search button in action. This is intentional for the purpose of this first assignment and will be fixed with proper html and javascript for a future version of this project. Below, you can see which line causes this issue: <br>

`<a href="search.html" class="btn btn-outline-success my-2 my-sm-0" type="submit"> Search </a>` <br>
<br>
**Check it out:** https://t-husnetdinova.github.io/webapp_spring2021_assignment1<br>
<br>
