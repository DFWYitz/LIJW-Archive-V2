# Jewish World Archive - Pseudocode

## Page Load Behavior
- Display title/header
- Show filter dropdown (months)
- Load ALL publications by default
- Sort by date: newest first, oldest last

## Publication Display
- Each publication = one box/card
- Box contains: thumbnail + title + date
- Click box = open PaperTurn link in NEW TAB
- Grid layout: 4 columns desktop, 2 tablet, 1 mobile

## Filter Functionality
- Dropdown shows all available months
- Select month = show only publications from that month
- "All Months" option to reset

## Data Structure (what info each publication needs)
- Title
- Date (for sorting)
- Month (for filtering) 
- Thumbnail URL
- PaperTurn link

## Adding New Publications
- Add new entry to data.js file
- Should automatically appear in correct chronological order
- New month automatically appears in filter dropdown