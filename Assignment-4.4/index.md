Here is a complete template and guide for Assignment 4.4 — Metadata & Page Setup.

Since this assignment requires updating your existing HTML files, below is a fully updated HTML structure containing all required metadata tags, along with an explanation of each step and instructions for taking your screenshot and submitting your work.

Part 1: Updated HTML Code (index.html)
You can use this structure to update your HTML files (e.g., index.html, about.html, etc.).

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Step 1: Character Encoding -->
    <meta charset="UTF-8">

    <!-- Step 2: Mobile Viewport Meta Tag -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Step 3: Meaningful Title -->
    <title>My Portfolio | Web Developer & Designer</title>

    <!-- Step 4: Meta Description for SEO -->
    <meta name="description" content="Welcome to my personal portfolio website showcasing my web design projects, coding assignments, and front-end development skills.">

    <!-- Step 5: Favicon Integration -->
    <link rel="icon" type="image/x-icon" href="favicon.ico">

    <!-- Step 6: Correct CSS Link -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <h1>Welcome to My Website</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="about.html">About</a>
        </nav>
    </header>

    <main>
        <p>This page is configured with proper metadata, viewport settings, title, description, and favicon.</p>
    </main>

    <footer>
        <p>&copy; 2026 My Portfolio</p>
    </footer>

</body>
</html>
Part 2: Step-by-Step Breakdown & Verification
meta charset="UTF-8": Ensures proper character encoding so text, emojis, and symbols render correctly without corruption.

meta name="viewport" ...: Ensures responsive rendering on mobile devices by setting the width to the device screen size and establishing an initial zoom level of 1.0.

<title>: Sets a clear, search-engine-friendly title that appears on the browser tab.

meta name="description": Provides search engines with a concise summary of what the page contains.

link rel="icon": Links an icon file (favicon.ico) to display next to the page title in the browser tab.

link rel="stylesheet": Connects the external CSS stylesheet (styles.css) using a valid relative file path.

Part 3: How to Complete & Submit Your Assignment
Favicon Setup:

Place an image file named favicon.ico (or favicon.png) in the same root folder as your HTML files.

If using PNG format, update the link tag to:

HTML
<link rel="icon" type="image/png" href="favicon.png">
Taking the Screenshot:

Open your index.html file in Google Chrome or any browser.

Look at the browser tab at the very top.

Take a screenshot of the tab bar showing both the Page Title and the Favicon icon clearly.

Final Submission Package:

Submit your updated HTML file(s) (index.html, etc.).

Submit the snippet of the <head> section containing the metadata code.

Attach your browser screenshot showing the favicon working on the tab.