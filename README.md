# Re: Technical Documentation

<p align="justify"> This is a part of my mini-project requirement in Web Development and Programming. Though not an experienced developer myself, I aim to present front-end development with a lightweight and user-friendly design.
It uses  HTML for structure, CSS for styling and animations and JavaScript for dynamic behavior, which creates an engaging user experience (UX). 
The combination of smooth transitions, hover effects, and interactive elements enhances both the aesthetic appeal and functionality of the website. </p>

## Structure
The website is one-pager and all content is contained within a single HTML file. Rather than loading multiple pages, the website uses internal navigation with anchor links to smoothly scroll to different sections.

### Key Sections
1 Header - the website's title, a short introductory quote, and a navigation menu
<p> 2 About Me - profile picture, a personal introduction, and a button-triggered fun fact display </p>
<p> 3 Hobbies & Interests - hobbies and self-improvement activities </p>
<p> 4 Contact Details - links to email and social media profiles </p>
<p> 5 Special Feature Section - achievement on stage with Thailand's Minister of Digital Economy and Society </p>
<p> 6 Footer - displays copyright information </p>

📌 Each section follows a semantic structure which improves readability and accessibility.

## Technologies Used
This website is built using standard front-end web technologies that ensure compatibility with Windows OS, macOS, Android OS and IOS. It incorporates CSS for styling, layout management, and animations.

1 HTML (HyperText Markup Language)
<p> 2 Semantic HTML5 tags <!-- (e.g., <header>, <nav>, <section>, <footer>) --> to structure content logically </p>
<p> 3 Anchor links <!-- (<a href="#section">) --> allow seamless navigation within the single-page layout </p>
<p> 4 Metadata (<!-- <meta> -->tags) in the "head" section improve responsiveness and usability </p>
<p> 5 CSS (Cascading Style Sheets) </p>
<p> 6 JavaScript (Client-Side Scripting) The website integrates JavaScript to enhance interactivity. </p>

## Key Styling Features
1 Uses the Arial sans-serif font for better legibility
<p> 2 The menu uses a flexbox layout to center items and smooth hover effects for better UX </p>
<p> 3 CSS media queries adjust styles for smaller screens to enhance usability on mobile devices </p>

## Animations and Transitions
1 The entire body fades in upon page load (opacity: 0 → 1).
<p> 2 Images and buttons change opacity and scale on hover. </p>
<p> 3 The navigation menu links slightly enlarge and change color when hovered. </p>
<p> 4 A pulsating effect is applied to buttons upon interaction. </p>

## Functionalities Implemented
1 Clicking the button toggles the visibility of a fun fact<!--(<p id="funFact">)-->.
<p> 2 Uses "setTimeout()" to control smooth fade-in/out transitions. </p>
<p> 3 Sections appear with a fade-in effect as the user scrolls (opacity: 0 → 1). </p>
<p> 4 The script continuously checks which sections are in the viewport using "getBoundingClientRect()". </p>

## Features & Enhancements
1 Uses a flexbox-based horizontal navigation menu for structured alignment.
<p> 2 Each menu item is linked to different sections via internal anchor links "(#id)". </p>
<p> 3 Hover effects modify color and add a slight scale effect for improved user interaction. </p>

### CSS Hover Effects
1 Change color when hovered (color: #007BFF)
<p> 2 Slightly increase in size (transform: scale(1.1)) to indicate interactivity </p>

### Buttons and Images
1 Buttons animate when clicked (transform: "scale(0.9)" on :active).
<p> 2 Images feature a pulse effect on hover. </p>

### JavaScript Interaction
1 [Fun Fact Toggle] Click button to reveal a hidden fact using display: block and opacity: 1.
<p> 2 [Smooth Section Animation] Sections remain hidden (opacity: 0) until scrolled into view. As the user scrolls, sections fade in and shift upwards (transform: translateY(20px) → 0). </p>

### Android-Friendly Layout
1 The navigation menu switches to a vertical stack on smaller screens.
<p> 2 Text sizes adjust dynamically for readability. </p>
<p> 3 Buttons enlarge to be more tap-friendly (width: 90% on small screens). </p>

### Additional Enhancements
1 Optimized image loading that uses max-width: 100% to ensure images scale properly.
<p> 2 Text emphasis and readability </p>
<p> 3 Line height adjustments (line-height: 1.6) improve text clarity. </p>

## Future improvements could include the following:
1 Dark mode support using CSS variables and JavaScript;
<p> 2 More JavaScript-based animations for a dynamic user interface (UI) and; </p>
<p> 3 Lazy loading for images to improve performance on slow networks. </p>
