![My Digital Profile Card - Showcase Yourself Online!](./thumbnail.png)

# My Digital Profile Card

Welcome to your **Digital Profile Card** project! This is a fantastic beginner-level web development project designed to help you create a personalized online presence. You'll learn how to structure content with HTML, style it beautifully with CSS (using Tailwind CSS), and add simple interactivity with JavaScript.

Your goal is to make this profile card truly represent YOU!

## 🚀 How to Get Started

1.  **Download the Code:**
    * Copy all the HTML, CSS, and JavaScript code into a single file named `index.html`.
2.  **Open in Browser:**
    * Double-click `index.html` to open it in your web browser.
    * You'll see a basic profile card layout.
3.  **Start Customizing!** Follow the "TODO" comments in the `index.html` file and the steps below.

## 🎨 Personalization Guide (TODO List)

Look for `<!-- TODO: ... -->` comments directly in the `index.html` file to find these customization points!

### Easy Customization:

* **1. Page Title:**
    * Change the `<title>` tag in the `<head>` section (around line 5). This text appears in your browser tab.
* **2. Profile Picture:**
    * In the `<img>` tag inside `profile-image-wrapper` (around line 125), replace the `src` URL with a link to your own photo.
    * *Tip:* You can use free image hosting sites or a local image file (if it's in the same folder as `index.html`).
* **3. Your Name & Title:**
    * Change the `<h1>` with `class="profile-name"` (around line 128) to your full name.
    * Change the `<p>` with `class="profile-title"` (around line 131) to describe yourself (e.g., "Aspiring Coder," "Creative Designer," "Future Scientist").
* **4. About Me Section:**
    * Rewrite the paragraph inside the `<div class="about-section">` (around line 139) to share a bit about yourself, your passions, and what you enjoy.
* **5. Interests & Skills:**
    * In the `<div class="interests-list">` (around line 155):
        * **Edit Existing:** Change the text inside the `<span class="interest-badge">` tags to your actual interests or skills (e.g., "Robotics," "Drawing," "Playing Guitar," "Learning Python").
        * **Add More:** Copy and paste an existing `<span>` tag to add more interests.
* **6. Fun Fact:**
    * Inside the `<div id="funFactSection">` (around line 169), write a cool or funny fact about yourself that will be revealed when the button is clicked!
* **7. Your Email:**
    * In the `<span id="myEmail">` tag (around line 180), replace `your.email@example.com` with your actual email address. The "Copy Email" button will then copy *your* email!
* **8. Social Media Links:**
    * In the `<div class="social-links">` (around line 186):
        * Replace `href="#"` with the actual URLs to your LinkedIn, GitHub, Twitter (or other) profiles.
        * You can remove any `<a class="social-link">` blocks you don't need, or add more from Font Awesome (search for "fab" icons like `fab fa-instagram`).

### Intermediate Customization (Challenge Yourself!):

* **1. Change Colors & Fonts:**
    * Experiment with the `background-color` of the `body` and `.profile-card-container` in the `<style>` section.
    * Try different color gradients for the `body` (`background: linear-gradient(...)`).
    * Explore [Google Fonts](https://fonts.google.com/) for new font styles and update the `@import url(...)` and `font-family` properties.
* **2. Customize Interaction:**
    * The "Copy Email" and "Reveal Fun Fact" buttons are already set up. Can you think of another simple interaction to add using JavaScript?
        * **Idea:** A button that changes a picture on the card, or displays a different quote.
* **3. Favicon (Website Icon):**
    * Create a small image (`favicon.ico` or `favicon.png`) using an online favicon generator or your own design.
    * Add this line in the `<head>` section (around line 7):
        ```html
        <link rel="icon" href="path/to/your/favicon.ico" type="image/x-icon">
        ```
    * Update `href` to your favicon file's relative path.
* **4. Deploy Your Website (Make it Public!):**
    * Once you're happy with your card, search for "free website hosting service" (e.g., GitHub Pages, Netlify, Vercel).
    * Follow their instructions to upload your `index.html` and images to make your profile card accessible online!

Have fun creating your unique digital profile! This is a great step in showcasing your creativity and skills.