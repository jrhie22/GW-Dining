<h2 align="center">GW Campus Dining Finder</h2>
<h3 align="center">Web Application for Campus Dining Discovery</h3>

## Overview
A user-friendly web application designed to enhance access to dining options at George Washington University. 
We address usability issues and providing intuitive search capabilities.

GW Campus Dining Finder aims to minimize the time students or D.C. locals spend searching for food options by streamlining the user experience and offering dynamic search capabilities. The application improves access to dining locations and enhances overall user satisfaction on campus.


## Project Details
**Project Structure**

<img width="881" height="415" alt="image" src="https://github.com/user-attachments/assets/41d15d62-7b02-4033-ab12-6a309ebb85fe" />


• Home - Landing page with featured dining options<br/>
• Dining Locations - Browse and filter all campus dining venues<br/>
• Menus - View detailed menu offerings and dietary information<br/>
• Discounts & Perks - Exclusive student dining deals<br/>
• Meal Plans - Information about available meal plan options<br/>
• Student Services - Additional dining-related resources<br/>

**Shared Components**

•Fixed Navbar - Consistent navigation across all pages<br/>
•Footer - Standardized footer with links<br/>
•Cart Panel - Shopping cart functionality<br/>


**Key Features**

•Interactive Map - Custom markers for easy location discovery and campus navigation<br/>
•Dynamic Filtering - Dietary preference and location-based filtering options<br/>
•Multi-Page Structure - Comprehensive dining information across multiple sections<br/>
•Responsive Design - Optimized for desktop, tablet, and mobile devices<br/>
•GW Branding - Professional design using university branding colors (navy blue and colonial gold)<br/>
•Real-Time Navigation - Integration with Google Maps for campus dining location guidance<br/>


**Technology Stacks**

HTML5 - Semantic markup for proper content organization and SEO optimization

CSS3 - Custom styling with GW branding implementation (Framework: Bootstrap)

JavaScript - Dynamic features including:

•Menu filtering capabilities<br/>
•Shopping cart functionality<br/>
•Google Maps integration<br/>
•Responsive design interactions<br/>


**Additional Tools**

Google Maps API - Real-time location mapping and navigation

Design Principles
Information Architecture

Clear navigation hierarchy
Intuitive user pathways from discovery to ordering
Responsive grid-based layout system

**Visual Design**

Color Palette: Navy blue and colonial gold (GW branding)
Card-Based Layout: Fluid adaptation across all screen sizes
Interactive Elements: Filter overlays and dynamic map markers

## Getting Started
**Prerequisites**

Modern web browser (Chrome, Firefox, Safari, Edge)
Local server environment (for development)

**Installation**

Clone the repository:
<pre><code>
bashgit clone https://github.com/your-username/gw-campus-dining-finder.git
cd gw-campus-dining-finder
</code></pre>
Set up a local server:

bash# Using Python 3
<pre><code>
python -m http.server 5500
</code></pre>
**Or using Node.js (if http-server is installed)
<pre><code>
npx http-server -p 5500
</code></pre>
Open your browser and navigate to:

http://127.0.0.1:5500/index.html

**Configuration**

Update Google Maps API key in js/main.js with your own API credentials<br/>
Customize dining location data in the appropriate data files<br/>
Adjust color variables in css/styles.css for branding customization<br/>

## Usage
**For Students**

Navigate to "Dining Locations" to view all campus dining options
Use filters to narrow results by dietary preferences and location
Click on locations to view detailed menus and hours
Add items to cart and proceed with ordering

**For Developers**

Modular component structure for easy maintenance
Reusable filter and map components
Separation of concerns (HTML, CSS, JavaScript)


## Future Enhancements

 •Backend database implementation for improved scalability<br/>
 •WCAG accessibility audits and compliance improvements<br/>
 •Automated testing suite integration<br/>
 •User authentication system<br/>
 •Real-time menu updates<br/>
 •Student feedback and ratings system<br/>
 •Push notifications for special dining events<br/>
 •Integration with campus payment systems<br/>

## Lessons Learned
**Successes**

Modular Design - Enhanced workflow and seamless component integration
Professional Appearance - Clean UI with strong GW branding implementation
User-Friendly Interface - Intuitive navigation for student users

**Future Improvements**

Implement backend systems for data persistence
Comprehensive accessibility testing from project start
Establish automated testing protocols early in development

## Contribution
This is a university project. For inquiries about contributions or modifications, please contact the project team.

**Development Guidelines**

•Follow the established modular component structure

•Maintain consistent CSS naming conventions

•Test changes across multiple device sizes

•Keep commits focused and well-documented


## 🔗 Resources

<a href="https://www.gwu.edu/">GW Campus Information</a>

<a href="https://getbootstrap.com/docs">Bootstrap Documentation</a>

<a href="https://developers.google.com/maps">Google Maps API Docs</a>

<a href="https://www.w3.org/WAI/WCAG21/quickref/">Web Accessibility Guidelines (WCAG)</a>
