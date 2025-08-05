# Portfolio Revamp  

A revamped developer portfolio built with **Next.js, TypeScript, and Firebase**, designed to showcase projects and technical skills.  

[Trello Board Link](https://trello.com/b/48h5sv1m)

Live Deployment Link (Not available yet)
  
## Table of Contents  

- [Purpose](#purpose)  
- [Functionality and Features](#functionality-and-features)  
- [Tech Stack](#tech-stack)  
- [Planned Features / To Do](#planned-features--to-do)  

## Purpose  

The purpose of this project is to create a dynamic and interactive portfolio that highlights my projects, skills, and professional growth. Beyond being a personal showcase, it also demonstrates practical full-stack development capabilities such as authentication, CRUD functionality, and responsive design.  

## Functionality and Features  

- **Home Page** with a hero introduction, tech stack overview, and featured projects showcase.  
- **Projects Page** displaying dynamic project cards fetched from Firestore, with category filtering options.  
- **Blog / Case Studies** section supporting markdown content to share detailed project breakdowns, lessons learned, and developer insights.  
- **Contact Page** featuring a smart form that saves submissions to Firestore and triggers email notifications via Firebase Cloud Functions.  
- **Private Admin Dashboard** secured with Firebase Authentication that allows:  
  - Creating, editing, and deleting projects.  
  - Creating, editing, and deleting blog posts.  
  - Viewing and managing contact form submissions.  
- **Responsive UI/UX** designed with Tailwind CSS and Material UI, including a dark/light mode toggle and smooth animations powered by Framer Motion.  

## Tech Stack  

- **Frontend**: Next.js (App Router) + TypeScript  
- **Backend / Database**: Firebase Firestore + Firebase Authentication  
- **Styling**: Tailwind CSS + Material UI  
- **Animations**: Framer Motion  
- **Deployment**: Netlify  

## Planned Features / To Do  

- [ ] Home Page: Intro section, tech stack, featured projects  
- [ ] Projects Page: Dynamic project cards with category filters  
- [ ] Blog / Case Studies: Markdown support for posts  
- [ ] Contact Page: Form with Firestore storage + email trigger  
- [ ] Admin Dashboard:  
  - [ ] Firebase Auth login  
  - [ ] CRUD for projects  
  - [ ] CRUD for blog posts  
  - [ ] Contact submissions management
- [ ] Public playground login without write access to test features  
- [ ] Responsive design improvements and accessibility enhancements  
- [ ] Dark/Light mode toggle  
- [ ] Animations and page transitions with Framer Motion  
- [ ] GitHub API integration: live commit feed and contribution calendar  
- [ ] Analytics dashboard: visits, message counts, GitHub activity stats  
- [ ] SEO optimization and metadata management  
- [ ] Unit and integration tests for critical components
- [ ] Automated deployment pipeline with Vercel preview environments
