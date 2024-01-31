# Module 1 - HoriSEOn Accessibility Refactor

## User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

## Acceptance Criteria
GIVEN a webpage meets accessibility standards...

WHEN I view the source code, 
THEN I find semantic HTML elements. 

WHEN I view the structure of the HTML elements, 
THEN I find that the elements follow a logical structure independent of styling and positioning.

WHEN I view the image elements, 
THEN I find accessible alt attributes. 

WHEN I view the heading attributes, 
THEN they fall in sequential order. 

WHEN I view the title element, 
THEN I find a concise, descriptive title. 

## Acceptance Criteria Breakdown
1. Semantic HTML elements
    - There are div elements throughout the starting code. Look up semantic sections that are fitting.
2. Logical structure that is agnostic of styling
    - May have to adjust CSS to look at semantic elements instead of divs with classes.
3. Accessible alt attributes
    - The first big image is declared in CSS... and looks like a div with a class in HTML. Change that.
    - All following images just need alt text.
4. Heading attributes are in sequential order
    - h1, h2, and h3 headers are present, check the styles sheet to make sure they don't visually change.
5. Concise, descriptive title
    - Current title is "website", this should be a quick change.