# Design Choices for Carrie Jones' Portfolio Website  

## Purpose and Audience  
The Carrie Jones Portfolio website is designed to showcase the artistic talents and professional portfolio of an writer  and drama coach. The site appeals to theatre enthusiasts, potential collaborators, and students interested in drama classes.

## Color Palette  
The chosen colour palette reflects the elegance and creativity of Carrie Jones' brand:  
- **#FFFFF0 (Ivory)**: Used as the primary background colour to ensure a clean and sophisticated look.  
- **#CBA328 (Gold)**: Highlights key elements like headings, buttons, and hover states, symbolizing creativity and prestige.  
- **#5C5346 (Brown)**: Adds depth and warmth, prominently featured in the footer, navbar branding, and certain text elements.  

This combination balances sophistication with readability, creating a professional and engaging atmosphere.  

## Typography  
Typography choices reflect a balance between readability and elegance:  
- **Playfair Display**: A serif font used for headings, delivering a bold and artistic impression that aligns with the theatrical theme.  
- **Lora**: A serif font used for body text to maintain readability and classic styling.  

Both fonts are sourced from Google Fonts, ensuring accessibility and performance.  

## Layout and Responsiveness  
The layout is designed with a **mobile-first approach**, ensuring accessibility across all devices:  
- **Hero Section**: A prominent visual with a full-screen background image and bold introductory text.  
- **About Section**: Cleanly organised to present Carrie Jones' biography and achievements.  
- **Portfolio Section**: Card-style layout with responsive images showcasing projects and performances.  
- **Footer**: Compact, informative, and visually cohesive, providing essential links and contact information.  

Media queries and flexbox are used to adapt the layout for tablets, desktops, and larger screens seamlessly.

## Images  
Images are optimised and styled to enhance the visual appeal and performance:  
- **Responsive Design**: All images use `width: 100%` and `height: auto` to maintain aspect ratios and fit containers across screen sizes.  
- **Performance Enhancements**: Explicit `width` and `height` attributes minimise layout shifts, improving the user experience.  
- **Borders and Spacing**: Subtle borders and spacing around images enhance visual separation and focus.

## Interactivity  
- **Navbar**: Includes smooth hover effects for links and highlights the active page with a distinct style.  
- **Buttons**: Styled with a gold background and hover effects for user engagement.  
- **Hover Effects**: Enhance the interactivity of images and cards in the portfolio section, drawing attention to key content.  

## Performance and Accessibility  
### Performance:  
- **Optimised Assets**: Images are compressed and appropriately scaled to ensure fast loading times.  
- **CSS Styling**: Organised CSS enhances maintainability and reduces unnecessary rendering overhead.  

### Accessibility:  
- **High Contrast**: Text and background colours ensure readability for users with visual impairments.  
- **Semantic HTML**: Tags such as `<header>`, `<main>`, and `<footer>` improve accessibility and SEO.  
- **Alt Text**: Included for all images to provide context for screen readers and enhance searchability.  

## Design Principles  
- **Elegance and Professionalism**: The design reflects Carrie Jones' theatrical artistry while maintaining a polished, professional appearance.  
- **Consistency**: The colour scheme, typography, and layout are consistent across all pages for a cohesive user experience.  
- **Visual Hierarchy**: Elements like the Hero section and Portfolio cards are strategically designed to draw attention to key content.  

This thoughtfully crafted design ensures that the website not only showcases Carrie Jones work effectively but also engages and informs its audience.


## **Project Objectives**
### **Purpose**
The primary goal of this portfolio website is to:
- Highlight Carrie’s accomplishments as a writer playwright and drama teacher.
- Provide potential collaborators and clients with an engaging platform to explore her projects.
- Establish Carrie’s online presence with a professional, responsive, and accessible design.
- Showcase her teaching initiatives and workshops in an interactive and informative manner.

## User Experience (UX)
### Project Goals
1. **Business Goals**: 
   - Promote Carrie Jones's work to readers, literary agents, and publishers.
   - Provide clear contact options for professional inquiries.
   - Build a community of readers and followers through blog posts, event and engagement features.

2. **Customer Goals**:
   - Provide easy access to information about Carrie Jones’s screenwriting, plays and events
   - Offer insights into Carrie’s creative process and updates on new releases.
   - Allow users to connect with Carrie through blog posts events and social media.

