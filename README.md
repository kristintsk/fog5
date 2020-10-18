# Web design for everybody Capstone

This is the final project for Michigan University online course on Coursera. The capstone will develop a professional-quality web portfolio.  Students will demonstrate the ability to design and implement a responsive site for a minimum of three platforms.  Adherence to validation and accessibility standards will be required. This course is only open to students who have completed the first four courses in the Web Design for Everybody specialization: Introduction to HTML5, Introduction to CSS3, Interactivity with JavaScript, and Advanced Styling with Responsive Design.

## Portfolio objectives
Your first step is to think about what type of portfolio you would like to make. Will it be about you? How do you want to lay out the content? What is the story you are trying to tell or the information you are trying to convey? The second step will be to consider the different development options (from scratch, from a template, and/or utilizing a development framework). 

### Portfolio Requirements
**Each portfolio must:**
- Have at least three "pages." These can be three different html files, or one file that links to all three "pages". 
- Each page must have at least two semantic tags (header, nav, footer, etc)
- Each page must validate at validator.w3.org.
- Each page must be responsive -- there must be at least two unique views
- You must have at least 4 images on one of your pages. (If this requirement doesn't "fit" your portfolio plan, please just make an extra page that fulfills it. You can always unlink it after you have been peer -graded.
- Each page must be styled. The goal is not to impress, but to show competence. S,o add enough to show that you know how to write CSS rules. But peer-review with the knowledge that not everything will be beautiful.

### Grading instructions
- Does the site validate? 10pts
- Is the site responsive? 20pts
- Is the site well-styled? 10pts
- Are the images incorporated effectively? 5pts
- Successfully demonstrated the ability to enhance their site? 40pts (Each extra will be worth 10 pts, for a total of 40 pts)

# My project description
I used a Startbootstrap template Grayscale which is a simple template for a simple one-page layout. 
   - **Bootstrap:** the biggest challenge was to understand the CSS (initially more than 10 thousand lines, the whole Bootstrap package) - to understand what classes were in use, what values were the default values and what was added/overwritten. I changed the project setup from Bootstrap in CSS to Bootstrap cdn so I did not need the whole package in CSS. But as there were made some modifications to Bootstrap default values it took an effort 'to read the code' in order to make the changes I wanted to, and finally to remove the unused part of CSS code. I aimed to add more Bootstrap classes to HTML to shorten the CSS. I believe there are still quite some lines in CSS that could be removed, but as the number of lines is less than 1000 including section headings and my personal enhancements and it looks quite clear and simple already, I’m happy with the result.
   - **Other changes** - I changed the entire color-scheme (the template was designed in black-and-white) and rearranged slightly the structure (removed one block, added type-sections, altered background images, added core theme images and created personal enhancements). Quite a challenge was to create the background gradients when every section has its own background but the background of the page must form a coherent whole.
   - **Images** - I used Pixabay free photos to get high quality img files. Although there was no attribution required I decided to acknowledge the author - if the image is clicked the file will be opened in new tab in it's original location in Pixabay and the whole collection of the particular author is ready-to-view.
   - **Detailed descriptions of fog types** - the links in the text are opened in the same tab.

## Validation
- **HTML** – one warning, no errors (warning about missing heading - I do not want to add heading to cite section)
- **CSS** - fully validated (no warnings, no errors)

## Responsive design
I created different designs and layouts for lg, md and sm screen view by adding respective Bootstrap classes to HTML and media queries in CSS.

## My personal enhancements
1. added a section to display some nice sayings about fog and used carousel to present four cites. If slide is hovered the invert filter for bg image will be activated.
2. added modal to mermaid img. In case modal is triggered some additional text about mermaids will be displayed too.
3. added JS script to change background picture of the landing page over main heading (FOG)
4. designed a simplified view for printing
5. created/designed a special favicon for fog – block F on yellow background

## Finally
**You passed!** Congratulations. You earned 100 / 100 points.
https://www.coursera.org/account/accomplishments/certificate/CPW4UY9YDDWZ

### Conclusion
I was warned that using someone else's code might not be the easiest way. I had never used a full template before so I did want to give a try. It would have been much easier an less time-consuming to leav the whole Bootstrap in CSS and to try to delete the unused part, just add my own lines. Bu I'm happy i did the effort and took my time (started couple of times from the very beginning again, because something has gone hopelessly wrong), but every new try was easier than the previous one and with this final version I got the feeling that I understand what I'm doing. Practice is the best teacher!

