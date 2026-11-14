# Apartment3D

An interactive, two-story house walkthrough reconstructed from supplied floor-plan photographs.

## Explore

Open `index.html` in a modern browser with WebGL support and internet access. No installation, database, or API keys are required. Three.js and material textures load from a CDN.

- **Walk inside:** drag to look; use WASD, arrow keys, or the on-screen movement buttons to move. The staircase connects both floors.
- **Dollhouse:** drag to orbit and scroll to zoom.
- **Floor / Go to:** switch levels or jump to a room.
- **Walls / Furniture:** show or hide either independently. Walls display at full height when enabled.
- **Daylight:** compare natural daylight, late-afternoon light, and overcast light.

The ground-floor TV and freestanding TV unit have been removed.

## Deploy on Vercel

Import this GitHub repository into Vercel and deploy. `vercel.json` configures static hosting without a build step, serving the repository root.

## Model accuracy

The model follows dimensions visible in the supplied photographs. Cropped areas, ceiling heights, some openings and door positions, furnishings, landscaping, and finishes are estimated or illustrative. It is a visualization, not a construction drawing or an accurate sunlight study.
