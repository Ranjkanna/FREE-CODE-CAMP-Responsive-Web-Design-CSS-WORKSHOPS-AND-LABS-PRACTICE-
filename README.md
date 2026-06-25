# Responsive Web Design & HTML AND CSS Styling Workshops 🎨

A collection of semantic HTML5 and modern CSS3 user interface components, layout experiments, and responsive styling labs.

## Projects Showcase

### ☕ 1. Camper Cafe Menu Layout
A beautifully structured, responsive menu landing page demonstrating precise typography styling, element spacing, and container centering.

* **Core Concepts Mastered:**
    * **Box Model Mechanics:** Custom padding, container max-widths, and margin resets (`margin: auto`) to flawlessly center components on any screen scale.
    * **Visual Elements:** Custom horizontal rules (`<hr>`), semantic background property pairings, and explicit color matching rules.
    * **Negative Margin Shifting:** Utilizing strategic negative offsets (`margin-top: -25px;`) to precisely realign structural elements under visual icons.
    * <img width="1920" height="1080" alt="Screenshot 2026-06-19 184052" src="https://github.com/user-attachments/assets/6fc8cf42-2293-4f5d-9b15-5fc3fcb42e19" />

    ### 📇 2. Professional Business Card Component
A clean, elegant profile contact card focusing on text alignment, image scaling containment, and global typography fallback stacks.

* **Core Concepts Mastered:**
    * **Typographic Fallbacks:** Implementing strict font families (`Arial, sans-serif`) globally within the body element.
    * **Container Shorthand Centering:** Using horizontal auto-margins to anchor block elements perfectly in the center of the viewport.
    * **Text Decoration Stripping:** Removing anchor element underlines using custom text property configurations to achieve a modern interface.
    * <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/75aa0e90-be8e-4eba-8132-7665a686d018" />
# 📝 Styled To-Do List with Dynamic Links

A lightweight, semantic HTML and CSS project featuring a structured to-do list. This project highlights nested lists and custom interactive styling for hyperlinks using various CSS pseudo-classes.

## 🚀 Features

* **Structured Schedule:** A clean layout mapping out a daily routine (Wakeup, Gym, Breakfast, Office).
* **Nested Sub-items:** Includes relevant resource links (like YouTube playlists/videos) nested neatly under each main task.
* **Interactive Link States:** Features custom user-experience styling for links based on their current interactive state.

## 🛠️ Tech Stack

* **HTML5:** Utilizes semantic list structures (`<ul>`, `<li>`), checkboxes, and explicitly paired labels (`for` attributes matched to `id`s).
* **CSS3:** Custom pseudo-class styling for interactive elements.

## 🎨 CSS Styling Breakdown

The project focuses heavily on mastering the anchor (`<a>`) tag states. The links dynamically change color and style based on user interaction:

| State | Pseudo-class | Color / Style | Description |
| :--- | :--- | :--- | :--- |
| **Normal** | `a:link` | 🔵 Blue | The default color for an unvisited link. |
| **Visited** | `a:visited` | 🟣 Purple | The color of the link after a user has clicked it. |
| **Focus** | `a:focus` | ⚫ Black + Outline | Triggered when navigating via keyboard (Tab key) for accessibility. |
| **Hover** | `a:hover` | 🟢 Green | Triggered when a user hovers their mouse cursor over the link. |
| **Active** | `a:active` | 🟡 Yellow | The brief color flash right at the exact moment the link is clicked. |

> 💡 **Note on CSS Order:** The styles follow the strict **LVHA-order** (`:link`, `:visited`, `:hover`, `:active`) ensuring that the pseudo-classes override each other correctly without breaking.

## 🏗️ How to Run the Project

1. Save the HTML code into a file named `index.html`.
2. Save the CSS code into a file named `styles.css` in the same folder.
3. Open `index.html` in any modern web browser to see it in action!
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6843acfb-5aab-42d3-aa67-03f06fe6c16b" />

