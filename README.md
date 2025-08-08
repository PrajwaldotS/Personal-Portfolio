This is a modern, single-page personal portfolio website built with HTML, Tailwind CSS, and GSAP. It features a sleek design with smooth animations, a glassmorphism effect, and a dark/light theme toggle. The site is fully responsive and designed to showcase skills, certificates, and projects in a visually engaging way.

✨ Key Features
Sleek & Modern UI: A clean interface with beautiful gradient backgrounds and a glassmorphism effect on key elements.

Stunning Animations: Powered by the GSAP (GreenSock Animation Platform) for a highly dynamic and interactive user experience. Animations include:

Page load and text animations.

Section transitions that animate content into view.

Animated skill bars that fill up when the section is viewed.

Interactive hover effects on cards and buttons.

A floating hero text animation.

Dual-Theme Support: A seamless Dark Mode and Light Mode toggle that instantly changes the color palette.

Fully Responsive: Built with Tailwind CSS, the layout adapts perfectly to all screen sizes, from mobile phones to desktop monitors.

Single-Page Navigation: Smooth, JavaScript-powered navigation that shows and hides sections without page reloads, giving it an app-like feel.

Interactive Elements: Includes a custom particle background and an optional smooth-following cursor for an enhanced Browse experience on desktops.

🚀 Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling:

Tailwind CSS - A utility-first CSS framework for rapid UI development.

Font Awesome - For high-quality icons.

Animations:

GSAP (GreenSock Animation Platform) - The core library for all animations.

ScrollTrigger - A GSAP plugin for scroll-based animations (though used here to trigger animations on section view).

Fonts:

Google Fonts - Using the 'Inter' and 'Poppins' font families.

🛠️ Getting Started
This project uses CDN links for all its dependencies, so there is no need for a complex build setup (like Node.js or npm). You can run it directly in your browser.

Prerequisites
You just need a modern web browser (like Chrome, Firefox, or Edge) and a code editor (like VS Code).

Installation
Clone the repository:

Bash

git clone https://github.com/PrajwaldotS/your-repository-name.git
Navigate to the project directory:

Bash

cd your-repository-name
Open the index.html file:
Simply open the index.html file in your web browser to see the portfolio live. For the best development experience, I recommend using a live server extension (like the "Live Server" extension in VS Code) to see your changes in real-time.

🎨 Customization
It's easy to customize this portfolio and make it your own. All content is located within the index.html file.

Personal Information:

Home Section: Edit the <h1> and <p> tags inside the <section id="home"> to change your name and tagline.

About Section: Update the paragraphs inside <section id="about"> to reflect your bio.

Skills: In the "Skills & Expertise" area, you can change the skill names and adjust the percentage by modifying the inline style="width: XX%" attribute in the .skill-fill divs.

Certificates & Projects:

Both the Certificates and Projects sections are built with reusable card components.

To add, remove, or modify an item, simply copy/paste or edit a <div> with the class .certificate-card or .project-card.

Update the href attribute in the <a> tags to link to your certificates or project demos.

Contact Information & Socials:

Go to <section id="contact">.

Update your email, phone number, and location in the contact info cards.

Change the href attribute in the social media links (<a href="...">) to point to your profiles (LinkedIn, GitHub, etc.).

Colors & Styling:

The background gradients for each section are defined in the <style> tag at the top of the file. Look for the .gradient-bg-* classes to change the colors for both light and dark modes.

📬 Contact
Created by Prajwal.S - feel free to connect with me!

LinkedIn: https://www.linkedin.com/in/prajwal-s-159b5a369/

GitHub: https://github.com/PrajwaldotS

Email: prajwal.s2294@gmail.com
