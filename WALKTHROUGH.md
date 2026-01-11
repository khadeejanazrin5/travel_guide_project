# VoyageSync - Walkthrough

**VoyageSync** is a modern, premium travel guide application completed as per specs.

## Features Implemented

### 1. Home & Discovery
- **Hero Section**: Immersive parallax background with glassmorphism search bar.
- **Destination Grid**: Filterable list of destinations (e.g., "Cultural", "Romance") with mock data.
- **Map View**: Integrated Leaflet map togglable from the Home page.

### 2. Destination Details
- **Dynamic Routing**: `/destination/:id` loads specific destination data.
- **Rich UI**: High-quality images, description, pricing, and attractions.
- **Add to Itinerary**: One-click action to save trips.

### 3. Itinerary Planner
- **Context API**: Global state management for trip items.
- **Itinerary Page**: Review saved destinations and see the total cost.

## Technology Stack
- **Framework**: React + Vite
- **Styling**: Vanilla CSS (Variables, Glassmorphism, Responsive)
- **Maps**: React Leaflet
- **Icons**: Lucide React

## How to Run

1.  Open text terminal in `travel_guide_project`.
2.  Run the development server:
    ```bash
    npm run dev
    ```
3.  Open the local URL (usually `http://localhost:5173`).

## Verification Results
- **Build**: Passed (`npm run build`).
- **Linter**: Passed.
- **Node.js**: Environment configured via winget.
