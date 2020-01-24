## 1. What is this?

The purpose of this project was to learn how to work with hero image/video, implement an accordion menu and a signup form with some validation.
These were the requirements for the project:

* Site should have a header with responsive image/video, a signup form, and a FAQ accordion.
* The form should should also post the form data into into a service called HTTPbin and it should show the data you put in.
* The form should contain all or some of these:
    * 2 x Text fields
    * 1 x A password field
    * 1 x Set of radio buttons
    * 1 x Set of checkboxes
    * 1 x Submit button
* The website should also have an accordion menu, meaning an area that can collapse to show and hide text. The accordion should fulfill the following basic requirements:
    1. Click a section title to expand its description.
    2. Click the title again to collapse the description.

These were some suggestions for a deep-dive in this project:

* Try out some other form elements or input types.
* Add some validation to the form.
* Add a header and/or a button on top of your video by using position: absolute and z-index to get everything in the right place.
* Make every other row in the accordion have another background color.

## 2. What did I do?

I've focused on the form implementation first and some basic validation. The hero video was added to the entire screen and the header position was adjusted using absolute. 
There's a simple JS script to control the display/hide of different containers. The accordion menu is under the FAQ section and I've used the adjacent sibling combinator to add a class that helps hiding/display the content under a section.

## 3. Where can you see it in action?

You can see the project [here](https://wonderful-murdock-e1473d.netlify.com).
