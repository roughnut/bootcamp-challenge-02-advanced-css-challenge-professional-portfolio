# Bootcamp Challenge 02 - Advanced CSS Challenge: Professional Portfolio

Coding bootcamp advanced CSS challenge to create a professional portfolio website from scratch.

## Description

Challenge is to build a professional coding portfolio using the advanced CSS concepts learned in Week 2 of coding bootcamp, including: flexbox, media queries and CSS variables. 

[User Story](#user-story) and [Acceptance Criteria](#acceptance-criteria) are below

Also included below is my [Process & Learnings](#process-learnings) section.

## Usage

Site to be deployed on Github pages once completed


<a id="user-story"></a>
## User Story

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

<a id=acceptance-criteria></a>
## Acceptance Criteria

```GIVEN I need to sample a potential employee's previous work
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

<a id="process-learnings"></a>
## Process & Learnings

1. During the week we looked at site wireframing and fellow student [Alex da Silva](https://design4reap.com/ "Link to Alex da Silva's personal website"), mentioned [Relume](https://www.relume.io/ "Link to Relume site") so I built a wireframe of this portfolio site on that service using the free version (very basic as a result).<br>
<br>
![wireframe screenshot](./assets/images/roughnut-dev-wireframe.png "roughnut portfolio website wireframe screenshot")
<br>

2. During the week we looked at CSS resets so sites are consistent across browsers. Once of the options mentioned was [normalize.css](https://necolas.github.io/normalize.css/ "Link to normalize.css"), which is a, and I quote, "A modern, HTML5-ready alternative to CSS resets. Normalize.css makes browsers render all elements more consistently and in line with modern standards. It precisely targets only the styles that need normalizing" <br>
<br>
I applied normalize.css using a CDN in the `<head>` <br>
`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css">`

3. Next...