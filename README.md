# Nama : Abdan Hafidz | NRP : 5054231021

# Tautan di bawah ini

<a href="https://abdanhafidz.com/news-portal">LINK BERIKUT </a>

# News Portal Website Documentation

## Overview

This documentation covers the structure and functionality of a simple news portal website. The website features multiple HTML pages with a responsive navigation bar, article listings, and detailed article pages.

![](assets/docgif1.gif)

![](assets/20250319_013458_docgif2.gif)


![](assets/20250319_013741_docgif3.gif)

## File Structure

```
news-portal/
├── index.html             # Homepage with featured articles
├── pages/                 # Directory for article pages
│   ├── politics.html      # Politics news page
│   ├── business.html      # Business news page
│   ├── technology.html    # Technology news page
│   ├── sports.html        # Sports news page
│   └── entertainment.html # Entertainment news page
├── articles/              # Directory for individual articles
│   ├── article1.html      # Sample article 1
│   ├── article2.html      # Sample article 2
│   └── article3.html      # Sample article 3
├── css/                   # Directory for CSS files
│   └── style.css          # Main stylesheet
└── js/                    # Directory for JavaScript files
    └── script.js          # Main JavaScript file
```

## Features

- Responsive navigation bar that works on mobile and desktop
- Category pages for different news types
- Individual article pages with full content
- Latest news section on the homepage
- Search functionality (basic implementation)
- Mobile-friendly design

## Navigation

The navigation bar is included on all pages and provides access to:

- Home page
- Category pages (Politics, Business, Technology, Sports, Entertainment)
- Search functionality

## Page Structure

Each page follows a consistent structure:

1. Header with site logo and navigation
2. Main content area with articles or full article content
3. Footer with additional links and copyright information

## Responsive Design

The website is designed to be responsive and work on different screen sizes:

- Mobile: Single column layout with collapsible navigation
- Tablet: Two column layout for article lists
- Desktop: Multi-column layout with sidebar

## Implementation Notes

- Pure HTML, CSS, and JavaScript implementation (no frameworks)
- Semantic HTML elements used for better accessibility
- CSS custom properties for consistent theming
- JavaScript event listeners for interactive elements
