# Blog-Project-Udacity
Blog Project for Udacity Front End Developer Program

Project Corrections:

1.	•	❌ The main index.html page should be in the root of the directory. 

I moved the index.html outside of the static folder. Originally it was inside of the static folder and while the code works this way, it will break if launched directly from GitHub. It will only work if opened in a browser via VS code ONLY when the index.html file is  INSIDE of the Static folder which is a subfolder of my project folder

2. 	•	❌ Headers (h1 to h3 at minimum) are used and styled with unique properties: Please also include <h3>

H3 headers were placed on Line 39 and line 48 in the index.html file

3. ❌ Paragraph text is styled with bold, italic, and underlined properties: None of the paragraph text styles tags are present.

Line 29 in the index.html file shows italics. Line 28 in the hero shows Underline. Line 29 shows <em> emphasis.

4. The webpage includes buttons with appropriate labels and functions: Please use <button> HTML tag	
I used a class for the button  in the HTML which was there originally(not sure why I was dinged for this) line 38 and line 49. It is also on my CSS page index.css line 16. 


5. ❌ According to the requirements, you need to use CSS Grid at least twice in the project. I can see you are using it once, so that is clear you know how to use it. It will not be a difficult task for you

Added grid again to the landing page layout in the hero banner at line 15

6. ❌ The webpage includes captions for images: Please add captions for all the images.

I cut and paste a quote onto the image. If I add the <figcaption> tag I don’t think it will render correctly in the webpage?
