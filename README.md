# User Directory App

A responsive web app that displays and filters user data from an API.

## Features

- Fetches user data from JSONPlaceholder  
- Search by name, email, company or Phone no  
- Responsive card layout  
- Detailed user modal  
- Designed using Tailwind CSS

## Setup

1. Download zip file of this repo  
2. Open `index.html` in any modern browser directly  
3. Or you can use Vs code live server extension to open it

## Dependencies

CDN-hosted:  
- Tailwind CSS  
- jQuery  
- Font Awesome

## Approach

1. Data Fetching:  
   - Used jQuery's AJAX to fetch user data from JSONPlaceholder

2. UI Components:  
   - Created responsive user cards with Tailwind CSS  
   - Added hover effects and transitions for interactivity  
   - Designed a modal dialog for detailed user information

3. Search Functionality:  
   - Implemented client-side filtering that searches across multiple fields  
   - Added debouncing (implicit via input event) for better performance  
   - Included a "no results" state for empty search results

4. Performance:  
   - Minimized DOM manipulations by storing fetched data  
   - Used event delegation for dynamic elements  
   - Implemented smooth animations for modal transitions
