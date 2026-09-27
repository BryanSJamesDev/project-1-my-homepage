# Dins Patel Personal Homepage — Design Document

## 1. Project Description

This project is a personal homepage and portfolio for Dins Patel, a Computer Science student with a Bachelor of Computer Applications background. It introduces Dins’s education, interests, skills, project concepts, and learning goals through a responsive website built with HTML, CSS, and JavaScript ES6 modules.

The site has three pages:

- **Home (index.html):** An introduction, education and interests, project concepts, skills, learning journey, and links to the other pages.
- **About (about.html):** More detail about Dins’s academic path, interests, and goals.
- **AI Creative Page (ai-page.html):** A page about AI and technology, with buttons that let visitors explore Dins’s interests in machine learning, computer vision, and future technology.

The visual design uses a warm off-white background, dark brown text, and terracotta accents. Flexbox and Grid organize the layouts, with responsive styles for smaller screens. JavaScript supports the mobile navigation menu and the interactive AI topic selector.

The homepage presents **LocalMind AI** and **TravelNexus** as project concepts, not completed products.

### Project goals

- Introduce Dins and his Computer Science background.
- Make education, interests, skills, and project concepts easy to find.
- Provide clear navigation between the three pages.
- Demonstrate semantic HTML, organized CSS, responsive layouts, and original JavaScript behavior.

## 2. Target Audience and User Personas

### Persona 1 — Jordan, a recruiter

- **Background:** A recruiter reviewing student and early-career technology portfolios.
- **Goal:** Quickly understand Dins’s education, technical interests, and project work.
- **Needs:** A clear introduction, easy-to-scan skills, project descriptions, and a way to contact Dins.
- **How the site helps:** The homepage presents Dins’s background, skills, and project concepts in clearly labeled sections, with contact links in the footer.

### Persona 2 — Priya, a classmate

- **Background:** A Computer Science student interested in what classmates are learning and building.
- **Goal:** Explore Dins’s interests and project ideas, then learn more about his education.
- **Needs:** Project summaries, technology interests, and straightforward navigation to the About page.
- **How the site helps:** The homepage introduces LocalMind AI and TravelNexus as concepts and links to more information about Dins’s academic path.

### Persona 3 — Morgan, a visitor interested in AI

- **Background:** A student or general visitor curious about AI in learning, software, and everyday life.
- **Goal:** Read Dins’s perspective and explore the AI topics that interest him.
- **Needs:** A focused explanation and a simple interaction that reveals more about selected topics.
- **How the site helps:** The AI Creative Page shares Dins’s perspective and lets Morgan select a topic to display a short explanation.

## 3. User Stories

### Story 1 — A recruiter scans the homepage

Jordan receives Dins’s portfolio link while reviewing applicants. Jordan opens the homepage, reads the introduction, scans the skills and education information, and reviews the project concepts. Jordan uses a footer contact link to get in touch.

**User story:** As a recruiter, I want to find Dins’s background, skills, and project information quickly so I can decide whether to contact him.

### Story 2 — A classmate explores project interests

Priya visits the homepage after meeting Dins in class. Priya reads the LocalMind AI and TravelNexus concept summaries, then opens the About page to learn more about Dins’s academic path and interests.

**User story:** As a classmate, I want to understand what Dins is interested in building so I can find shared technical interests and possible project ideas.

### Story 3 — A visitor explores AI topics

Morgan opens the AI Creative Page and reads Dins’s introduction to AI. Morgan selects “Computer Vision,” then “Future Technology,” and reads the related text that appears.

**User story:** As a visitor, I want to choose an AI topic and see Dins’s related interests so I can explore the page interactively.

### Story 4 — A mobile visitor navigates the site

Priya opens the site on a phone. Priya taps the menu button, chooses a page or section, and continues browsing in the mobile layout.

**User story:** As a mobile visitor, I want the navigation to open and close clearly so I can move around the site on a small screen.

## 4. Design Mockups

These wireframes describe the page layouts and serve as design mockups for the project. They are layout sketches, not screenshots of the finished site.

