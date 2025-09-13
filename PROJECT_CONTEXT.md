# georgekutti.com - Project Context

## Overview
A minimal, text-based personal website inspired by Berkshire Hathaway's ultra-simple design philosophy. The site serves as a personal journal and project documentation platform.

## Design Philosophy
- **Minimalism**: No unnecessary styling, animations, or complex layouts
- **Function over form**: Pure content focus, like Berkshire Hathaway's website
- **Manual editing**: Designed for direct HTML file editing, not CMS
- **Typography**: Georgia serif font for readability and classic feel

## Site Structure
```
georgekutti.com/
├── index.html              # Homepage with project list
├── style.css               # Shared stylesheet
├── project-alto.html       # Car restoration project journal
├── project-x.html          # Project X journal
├── project-upskill.html    # Learning and skill development journal
├── project-camera.html     # Photography project journal
├── awareness.html          # Personal awareness journal
├── money.html              # Financial tracking journal
├── time.html               # Time management journal
├── grooming.html           # Personal grooming journal
├── books.html              # Personal library and reading list
├── images/                 # Book cover images and other assets
│   ├── deep-work.jpg       # Deep Work book cover
│   ├── the-book-of-secrets.jpg # The Book of Secrets book cover
│   ├── make-time.jpg       # Make Time book cover
│   └── book-placeholder.jpg # Default book cover placeholder
└── PROJECT_CONTEXT.md      # This file
```

## Technical Details
- **Hosting**: GitHub Pages
- **Domain**: georgekutti.com (custom domain configured)
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
1. Save book cover image in `images/` directory
2. Name image descriptively (e.g., `book-title.jpg`)
3. Copy existing book-item div in `books.html`
4. Update image source, title, author, and year
5. Place in appropriate section (currently reading or books read)

## Git Workflow
- **Add changes**: `git add .`
- **Commit**: `git commit -m "Description of changes"`
- **Push**: `git push`
- **Auto-deployment**: GitHub Pages automatically updates when pushed

## CSS Features
- **Dark mode**: Automatic switching based on `prefers-color-scheme`
- **Typography**: Georgia serif font throughout
- **Minimal styling**: Clean, readable layout
- **Journal entries**: Structured with dates, titles, and content
- **Links**: Simple underline on hover
- **Books page**: Clickable book covers, organized layout with images

## Books Page Features
- **Currently Reading**: Active books with progress tracking
- **Books Read**: Completed books with finish dates
- **Book Information**: Title, author, publication year
- **Clickable Covers**: Book images open full-size in new tab
- **Image Organization**: All book covers stored in `images/` directory
- **Responsive Design**: Works on all devices

## Maintenance
- **Regular updates**: Add journal entries as needed
- **File editing**: Direct HTML editing, no build process
- **Backup**: Git repository serves as backup
- **Domain**: Managed through Squarespace DNS

## Inspiration
Based on Berkshire Hathaway's famous minimal website design - prioritizing content and functionality over visual complexity.

---
*Last updated: December 2024*
