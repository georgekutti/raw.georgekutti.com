# raw.georgekutti.com - Project Context

## Overview
A minimal, text-based personal website inspired by Berkshire Hathaway's ultra-simple design philosophy. The site serves as a personal journal and project documentation platform.

## Design Philosophy
- **Minimalism**: No unnecessary styling, animations, or complex layouts
- **Function over form**: Pure content focus, like Berkshire Hathaway's website
- **Manual editing**: Designed for direct HTML file editing, not CMS
- **Typography**: Georgia serif font for readability and classic feel

## Site Structure
```
/Users/george/Development/raw.georgekutti.com/
├── index.html              # Homepage with organized project sections
├── style.css               # Shared stylesheet with dark mode improvements
├── project-alto.html       # Car restoration project journal
├── project-x.html          # Project X journal
├── project-camera.html     # Custom camera project with tabs (journal/showcase)
├── project-upskill.html    # Learning and skill development journal
├── project-awareness.html  # Personal awareness journal
├── project-time.html       # Time management journal
├── project-grooming.html   # Personal grooming journal
├── project-money.html      # Money management journal
├── reading.html            # Personal library and reading list (renamed from books.html)
├── watching.html           # Media consumption tracking log
├── thinking.html           # Personal thinking and micro-blog (renamed from thoughts.html)
├── images/                 # Organized image assets
│   ├── books/              # Book cover images (for reading page)
│   │   ├── deep-work.jpg
│   │   ├── the-book-of-secrets.jpg
│   │   ├── make-time.jpg
│   │   └── the-pragmatic-programmer.jpg
│   ├── media/              # Show/movie posters
│   │   └── how-i-met-your-mother-season-4.jpg
│   └── projects/           # Project images
│       ├── alto/
│       │   └── alto-instax.jpg
│       └── camera/
│           ├── bought-3d-printer.jpg
│           ├── bought-raspberry-pi.jpg
│           └── took-photo.jpg
└── PROJECT_CONTEXT.md      # This file
```

## Technical Details
- **Hosting**: GitHub Pages
- **Domain**: raw.georgekutti.com (custom domain configured)
- **CSS**: External stylesheet with dark/light mode support
- **Responsive**: Basic responsive design
- **Theme**: Automatic dark/light mode based on device preference

## Journal Entry Structure
Each project page follows this template for easy manual editing:

```html
<!-- ENTRY START -->
<div class="journal-entry">
    <div class="entry-header">
        <span class="entry-date">Date here</span>
        <span class="entry-title">Entry title here</span>
    </div>
    <div class="entry-content">
        <p>Entry content here...</p>
    </div>
</div>
<!-- ENTRY END -->
```

## Adding New Entries
1. Copy the entire entry block (from `<!-- ENTRY START -->` to `<!-- ENTRY END -->`)
2. Paste it above the "JOURNAL ENTRIES START" comment
3. Update date, title, and content
4. Maintain the same HTML structure

## Adding New Project Pages
1. Create new HTML file (e.g., `project-name.html`)
2. Use existing project pages as template
3. Add link to `index.html` projects list
4. Follow same journal entry structure

## Adding New Books
1. Save book cover image in `images/books/` directory
2. Name image descriptively (e.g., `book-title.jpg`)
3. Copy existing book-item div in `reading.html` (use template comments)
4. Update image source, title, author, year, and progress
5. Use percentage format for progress (e.g., "30% complete")
6. Add Goodreads link to book title
7. Place in appropriate section (currently reading or books read)

## Adding New Thoughts
1. Copy the entire thought block (from `<!-- THOUGHT START -->` to `<!-- THOUGHT END -->`)
2. Paste it above the "THOUGHTS START" comment
3. Update date, time, heading, and content
4. Maintain the same HTML structure

## Git Workflow
- **Add changes**: `git add .`
- **Commit**: `git commit -m "Description of changes"`
- **Push**: `git push`
- **Auto-deployment**: GitHub Pages automatically updates when pushed

## CSS Features
- **Dark mode**: Automatic switching based on `prefers-color-scheme`
- **Typography**: Georgia serif font throughout
- **Minimal styling**: Clean, readable layout
- **Centered content**: 600px max-width containers for optimal readability
- **Journal entries**: Structured with dates, titles, and content
- **Links**: Simple underline on hover
- **Books page**: Clickable book covers, organized layout with images
- **Responsive design**: Works on all screen sizes

## Books Page Features
- **Currently Reading**: Active books with percentage-based progress tracking
- **Books Read**: Completed books with finish dates
- **Book Information**: Title, author, publication year
- **Progress Display**: Percentage completion (e.g., "15% complete")
- **Clickable Covers**: Book images open full-size in new tab
- **Clickable Titles**: Book titles link to Goodreads pages
- **Image Organization**: All book covers stored in `images/` directory
- **Template System**: Easy-to-use comment templates for adding books
- **Responsive Design**: Works on all devices

## Thinking Page Features
- **Micro-blog Style**: Twitter-like personal thinking sharing
- **Date and Time**: Each thought includes timestamp
- **Headings**: Each thought entry has a descriptive heading/title
- **Template System**: Easy-to-use comment templates for adding thinking
- **Centered Layout**: 600px max-width for optimal readability
- **Chronological Order**: Newest thinking appears at the top
- **Minimal Design**: Clean, distraction-free interface

## Home Page Features
- **Personal Bio**: Evolving description of the website
- **Project Links**: Organized list of all project journals
- **Resource Links**: Quick access to books, thinking, and other resources
- **Divider Design**: Clean separation between header and content
- **Centered Layout**: Consistent with all other pages

## Maintenance
- **Regular updates**: Add journal entries as needed
- **File editing**: Direct HTML editing, no build process
- **Backup**: Git repository serves as backup
- **Domain**: Managed through Squarespace DNS

## Recent Updates (September 2025)

### Homepage Organization
- **Reorganized sections**: side projects, personal projects, log
- **Consistent naming**: All projects use "project-" prefix
- **Moved project-upskill**: From side projects to personal projects section
- **Renamed resources**: Changed to "log" for better accuracy

### New Features
- **watching.html**: New page for tracking media consumption with awareness focus
- **Tabbed interface**: project-camera.html and project-alto.html now have journal/showcase tabs
- **Image organization**: Structured images into books/, media/, and projects/ directories
- **Apple-style styling**: Rounded corners for project images
- **Status indicators**: Project status shown with simple text tags (e.g., "[paused]")

### Dark Mode Improvements
- **Background color**: Changed from pure black (#000) to softer gray (#1e1e1e)
- **Text color**: Softened from pure white (#fff) to gray-white (#d4d4d4)
- **Better contrast**: More comfortable reading experience

### Content Updates
- **Project descriptions**: Added brief descriptions to project pages
- **Consistent branding**: Updated all project titles to use hyphens
- **Enhanced spacing**: Improved visual hierarchy and readability
- **Page renaming**: books.html → reading.html, thoughts.html → thinking.html
- **Thinking page**: Added headings to thought entries for better organization
- **Project status**: Added status indicators for paused projects
- **Watching page**: Added day of the week to all journal entries for better time awareness tracking

## Inspiration
Based on Berkshire Hathaway's famous minimal website design - prioritizing content and functionality over visual complexity.

---
*Last updated: September 2025*