### Home page — desktop

    ┌──────────────────────────────────────────────────────────────┐
    │ DINS PATEL       Home  About  Projects  Skills  More About Me │
    ├──────────────────────────────────────────────────────────────┤
    │ COMPUTER SCIENCE STUDENT                                     │
    │ Dins Patel                              ┌───────────────────┐ │
    │ Intro to AI, software, and web tech     │ CURRENTLY         │ │
    │ [View My Work] [About Me]               │ Learning & Building│ │
    │                                         │ Education / focus │ │
    ├─────────────────────────────────────────┴───────────────────┤
    │ ABOUT: From BCA to Computer Science                          │
    │ Background text                         Education / interests│
    ├──────────────────────────────────────────────────────────────┤
    │ PROJECT CONCEPTS: LocalMind AI | TravelNexus                 │
    ├──────────────────────────────────────────────────────────────┤
    │ SKILLS: Java, JavaScript, HTML/CSS, Python, MySQL, Git, ...  │
    ├──────────────────────────────────────────────────────────────┤
    │ MY JOURNEY: 2022 → 2025 → 2026 → Next                        │
    ├──────────────────────────────────────────────────────────────┤
    │ CURRENT FOCUS                                                │
    ├──────────────────────────────────────────────────────────────┤
    │ Contact links                              AI Creative Page → │
    └──────────────────────────────────────────────────────────────┘

### Home page — mobile

    ┌──────────────────────────┐
    │ DINS PATEL          Menu  │
    ├──────────────────────────┤
    │ COMPUTER SCIENCE STUDENT │
    │ Dins Patel               │
    │ Introductory paragraph   │
    │ [View My Work] [About Me]│
    │ ┌──────────────────────┐ │
    │ │ Learning & Building  │ │
    │ │ Education / interests│ │
    │ └──────────────────────┘ │
    ├──────────────────────────┤
    │ About and education      │
    │ Project concepts         │
    │ Skills                   │
    │ Journey and current focus│
    │ Contact / AI page link   │
    └──────────────────────────┘

### About page

    ┌──────────────────────────────────────────────────────────────┐
    │ DINS PATEL       Home  About  Projects  Skills               │
    ├──────────────────────────────────────────────────────────────┤
    │ ABOUT ME                                                     │
    │ A little more about my journey                               │
    ├──────────────────────────────────────────────────────────────┤
    │ MY STORY: background text in two columns                     │
    ├──────────────────────────────────────────────────────────────┤
    │ EDUCATION: BCA graduate / current MS Computer Science        │
    ├──────────────────────────────────────────────────────────────┤
    │ INTERESTS: AI / Software Development / Web / New Technology  │
    ├──────────────────────────────────────────────────────────────┤
    │ GOALS: Keep learning. Keep building.                         │
    ├──────────────────────────────────────────────────────────────┤
    │ Footer links                              AI Creative Page → │
    └──────────────────────────────────────────────────────────────┘

### AI Creative Page

    ┌──────────────────────────────────────────────────────────────┐
    │ DINS PATEL                      Home  About  Projects  Skills│
    ├──────────────────────────────────────────────────────────────┤
    │ DARK HERO: “Technology is changing how we build.”   AI visual│
    ├──────────────────────────────────────────────────────────────┤
    │ MY VIEW: AI should help people build better things           │
    ├──────────────────────────────────────────────────────────────┤
    │ AREAS: Learning | Software | Everyday Life                  │
    ├──────────────────────────────────────────────────────────────┤
    │ EXPLORE: [Machine Learning] [Computer Vision] [Future Tech] │
    │ Selected topic explanation appears here                     │
    ├──────────────────────────────────────────────────────────────┤
    │ LOOKING AHEAD: Learn. Build. Experiment.                     │
    └──────────────────────────────────────────────────────────────┘

## 5. Visual and Interaction Decisions

- **Colors:** Warm off-white (#f7f3ee), white cards, dark brown (#2f2925), terracotta accent (#b85c38), and pale terracotta (#f3dfd4).
- **Typography:** Arial with common sans-serif fallbacks for readability and broad availability.
- **Layout:** Flexbox and CSS Grid organize the hero, project cards, skills, journey, and AI content. Media queries adapt the layout to phones.
- **Navigation:** A JavaScript menu toggle supports small screens. Selecting a navigation link closes the mobile menu.
- **Interactive feature:** On the AI page, selecting a topic updates the result text and highlights the selected button.
- **Accessibility:** Pages use semantic HTML and labeled controls. Any content images added to the site should include suitable alt text.

## 6. Technology

- HTML5
- CSS3
- JavaScript ES6 modules
- CSS Flexbox and Grid
- ESLint and Prettier

The site is a static frontend and does not require a backend.
