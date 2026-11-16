# Lakeshore Lens Co. Created with React + Vite

- React 19.2.8
- Vite 8.2.2
- React Router Dom
- es-lint react hook



## How to run 

- git clone https://github.com/Jantioho26/lakeshore-lens-react.git
- cd lakeshore-lens-react 
- npm install 

## Features 

-**Interactive Lens Catalog**: Browse a collection of camera lenses with detailed specifications and descriptions.

-**Search Functionality**: Quickly find lenses by name, brand, type, or photography style.

-**Dynamic Filtering**: Narrow down lens options to find equipment that matches your photography needs.

-**Responsive Design**: Clean, user-friendly layout optimized for desktop and mobile devices.

-**Interactive UI**: Smooth navigation, hover effects, and visually appealing product cards for an engaging browsing experience.

<img width="1403" height="649" alt="Screenshot 2026-11-15 at 6 31 23 PM" src="https://github.com/user-attachments/assets/ed239aff-e8db-447d-9808-31e83dacfe0b" />

<br /> 

<img width="1392" height="620" alt="Screenshot 2026-11-15 at 6 31 48 PM" src="https://github.com/user-attachments/assets/751e931c-f7a6-47a1-a7a0-d408ee9c938e" />


## Performance Optimization

Improved mobile performance using Google Lighthouse to identify and resolve image-loading bottlenecks.

**Optimizations implemented:**
- Converted the hero background image from PNG to WebP.
- Resized the image from 6000px to 1920px wide.
- Reduced the hero image file size from 3.1 MB to 445 KB (86% reduction).
- Updated CSS and image preloading to prioritize the optimized asset.

### Lighthouse Results (Mobile)

| Metric | Before | After |
|---|---|---|
| Performance Score | 70 | **98** |
| Largest Contentful Paint | 18.0s | **2.3s** |
| First Contentful Paint | 1.2s | **0.8s** |
| Speed Index | 5.6s | **0.8s** |
| Total Blocking Time | 0ms | **0ms** |

*Results measured using Google Lighthouse with simulated mobile conditions. Individual test results may vary.*

