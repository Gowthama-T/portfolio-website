# portfolio-website

Gowthama T - Data Analyst Portfolio ⚡️

A clean,minimal, and responsive portfolio template for Data Analysts!
___________________________________________________________________________________________________________________________________________________________________

___________________________________________________________________________________________________________________________________________________________________
**📚 Table of Contents**

-Getting Started

-How to Use

-Change and Customize

-Deployment

-Technologies Used

-Illustrations

-For the Future

-Contributors

-Contact for Queries
___________________________________________________________________________________________________________________________________________________________________












Customize your personal portfolio by editing the HTML, CSS, and JavaScript directly in the provided files. Adjust the theme by modifying colors, fonts, and styles in the <style> section of the HTML file. Feel free to use it as-is or personalize it to suit your needs.
If you'd like to contribute and improve this for other users, check out the Issues section.
Created something awesome with your fork of this portfolio? Feel free to open a pull request to share it!
Table of Contents

Portfolio Sections
Getting Started
How to Use
Change and Customize
Deployment
Technologies Used
Illustrations
For the Future
Contributors
Contact for Queries

Portfolio Sections
✔️ Summary and About Me✔️ Skills✔️ Education✔️ Work Experience✔️ Certifications 🏆✔️ Projects✔️ Contact Me  
To view a live example, click here.
Getting Started
These instructions will help you get a copy of the project up and running on your local machine for development and testing purposes.
You'll need a modern web browser (e.g., Chrome, Firefox) and a code editor (e.g., VS Code) installed on your computer.
Prerequisites

Git: Version 2.17.1 or higher
Code Editor: For editing HTML, CSS, and JavaScript
Web Browser: To preview and test the portfolio

How to Use
From your command line, clone and set up the portfolio:
# Clone this repository
git clone https://github.com/kas0380/Portfolio.git

# Go into the repository
cd Portfolio

# Open the project in your code editor
code .  # For VS Code, or use your preferred editor


Open the index.html file in your code editor.
Preview the portfolio by opening index.html in a web browser (e.g., right-click and select "Open with Live Server" in VS Code, or drag the file into your browser).
Modify the content, styles, and scripts as needed (see Change and Customize).

Change and Customize
Personalize every section according to your needs:

Content: Edit the index.html file to update:
Greeting section (e.g., name, tagline: "Hi, I'm Gowthama T!", "Google Certified Business Intelligence & Data Analyst")
About Me description
Experience, Skills, Education, Certifications, and Projects details
Contact information (email, phone, LinkedIn, GitHub, location)


Styling: Modify the <style> section in index.html to:
Change colors (e.g., replace #1a237e for the primary blue or #ff6e40 for the accent orange)
Adjust fonts (currently using Poppins and Roboto via Google Fonts)
Tweak animations, card styles, or section backgrounds


JavaScript: Update the <script> section in index.html to:
Modify smooth scrolling behavior
Adjust scroll-based sidebar visibility for the logo, email, and social links


Resume Upload: To include your resume:
Upload your resume as a PDF to a folder (e.g., create a resume folder in the project directory).
Rename the file to resume.pdf.
Add a link in the HTML, e.g., <a href="resume/resume.pdf" download class="bg-1a237e text-white px-4 py-2 rounded-full font-semibold text-sm hover:bg-ff6e40 transition-colors">Download Resume</a> in the home or contact section.



Using Emojis
Add emojis directly in the HTML for compatibility across browsers. For example:

Use 📊 for Tableau, 🐍 for Python, etc., as seen in the Skills section.

Customize Animations
Modify the @keyframes in the <style> section to adjust animations like fadeInUp, slideInLeft, slideInRight, bounceIn, underlineGrow, particleMove, and gradientShift for a unique look.
Deployment
When you're ready to host your website online, follow these steps:
Deploying to GitHub Pages

Update index.html Metadata:
Modify the <title> and <meta> tags in index.html for SEO (e.g., <title>Gowthama T - Data Analyst Portfolio</title>).


Push to GitHub:# Add all changes
git add .

# Commit your changes
git commit -m "Initial portfolio setup"

# Push to your repository
git push origin main


Enable GitHub Pages:
Go to your repository on GitHub.
Navigate to Settings > Pages.
Set the source to the main branch and the / (root) folder.
Save, and your site will be live at https://<your-username>.github.io/Portfolio.


Optional: Custom Domain:
Add a CNAME file in the root directory (e.g., yourdomain.com).
Configure your domain provider to point to GitHub Pages (see GitHub Pages documentation).



Deploying to Netlify

Link Your Repository:
Push your project to a GitHub repository.
Sign up/log in to Netlify.
Click "New site from Git" and connect your GitHub repository.


Configure Build:
Set the build command to empty (no build needed for static HTML).
Set the publish directory to . (root).


Deploy:
Click "Deploy site" to host your portfolio.
Netlify provides a unique URL (e.g., https://your-portfolio.netlify.app).
Optionally, configure a custom domain in Netlify settings.



For more details, read Hosting on Netlify.
Technologies Used

HTML
CSS (via Tailwind CSS)
JavaScript
Google Fonts (Poppins, Roboto)

Illustrations

SVGs: Custom inline SVGs used for icons (e.g., email, LinkedIn, GitHub, project icons).
Particle Background: SVG-based particle animation in the home section for visual appeal.

For the Future
If you can help with these, please don’t hesitate to open a pull request:

Integrate a dynamic contact form with email submission
Add a blog section linked to a platform like Medium
Incorporate data visualization charts (e.g., for project metrics)
Enhance accessibility (e.g., ARIA labels, keyboard navigation)

Contributors

Gowthama T - Creator and Designer

Contact for Queries
If you have any questions or need assistance with setup, customization, or deployment, feel free to reach out:  

Email: gowthamat634@gmail.com  
LinkedIn: Gowthama T  
GitHub: Gowthama-T
I’m happy to help with any issues or suggestions for improving this portfolio!