### User Goals
#### New Users
- Learn about Carrie Jones and her plays and workshops.
- Easily navigate the site to find specific information.
- View sample scenes or synopses of her scripts.

#### Returning Users
- Stay updated on Carrie’s latest projects via blog posts.
- Access details about upcoming play performances or events.
- Engage through comments or newsletters.

#### Frequent Users
- Quickly find updates about Carrie’s workshops or play premieres.
- Engage with Carrie’s ongoing discussions or writing prompts.


## **User Stories**
### **External Users (Site Visitors)**
## **User Story 1: Potential Clients**
**Objective:** Learn about Carrie’s expertise and projects to evaluate her suitability for creative collaborations.
### ✅ **Must Have**  
- A **Portfolio Section** showcasing selected writing, plays, and creative projects.
### 🔵 **Should Have**  
- A section with detailed project descriptions, including Carrie’s creative contributions.
### 🟢 **Could Have**  
- Multimedia content showcasing excerpts from plays or collaborative projects.



### ✅ **Acceptance Criteria**
1. The portfolio section should display project summaries with images and descriptions.
2. Each project should include details about Carrie’s role and creative process.
3. Navigation to the portfolio should be fast and intuitive.

### 📝 **Task List**
- [ ] Create a dedicated Portfolio Page.
- [ ] Organise projects into categories (Plays, Writing, Collaborations).
- [ ] Include high-quality images and project descriptions.
- [ ] Optimise load times for multimedia content.

---
## **User Story 2: Drama Enthusiasts**
**Objective:** Explore Carrie’s creative projects, plays, and workshops to deepen their understanding and appreciation of the art.
### ✅ **Must Have**  
- A **Works Section** showcasing plays, projects, and creative excerpts.
### 🔵 **Should Have**  
- Multimedia excerpts from plays and creative projects.
### 🟢 **Could Have**  
- Behind-the-scenes content and interactive creative workshops.
### ✅ **Acceptance Criteria**
1. Projects and plays should include multimedia and visual elements.
2. Each project should have a description of the plays
3. Navigation should be easy and visually appealing.
### 📝 **Task List**
- [ ] Create sections for Plays, Writing, and Creative Projects.
- - [ ] Provide clear and concise descriptions for each project.

### **User Story 3 Collaborators (Producers, Actors, Directors)**
**Objective:** Quickly find contact details and collaborate on creative projects.
### ✅ **Must Have**  
- A **Contact Section** with an inquiry form, social media links, and direct email information.
### 🔵 **Should Have**  
- Collaboration testimonials and examples of past creative projects.
### 🟢 **Could Have**  
- Links to collaborative platforms, schedules, and behind-the-scenes content.

### ✅ **Acceptance Criteria**
1. A functional **Contact Section** should include an email form, social links, and direct contact details.
2. Collaboration testimonials should highlight Carrie’s past creative partnerships.
3. The contact form should send messages without errors.

### 📝 **Task List**
- [ ] Create a **Contact/About Page** with an inquiry form.
- [ ] Embed social media profiles and links to professional platforms.
- [ ] Showcase examples of successful collaborations and testimonials.

---
### **Internal User (Carrie Jones)**
## **User Story 4 : Present Creative and Educational Accomplishments**
**Objective:** Present her biography, achievements, and creative contributions professionally.

### ✅ **Must Have**  
- A well-structured **About - Biography Section** with achievements and career highlights.

### 🔵 **Should Have**  
- Images and multimedia showcasing her accomplishments.

### 🟢 **Could Have**  
- A timeline highlighting significant milestones in Carrie’s creative journey.
### ✅ **Acceptance Criteria**
1. The Biography page should include relevant text, photos, and multimedia.
2. Key achievements should be presented in a chronological or thematic order.

### 📝 **Task List**
- [ ] Create a **About Page**.
- [ ] Include photos, videos, and creative project milestones.
- [ ] Organise content in an intuitive and visually appealing format.

## **User Story 5: Centralise Portfolio Content**
**Objective:** Showcase her portfolio of plays, writing, and teaching initiatives in a clean and accessible format.
### ✅ **Must Have**  
- A well-organised **Portfolio Page** that categorises content clearly.

