# Depth Anything 3 Project Page

This directory contains the HTML project page for Depth Anything 3.

## Files

- `index.html` - Main project page with all sections and demos
- `styles.css` - CSS styles for the project page
- `script.js` - JavaScript functionality for interactions and carousels
- `generate_placeholders.html` - Tool to generate placeholder images for videos
- `README.md` - This file

## Features

### Design
- **Modern UI**: Clean, professional design with gradient backgrounds
- **Dark/Light Theme**: Toggle between dark and light modes
- **Responsive**: Works on desktop, tablet, and mobile devices
- **Smooth Animations**: Fade-in effects and smooth transitions

### Sections
1. **Banner**: Title, authors, and quick links
2. **Main Demo Video**: Primary demonstration video
3. **Overview**: TL;DR and Abstract
4. **Performance Comparison**: Benchmark charts
5. **Interactive Demos**: Multiple demo videos with descriptions
6. **Applications**: Carousel of application videos with descriptions
7. **Technical Analysis**: Carousel of analysis videos
8. **Model Specifications**: Different model variants and parameters
9. **Citation**: BibTeX citation format

### Interactive Features
- **Carousel Navigation**: Left/right arrows and dot indicators
- **Auto-play**: Automatic carousel rotation (pauses on hover)
- **Keyboard Navigation**: Arrow keys for carousel control
- **Touch Support**: Swipe gestures on mobile devices
- **Smooth Scrolling**: Navigation links scroll smoothly to sections

## Usage

### Setting Up Video Assets

1. Open `generate_placeholders.html` in a web browser
2. Click "Download All Placeholder Images" to get placeholder images
3. Replace the placeholder images with your actual video content:
   - `assets/main_demo_poster.jpg` - Main demo video poster
   - `assets/benchmark_comparison.png` - Performance comparison chart
   - `assets/interactive_demo1.mp4` - Multi-view depth estimation demo
   - `assets/interactive_demo2.mp4` - 3D Gaussian estimation demo
   - `assets/interactive_demo3.mp4` - Pose-conditioned depth demo
   - `assets/app_robotics.mp4` - Robotic navigation application
   - `assets/app_ar_vr.mp4` - AR/VR applications
   - `assets/app_autonomous_driving.mp4` - Autonomous driving application
   - `assets/app_3d_reconstruction.mp4` - 3D reconstruction application
   - `assets/analysis_architecture.mp4` - Network architecture analysis
   - `assets/analysis_ablation.mp4` - Ablation studies
   - `assets/analysis_failure_cases.mp4` - Failure case analysis

### Customization

- **Colors**: Modify CSS variables in `styles.css` to change the color scheme
- **Content**: Edit text content in `index.html`
- **Videos**: Replace video sources with your actual content
- **Layout**: Adjust grid layouts and spacing in CSS

### Deployment

Simply upload all files to your web server. The page is self-contained and doesn't require any server-side processing.

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## License

This project page is part of the [Depth Anything 3](https://github.com/ByteDance-Seed/depth-anything-3) project. Please refer to the main project license for usage terms.
