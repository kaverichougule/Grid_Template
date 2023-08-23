Hosted Link: https://kaverichougule.github.io/Grid_Template/

![image](https://github.com/kaverichougule/Grid_Template/assets/101037685/572a9ff1-eb6c-4f3c-b41b-6b3343a4c1af)
'body': Contains the visible content of the webpage. <br>
'main class="testimonial-grid"': Represents the main content section using the "testimonial-grid" class. <br>
Inside the main section, there are five 'article' elements representing individual testimonials. <br>
CSS Code (style.css): <br>
:root: Defines global CSS variables (custom properties) for colors, fonts, font weights, and font sizes. <br>
Global CSS rules: <br>
Set box-sizing for all elements and remove default margin and list styles. <br>
Set default styles for body, headings, and fonts. <br>
Define utility classes for flex layout and spacing. <br>
Component Styles: <br>
.testimonial-grid: Styles the main grid container for testimonials, setting grid areas and layout. <br>
.testimonial: Styles each individual testimonial article. <br>
Media queries are used to adjust the layout for different screen widths. <br>
Background Colors and Text Colors: <br>
.bg-primary-400, .bg-secondary-400, .bg-secondary-500, .bg-neutral-100: Define background colors. <br>
.text-neutral-100, .text-secondary-400: Define text colors. <br>
.border-primary-400: Define border color. <br>
Additional Styles: <br>
Testimonial images, name, and position styles. <br>
Adjust font sizes and line heights for different elements. <br>
Media Queries: <br>
Adjust the layout of testimonials using media queries for various screen widths. <br>
Modify the grid-template-areas to rearrange testimonials based on screen width. <br>
.testimonial.quote: Adds a background image to the quote-style testimonial. <br>
.testimonial img: Styles the testimonial images. <br>
.testimonial .name, .testimonial .position: Styles for name and position text. <br>
.testimonial > p:first-of-type, .testimonial > p:last-of-type: Styles for the first and last paragraphs in each testimonial. <br>