### 🔵 **Should Have**  
- Categories for different types of work (Plays, Writing, Teaching).

### 🟢 **Could Have**  
- Interactive elements, such as carousels or collapsible sections.

### ✅ **Acceptance Criteria**
1. The Portfolio Page should organise projects into clear categories.
2. Each project should have concise summaries, images, and descriptions.

### 📝 **Task List**
- [ ] Design and implement sections for Plays, Writing, and Teaching Projects.
- [ ] Use multimedia elements (images, videos) to enhance each project entry.
- [ ] Create interactive elements to improve navigation and user experience.

## **User Story 6: Promote Workshops and Events**
**Objective:** Share information about workshops and creative events with a wider audience.
### **Should Have**  
- An **Events Page** showcasing upcoming workshops, classes, and talks.
### 🔵 **Should Have**  
- Integration for booking, registration, and event details.
### 🟢 **Could Have**  
- Testimonials and behind-the-scenes photos of past workshops and creative activities.
### ✅ **Acceptance Criteria**
1. The Events Page should contain accurate details about workshops and creative initiatives.
2. A booking system or registration link should be functional and accessible.
### 📝 **Task List**
- [ ] Create an **Events Page** to list upcoming workshops and classes.
- [ ] Provide booking details and relevant event information.
- [ ] Include multimedia content showcasing past workshops and classes.

## **User Story 7  Maintain a User-Friendly Interface**
**Objective:** Ensure site visitors can easily navigate and interact with the website.
### ✅ **Must Have**  
- A fixed, responsive **Navigation Bar** for quick access to all sections.
### 🔵 **Should Have**  
- Smooth animations and transitions for an enhanced user experience.
### 🟢 **Could Have**  
- Interactive elements like dropdowns, modals, and collapsible sections.
### ✅ **Acceptance Criteria**
1. The navigation should be consistent across all sections of the website.
2. Transitions and animations should be seamless and not hinder performance.
### 📝 **Task List**
- [ ] Implement a **Fixed, Responsive Navigation Bar**.
- [ ] Optimise animations and transitions to ensure a smooth interface experience.
- [ ] Test all interactive elements across different devices (desktop, tablet, mobile).-


## **Features**
### **Website Highlights**
MVP
- **Responsive Design**: The site is fully responsive, ensuring an optimal experience on all devices.
- **Structured Navigation**: A clear and intuitive navigation bar guides users to all major sections of the site.
- **Portfolio Showcase**: Features Carrie’s works, including summaries and images of her plays.
- **Contact Section**: Provides a contact form, email, and social media links for easy connection.
- **Biography**: A dedicated section presenting Carrie’s background, skills, and teaching philosophy.
- **Testimonials**: Optional Displays feedback from students, collaborators, and industry professionals.
-** Phase 2
  **Events Section** (Optional): Highlights upcoming workshops, performances, or speaking engagements.
**Testimonials**: Optional Displays feedback from students, collaborators, and industry professionals.
-

**Main Technologies**

- **HTML5**: For semantic and accessible page structure.
- **CSS3**: Clean a## nd responsive design with a minimalist aesthetic.
- **Bootstrap** (Optional): For responsive layouts, grid systems, and navigation components.
- **Git & GitHub**: For version control and deployment.

## **Website Structure**
### **Pages/Sections**

1. **Home Page**
   - A welcoming section with an introduction to Carrie Jones.
   - Quick links to her portfolio, biography, and contact sections.

2. **Portfolio Section**
   - A showcase of projects with summaries, images, and relevant details.
   - Organized in a grid layout or card system for clarity and accessibility.

3. **Contact/About section**
   - two sections with a detailed biography and a fully functional contact form.
   - Social media links and direct contact details displayed intuitively.


## **Deployment**
I deployed the page on GitHub pages via the following procedure: -

1. From the project's [repository](https://github.com/HelenLloydJeng/Milestone-Project-1), go to the **Settings** tab.
2. From the left-hand menu, select the **Pages** tab.
3. Under the **Source** section, select the **Main** branch from the drop-down menu and click **Save**.
4. A message will be displayed to indicate a successful deployment to GitHub pages and provide the live link.

You  can find the live site via the following URL [Helen Lloyds MileStone Project 1 Live Webpage] (https://helenlloydjeng.github.io/Milestone-Project-1/)
