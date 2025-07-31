# Demon Slayer: Hashira Archives ⚔️

> A sleek, responsive, single-page fan website built for a college web development project. Coded from scratch with a focus on a clean, modern design and simple, readable code.

This project was an assignment to demonstrate core HTML and CSS skills. I chose to create a hub for Demon Slayer because it offered a great opportunity to build a stylish dark-mode interface and work with some amazing visuals.

### ✨ Features

*   **Fully Responsive Design:** Looks great on both desktop and mobile devices.
*   **Modern Dark Theme:** A clean, dark interface with vibrant accents inspired by the anime.
*   **Interactive Character Cards:** A gallery of the Hashira with hover effects and links to more info.
*   **Structured Data Table:** A clean table layout for presenting information on Breathing Styles.
*   **Embedded Media:** Includes a responsive YouTube video iframe.
*   **Pure HTML & CSS:** No frameworks, no libraries. Just the fundamentals.


### 🛠️ Built With

*   **HTML5:** Structured with semantic tags for accessibility and clarity.
*   **CSS3:** Styled with modern features like:
    *   Flexbox for the gallery layout.
    *   CSS Variables for easy theme customization.
    *   Transitions for smooth hover effects.
*   **Google Fonts:** Using the 'Roboto' font family for a clean, professional look.


### 🚀 Getting Started

Getting this project running locally is simple:

1.  Clone this repository or download the ZIP file.
    ```sh
    git clone https://github.com/Kartik-Sohal/Demon-Slayer-Hashira-Archives.git
    ```
2.  Navigate to the project directory.
3.  Open the `index.html` file in your favorite browser. That's it!


### 🎨 Make It Your Own

This project is open-source and perfect for anyone looking for a solid starting point for a similar assignment. Here’s how you can easily customize it:


#### Adding a New Character

Find the `.gallery-container` in `index.html`. To add another character, just copy an entire `<div class="character-card">...</div>` block and swap out the image URL, links, and text.

```html
<!-- Add this block inside the .gallery-container -->
<div class="character-card">
    <a href="WIKI_LINK" target="_blank">
        <img src="IMAGE_URL" alt="CHARACTER_NAME">
    </a>
    <h3>CHARACTER_NAME</h3>
    <p>SHORT_DESCRIPTION</p>
</div>
```

#### Changing the Theme Colors

Want a different color scheme? I used CSS Variables to make it incredibly easy. Open `style.css` and edit the values in the `:root` block at the top of the file.

```css
:root {
    --background-color: #121212;
    --accent-color: #00A3FF; /* Change this for a new accent color! */
    /* ... and so on */
}
```

This was a fun project to build, and I hope it can be useful to others. Feel free to fork this repo, make it your own, and maybe even show me what you create.

**Set your heart ablaze and happy coding!**
