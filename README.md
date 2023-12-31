# Grid - Magazine Ass CSS

## Hosted Link
You can view the project live at [View Live Project](https://saifulislam05.github.io/grid-magazine/)
## Porject Description 
This project is an example of a magazine webpage built using HTML and CSS. It showcases various HTML elements and CSS styles to create an attractive and responsive magazine layout.

## UI
![image](https://github.com/saifulislam05/grid-magazine/assets/73392705/138b1092-49df-41b6-9e36-5bd92e03acd7)

## HTML Structure

### Main Section:
- `<main>`: The main content of the web page.
    - `<section class="heading">`: Section for the heading.
      - `<header class="hero">`: Header for the hero section.
        - `<img src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" alt="freecodecamp logo" loading="lazy" class="hero-img">`: Hero image.
        - `<h1 class="hero-title">OUR NEW CURRICULUM</h1>`: Hero title.
        - `<p class="hero-subtitle">Our efforts to restructure our curriculum with a more project-based focus</p>`: Hero subtitle.
      - `<div class="author">`: Author information.
        - `<p class="author-name">`: Author's name.
          - `<a href="https://freecodecamp.org" target="_blank" rel="noreferrer">freeCodeCamp</a>`: Author's link.
        - `<p class="publish-date">March 7, 2019</p>`: Publish date.
      - `<div class="social-icons">`: Social media icons.
        - Social media links with Font Awesome icons.

    - `<section class="text">`: Section for text content.
      - Text paragraphs, quotes, and blockquotes.

    - `<section class="text text-with-images">`: Section for text with images.
      - `<article class="brief-history">`: Article about the brief history.
        - List of versions with descriptions.
      - `<aside class="image-wrapper">`: Image aside.
        - Images with descriptions.

## Global Styles
- `*`, `::before`, `::after`
  - `padding: 0; margin: 0;`: Resets padding and margin for all elements.
  - `box-sizing: border-box;`: Sets box-sizing to include padding and borders.

## HTML (`html`)
- `font-size: 62.5%;`: Sets the base font size to 62.5% for easier `rem` calculations.

## Body (`body`)
- `font-family: 'Baskervville', serif;`: Sets the font family for the entire document.
- `color: linen;`: Sets text color to linen.
- `background-color: rgb(20, 30, 40);`: Sets background color to dark blue-gray.

## Headings (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`)
- `font-family: 'Anton', sans-serif;`: Applies 'Anton' font family to all headings.

## Links (`a`)
- `text-decoration: none;`: Removes underlines from links.
- `color: linen;`: Sets link text color to linen.

## Main (`main`)
- `display: grid;`: Defines `main` as a grid container.
- `grid-template-columns: minmax(2rem, 1fr) minmax(min-content, 94rem) minmax(2rem, 1fr);`: Creates a three-column grid layout.
- `row-gap: 3rem;`: Adds a gap between rows.

## Images (`img`)
- `width: 100%;`: Makes images fill their containers horizontally.
- `object-fit: cover;`: Ensures the image covers its container while maintaining aspect ratio.

## Horizontal Rule (`hr`)
- `margin: 1.5rem 0;`: Adds margin above and below horizontal rules.
- `border: 1px solid rgba(120, 120, 120, 0.6);`: Sets border style for horizontal rules.

## Hero Section (`header.hero`)
- `grid-column: 1 / -1;`: Spans the entire grid horizontally.
- `position: relative;`: Allows positioning elements inside the hero section.

## Hero Title and Subtitle (`h1.hero-title`, `p.hero-subtitle`)
- `text-align: center;`: Centers text horizontally.
- `color: orangered;`: Sets text color to orangered.
- `font-size: 8rem;`: Sets a large font size for the hero title.
- `font-size: 2.4rem;`: Sets font size for the hero subtitle.

## Author Section (`div.author`)
- `font-size: 2rem;`: Sets font size for author information.
- `font-family: "Raleway", sans-serif;`: Sets font family for author's name and other elements.

## Social Icons (`div.social-icons`)
- `display: grid;`: Makes social icons a grid container.
- `font-size: 3rem;`: Sets font size for social icons.

## First Paragraph (`p.first-paragraph`)
- `font-size: 1.8rem;`: Sets font size.
- `color: orangered;`: Sets text color to orangered.
- `float: left;`: Floats the first letter to the left to create a drop cap effect.
- `margin-right: 1rem;`: Adds right margin to separate the letter from the text.

## Quote (`blockquote.image-quote`)
- `color: #00beef;`: Sets text color to blue-green.

## Text with Images Section (`section.text.text-with-images`)
- `display: grid;`: Makes this section a grid container.
- `grid-template-columns: 1fr 2fr;`: Defines a two-column grid layout.
- `column-gap: 3rem;`: Sets gap between columns.
- `margin-bottom: 3rem;`: Adds margin at the bottom.

## Lists (`ul.lists`, `li`)
- `list-style-type: none;`: Removes bullet points from unordered lists.
- `margin-top: 2rem;`: Adds margin to the top of unordered lists.

## Image Wrapper (`aside.image-wrapper`)
- `display: grid;`: Makes this section a grid container.
- `grid-template-columns: 2fr 1fr;`: Defines a two-column grid layout.
- `grid-template-rows: repeat(3, min-content);`: Defines three rows of minimum content height.
- `gap: 2rem;`: Sets the gap between grid items.
- `place-items: center;`: Centers items within the grid.

## Media Queries
- Adjust styles for different screen widths to ensure responsiveness.
- Modify font sizes, layout, and other styles for better user experience on smaller screens.


