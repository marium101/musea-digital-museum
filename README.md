<img width="1038" height="894" alt="image" src="https://github.com/user-attachments/assets/dd3825f0-260d-4143-9633-f93cd0045805" /># 🏛️ MUSEA — Digital Museum Experience

> **History deserves to be experienced.**

MUSEA is a modern, responsive digital museum landing page designed to transform the traditional museum experience into an immersive digital journey.

The website presents historical artifacts, cultural collections, stories, categories, and different levels of digital archive access through an elegant editorial-inspired interface.

The project was developed entirely from scratch using **HTML5 and vanilla CSS3**, with no JavaScript and no CSS frameworks.

---

## 🎯 Project Overview

MUSEA combines the atmosphere of a traditional museum with the visual language of a modern digital experience.

The landing page allows visitors to:

- Explore featured historical collections
- Discover individual artifacts and their stories
- Browse different cultural categories
- Explore MUSEA's digital access tiers
- Learn about the concept behind MUSEA
- Enter the digital museum experience through interactive calls-to-action

The design focuses on visual storytelling, strong typography, generous spacing, subtle animations, and a dark museum-inspired color palette.

---

## 👥 Target Audience

MUSEA is designed for:

- 🏛️ Museum and history enthusiasts
- 📚 Students and researchers
- 🎨 Art and culture lovers
- 🌍 People interested in world history
- 💻 Visitors interested in digital museum experiences
- 🔎 Curious users who enjoy discovering historical stories

---

# 🌐 Live Website

### 🚀 Live Demo

**[Visit MUSEA Live →](YOUR_VERCEL_URL_HERE)**

> Replace `YOUR_VERCEL_URL_HERE` with the actual Vercel URL after deployment.

### 💻 GitHub Repository

**[View Source Code →](YOUR_GITHUB_REPOSITORY_URL_HERE)**

---

# ✨ Features

## 🧭 Sticky Navigation

The navigation bar remains accessible while the user scrolls through the website.

Implemented using:

