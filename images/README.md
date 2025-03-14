# Online Images for ModernHaus Website

This website uses online placeholder images from services like Unsplash instead of local image files. The images are dynamically generated and applied through the utils/imageUtils.ts functionality.

## How it works

- The website uses Unsplash API to fetch high-quality architecture and interior design images
- Images are consistently generated based on project IDs to ensure the same images are displayed on each load
- All images are displayed with grayscale filter to match the black and white design theme
- No local image files are needed to run the website

## Customizing Images

If you want to use your own images later:

1. Replace the online image URLs in the utils/imageUtils.ts file with your local image paths
2. Add your images to the public/images/ directory
3. For project images, follow the naming convention: project-id-1.jpg, project-id-2.jpg, etc.

Note: When using local images, make sure all images are high-quality and have the right aspect ratio for their intended use. 