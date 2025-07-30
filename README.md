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
- Grid layout: 3 columns desktop, 2 tablet, 1 mobile

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

## Stretch Goals - Topic-Based Navigation
### Multi-Tag System
- Each publication gets 5-15 topic tags: ["politics", "community", "religion", "culture", "events"]
- Users can filter by topic: "Show me all Politics articles"
- Combine filters: "Show me Politics articles from December 2024"

### Advanced PaperTurn Integration
- Upgrade PaperTurn plan for table of contents features
- Link directly to specific pages/articles within each publication
- Topic tags link to exact page in publication where that topic appears
- Example: "Community Events" tag opens publication directly to page 12

### Enhanced UI for Topics
- Topic tag buttons/chips on each publication card
- Click tag = filter by that topic across all publications