```css
position: sticky;
top: 0;


---

🎭 Hero Section

The hero section introduces the MUSEA experience using:

Large editorial typography

Museum-inspired imagery

Call-to-action button

Supporting information

CSS animation

Responsive layout
---
🏺 Featured Collections

The collections section presents different areas of the museum archive using responsive cards.

Featured collections include:

Ancient World

Renaissance

Lost Stories


The cards use CSS transitions and hover effects to provide visual feedback.


---

🗿 Artifact Spotlight

A dedicated artifact section highlights an individual museum object and its story.

The layout uses:

Flexbox

Relative positioning

Absolute positioning

Responsive images

object-fit

CSS transitions

Image hover scaling



---

🧭 Explore by Category

Visitors can browse the archive through categories including:

Art

History

Culture

Science


The category rows include hover transitions, animated arrows, and responsive typography.


---

🎟️ MUSEA Access Tiers

The project includes a dedicated Services/Tier section as required by the project brief.

The three access levels are:

Visitor

For users beginning their museum journey.

Explorer

For visitors who want deeper access to the digital archive.

Curator

For users looking for the complete museum experience.

The tier system uses terms such as:

Standard Quota

Extended Archive

Digital Credits

Premium Access

Curator Insights

Unlimited Exploration


No prices or currency symbols are displayed anywhere on the website.


---

📖 About MUSEA

The About section explains the purpose of the digital museum and presents the idea that historical objects can be experienced through modern digital storytelling.


---

✨ Final Call-to-Action

The final CTA encourages visitors to enter the MUSEA experience and continue exploring the digital archive.


---

🦶 Responsive Footer

The footer provides navigation to:

Collections

Stories

Access

About

Contact

Archive

Social platforms


The footer automatically adapts to smaller screen sizes.


---

🎨 CSS Techniques Used

This project demonstrates a variety of modern CSS techniques.

CSS Variables

A centralized color system is defined using CSS custom properties:

:root {
    --bg-main: #0e0d0b;
    --bg-secondary: #151310;
    --bg-card: #1b1915;
    --text-main: #f4efe6;
    --text-muted: #aaa39a;
    --accent: #c9a86a;
}

This makes the visual theme consistent and easy to maintain.


---

Flexbox

Flexbox is used for:

Navigation

Hero layout

Artifact Spotlight

Footer

Access tier content

Responsive alignment


Example:

.spotlight-container {
    display: flex;
    align-items: center;
    gap: 90px;
}


---

CSS Grid

CSS Grid is used for structured layouts such as:

Collection cards

Access tiers

Category rows

Footer layouts

Responsive content sections


Example:

.tier-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}


---

Responsive Media Queries

Media queries are used to adapt the website to different screen sizes.

Examples include:

@media (max-width: 900px) {
    /* Tablet adjustments */
}

@media (max-width: 600px) {
    /* Mobile adjustments */
}

The design was created to work across desktop, tablet, and mobile devices.


---

Fluid Typography

The project uses clamp() to make headings scale smoothly between screen sizes.

Example:

font-size: clamp(3rem, 5vw, 5.5rem);

This prevents large headings from becoming too small on desktop or overflowing on mobile.


---

CSS Keyframe Animations

Custom keyframes are used for page entrance animations.

Example:

@keyframes fadeUp {

    from {
        opacity: 0;
        transform: translateY(25px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }

}

The animation is then applied using:

.hero-content {
    animation: fadeUp 1s ease-out both;
}


---

CSS Transitions

Smooth transitions are used throughout the interface for:

Buttons

Cards

Images

Arrows

Links

Borders

Hover states


Example:

transition: transform 0.4s ease;


---

Transform Effects

Interactive elements use CSS transformations such as:

transform: translateY(-8px);

and:

transform: scale(1.04);

These create subtle movement without JavaScript.


---

Positioning

The project demonstrates:

position: relative

position: absolute

position: sticky


These are used for navigation, artifact numbering, labels, and decorative interface elements.


---

Responsive Images

Images use:

object-fit: cover;

to maintain a consistent visual appearance across different screen sizes.


---

🏗️ Design Architecture

The project uses a simple external CSS architecture to keep the HTML structure clean and the styling maintainable.

Project Structure

MUSEA/
│
├── index.html
│
├── css/
│   └── style.css
│
├── images/
│   ├── artifact.jpg
│   ├── ancient.jpg
│   ├── renaissance.jpg
│   ├── stories.jpg
│   └── spotlight.jpg
│
├── desktop.png
├── mobile.png
│
└── README.md


---

HTML Architecture

The HTML is divided into clear semantic sections:

Navigation
    ↓
Hero
    ↓
Featured Collections
    ↓
Artifact Spotlight
    ↓
Explore by Category
    ↓
Access Tiers
    ↓
About MUSEA
    ↓
Final CTA
    ↓
Footer

Semantic HTML elements such as:

<nav>
<section>
<article>
<footer>

are used to keep the structure organized and meaningful.


---

CSS Architecture

All styling is contained in an external stylesheet:

css/style.css

The stylesheet is organized into logical sections:

CSS Variables
Reset / Base Styles
Container
Navigation
Hero
Hero Animations
Collections
Artifact Spotlight
Categories
Access Tiers
About
Final CTA
Footer
Responsive Media Queries

This organization makes the stylesheet easier to read, debug, and maintain.


---

Naming Convention

Descriptive class names are used throughout the project.

Examples:

.hero
.hero-content
.hero-visual
.spotlight
.spotlight-container
.spotlight-image
.spotlight-content
.tier-card
.category-item
.footer

The naming approach makes it easier to identify which part of the interface each CSS rule controls.


---

🎨 Design System

Color Palette

The visual identity uses a dark, museum-inspired palette.

Color	Purpose

Deep Charcoal	Main background
Dark Brown	Secondary sections
Warm Gold	Accent and interactive elements
Off White	Primary text
Muted Gray	Supporting text


The warm gold accent creates a connection with antique artifacts and museum interiors.


---

Typography

The design combines:

Serif typography

Used for:

Main headings

Large editorial statements

Museum-inspired titles


Sans-serif typography

Used for:

Navigation

Paragraphs

Buttons

Labels

Supporting information


This combination creates an editorial and premium museum aesthetic.


---

📱 Responsive Design

MUSEA was designed using a mobile-first responsive mindset and tested across multiple viewport sizes.

Desktop

The desktop version uses:

Multi-column layouts

Large imagery

Spacious sections

Three-column tier cards

Side-by-side editorial sections


Tablet

Tablet layouts adjust:

Grid columns

Typography

Spacing

Image sizes


Mobile

At smaller screen sizes:

Multi-column layouts become single-column

Content stacks vertically

Typography scales using clamp()

Cards become full width

Footer columns adapt

Images resize appropriately


The primary mobile breakpoint is:

@media (max-width: 600px)


---

🖼️ Screenshots

Desktop View
<img width="1324" height="880" alt="image" src="https://github.com/user-attachments/assets/5f452495-8fe2-4a84-9ec0-a9fce6a8234f" />
<img width="1356" height="864" alt="image" src="https://github.com/user-attachments/assets/8d4ed4a4-0821-4c0c-9a3c-0b92376d56cc" />
<img width="1356" height="864" alt="image" src="https://github.com/user-attachments/assets/9548bcf6-6cce-4ab6-aacd-4674c202a324" />
<img width="1173" height="763" alt="image" src="https://github.com/user-attachments/assets/4f0d7302-eeaa-4e64-b9ca-3b36fc83da7b" />
<img width="1069" height="717" alt="image" src="https://github.com/user-attachments/assets/280a0056-c40e-43ea-9651-349dcf70c37d" />

The desktop version demonstrates the full visual hierarchy, large editorial typography, collection cards, artifact imagery, access tiers, and spacious layout.


---

Mobile View

<img width="1044" height="885" alt="image" src="https://github.com/user-attachments/assets/956e3a6c-b6a3-4679-9d59-b917d44687ec" />
<img width="1023" height="865" alt="image" src="https://github.com/user-attachments/assets/618f5da3-cd10-4586-b101-43bd67c5e668" />
<img width="1023" height="865" alt="image" src="https://github.com/user-attachments/assets/0564935e-e0c8-4bbb-9bd8-74210c04c7a4" />
<img width="997" height="883" alt="image" src="https://github.com/user-attachments/assets/76720ff4-2302-4549-9597-d2ed386c80d1" />
<img width="1038" height="894" alt="image" src="https://github.com/user-attachments/assets/c02fcc17-34d5-4a13-8967-9ac37faf31aa" />




The mobile version demonstrates the responsive single-column layout, scaled typography, stacked sections, and mobile-friendly navigation.


---

💻 Technologies Used

Technology	Purpose

HTML5	Page structure and semantic markup
CSS3	Complete visual design
Flexbox	Flexible layouts
CSS Grid	Structured layouts
Media Queries	Responsive design
CSS Variables	Design system
Keyframes	Custom animations
CSS Transforms	Interactive effects
GitHub	Source code hosting
Vercel	Live deployment


Important

This project uses:

HTML + CSS only

No JavaScript was used for layout, interaction, or animations.

No Bootstrap, Tailwind CSS, or other CSS frameworks were used.


---

🚀 How to Run Locally

Because MUSEA is a static HTML/CSS project, no package installation or build process is required.

Method 1 — Download the Repository

Download or clone the project:

git clone https://github.com/marium101/musea-digital-museum/edit/main
Navigate into the project:

cd musea-digital-museum

Open:

index.html

in a web browser.


---

Method 2 — Open Directly

You can also download the project and double-click:

index.html

The website will open directly in your browser.


---

🔍 Browser Testing

The interface was tested at different viewport sizes including:

Desktop

Tablet

Mobile

Approximately 390px mobile width

Approximately 600px width

Approximately 768px tablet width

Approximately 1024px desktop/tablet width

Large desktop screens


The responsive design was checked for:

Horizontal overflow

Image scaling

Text wrapping

Card layout

Navigation

Footer layout

Section spacing



---

📂 Project Goals

The main goals of this project were to demonstrate practical knowledge of:

HTML5 structure

CSS Box Model

Flexbox

CSS Grid

Responsive Web Design

Media Queries

Fluid Typography

Positioning

CSS Variables

CSS Transitions

CSS Keyframe Animations

UI/UX principles

Visual hierarchy

Responsive layouts



---

🌟 Design Philosophy

MUSEA was designed around one central idea:

> Historical objects should not feel distant.



The interface therefore avoids a traditional dense museum layout and instead uses large visual elements, editorial typography, controlled spacing, subtle animation, and warm accent colors to create a modern digital gallery experience.


---

👤 Author

MUSEA — Digital Museum Experience

Designed and developed as an individual HTML & CSS mini project.


---
