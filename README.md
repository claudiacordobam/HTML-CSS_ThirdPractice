# HTML-CSS_ThirdPractice
This repository contains the third page I created as part of the HTML and CSS subject of the Bachelor's Degree in Multimedia. This subject took place during the Spring semester of the scholar year 2023-2024. </br>
This exercise's prompt asked students to replicate a webpage from a screenshot that we were provided with. It also required the website to be as responsive as possible, which was successfully acheived using the CSS `@media` rule. </br>
Furthermore, just like in the [previous exercise](https://github.com/claudiacordobam/HTML-CSS_SecondPractice), it was also required that we created a design that was WCAG 2.0-compliant. Some of the changes I implemented for this purpose were:
- The colour contrasts were modified so that all pairings had a minimum contrast of 4:5:1, acheiving a contrast of 7.12655 in one of the pairings
- The sprites that the University provided were modified using a vector graphics editor so that they did not contain any text (that would not only be too small to read for most users and not possible to adjust, but also not possible to read for screen readers) and so that the colour pairings' contrast was WCAG 2.0-compliant. This task was not requested in the exercise's prompt, but I truly believed that my website had to be as accessible as possible, and I worked a little bit extra to acheive that. You can find a screenshot of how I modified one of the sprites and its `:hover`/`:focus-within` version attached below:
<img width="970" alt="The picture shows how the colours of the sprite were modified so that they had a higher contrast. It also shows the before and after of how some text that was not accessible got removed" src="https://github.com/user-attachments/assets/68c6b5e8-9b5e-4a9d-8320-4ffadf1a9e7c">

- Just like in the previous exercise, I added `:focus-within` pseudo-classes in those parts that had a `:hover` pseudo-class
- Since one of the guidelines specifies that the context of an element should not be changed if it is focused, I did not apply the scale transformation of the "Sign up" button for keyboard users so that the context was not changed.

Last, but not least, please, kindly note that all the content was provided by the University. The original authors of the pictures and the text, therefore, own all copyrights.
