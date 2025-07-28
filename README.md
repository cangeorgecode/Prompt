### Project Vision
[1-2 sentence description of what you want to build and why]

### Core Features
[Numbered list of must-have functionality]
1. 
2. 
3. 

### Technical Specifications
- Django project name: [name]
- Django app name(s): [name]
- Database: [PostgreSQL/MySQL/SQLite]
- Packages: [list any specific packages you want to use]
- Frontend: [Bootstrap/Tailwind/React/Vanilla]

### Data Models Needed
[Describe your main data models with fields]
- Model1:
  - field1: type (purpose)
  - field2: type (purpose)
- Model2:
  - field1: type (purpose)

### Views/Pages Required
[List of views with their functionality]
- Page 1: [purpose, functionality]
- Page 2: [purpose, functionality]

### User Roles & Permissions
[Define different user types and what they can do]
- Role 1: Can do X, cannot do Y
- Role 2: Can do A, B, C

### Special Requirements
[Any unique functionality or constraints]
- 
- 

### Design Preferences
[Any UI/UX preferences or examples]
- 
- 

### Deployment Considerations
[Any hosting or deployment constraints]
- 
- 

### Future Roadmap
[Planned future enhancements]
1. 
2. 


## Example
### Project Vision
Build a web app that teaches car maintenance basics to complete beginners. Users should access step-by-step guides with video tutorials.

### Core Features
1. List of essential car maintenance tasks
2. Detailed view for each task with problem/fix explanation
3. Embedded YouTube tutorials
4. Admin-only content management
5. Real-time search with HTMX

### Technical Specifications
- Django project name: proj
- Django app name: car
- Database: SQLite (for development)
- Packages: django-filter, pillow, htmx
- Frontend: Bootstrap 5

### Data Models Needed
- MaintenanceTip:
  - title: CharField (tip name)
  - problem: TextField (description of issue)
  - fix: TextField (step-by-step solution)
  - video_url: URLField (YouTube link)
  - tools_needed: CharField (optional, comma-separated)

### Views/Pages Required
- Home: List all tips with search/filter
- Detail: Show single tip with video and instructions
- Admin: Django admin for CRUD operations

### User Roles & Permissions
- Anonymous users: View content only
- Admin users: Full CRUD via admin panel

### Special Requirements
- Real-time search with HTMX
- Mobile-responsive design
- YouTube embedding with URL parsing

### Design Preferences
- Clean, minimalist interface
- Card-based layout for tips
- Responsive video embeds
- Easy navigation

### Future Roadmap
1. Mobile app (React Native)
2. User favorites/saved tips
3. PDF export for offline use
