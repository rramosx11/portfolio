## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria

```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## What I added to my portfolio

* My portfolio has my name, recent photo, and the navigation will redirect to the section of the portfolio.
* Added semantic elemnents through the HTML
* Changed the h3 tags to h2 tags to fix the hierarchy of the headers.
* Removed the extra class titles and adjusted the CSS to condense the code in html and css.
* Reordered the css to follow the structure of the webpage.
* Added alt descriptions to the images
* Fixed the navigation bar so that when the tab in clicked on the website, the viewer will be redirected to that section of the page. The id was missing for the SEO section.