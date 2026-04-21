Create a photo granary with following specs.

1. Visual Design & Layout
Title: The gallery must prominently display the title "My photo gallery" at the top.
Modern Grid: Images will be arranged in a responsive grid that spans the full width of the browser.
Clean Aesthetic: Use a minimalist design with consistent spacing (margins/padding) between photos and no heavy borders or shadows.
Image Scaling: Photos will automatically adjust their size to fit any screen (mobile to desktop) while maintaining their focus using modern CSS cropping techniques.

2. Photo Content
Quantity: The page will feature a total of 20 photos. 
Nature Themes: The collection will include a diverse range of nature photography:
Landscape: Mountains, deserts, and forests.
Water: Waterfalls, oceans, and lakes.
Atmosphere: Northern lights, sunsets, and starry skies.
Macro: Close-ups of flowers, leaves, and moss.
Generate all the needed photos

3. Core Functionality (The "Lightroom" Effect)
Full-Screen View: Clicking any photo triggers a "Lightbox" mode where the background dims and the selected image appears in high resolution at the center of the screen.
Manual Navigation:
Right Arrow: Swaps the current view to the next image.
Left Arrow: Swaps the current view to the previous image.
Infinite Loop: Navigation is continuous; moving "next" from the 20th photo returns the user to the 1st photo.
Exit Strategy: Users can exit the full-screen view by clicking a "Close" button or tapping the dimmed area outside the image.

4. Technical Constraints (Strict)
Vanilla JavaScript Only: Absolutely no external libraries or frameworks (like jQuery, React, or Bootstrap). All logic must be written in raw, standard JavaScript.
Native HTML & CSS: Use only the built-in capabilities of modern web browsers to handle the layout and animations.
Zero Dependencies: The app should function perfectly as a standalone project with no need to download or link to outside scripts.

5. Perform the following tests
Open the App in a web browser
Click on the images and see the image opens in the lightbox
Check the navigation
