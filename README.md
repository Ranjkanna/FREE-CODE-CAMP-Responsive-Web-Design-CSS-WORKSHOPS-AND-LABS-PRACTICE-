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

> 💡 **Note on CSS Order:** The styles follow the strict **LVHA-order** (`:link`, `:visited`, `:hover`, `:active`) ensuring that the pseudo-classes override each other correctly without breaking
> <img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/75c04996-782c-49fd-b520-5cb5ae49fc21" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6843acfb-5aab-42d3-aa67-03f06fe6c16b" />
# Responsive Web Design: Event Flyer Page

A responsive event flyer webpage built as part of the freeCodeCamp Responsive Web Design certification. This project demonstrates structured HTML5 semantic layout architecture alongside clean, validated CSS positioning and scaling mechanics.

---

## 💻 Project Structure

The project is split cleanly into two structural layers to decouple content markup from presentation styling:
* `index.html` — Structural markup utilizing semantic headers, sections, and structural dividers.
* `styles.css` — Box-model parameters, viewport calculations, and percentage-based responsive scaling.
<img width="1920" height="1080" alt="Screenshot 2026-07-09 230556" src="https://github.com/user-attachments/assets/e3a82c32-384e-434f-b56a-31d1d770cc91" />
# 💌 Greeting Card Layout

A beautifully structured, interactive greeting card component demonstrating modern CSS pseudo-classes, dynamic hover animations, and CSS target state transitions.

---

## 🎯 Core Concepts Mastered

### 📦 Box Model & Centering
* **Responsive Card Constraints:** Configured a sharp `max-width: 400px` structure combined with adaptive padding to create a punchy, compact card footprint.
* **Flawless Component Alignment:** Leveraged the traditional `margin: 0 auto;` technique to center the card effortlessly within the brown body background.

### 🎭 Micro-Interactions & Transitions
* **Dynamic Hover Scales:** Paired `transform: scale(1.1);` with `background-color` transitions to give the card a smooth, tactile, "pop-out" depth effect on user hover.
* **Pseudo-Element Decorators:** Cleanly injected automated party emoji accents (`🥳`) before and after the main header utilizing CSS `::before` and `::after` strings.

### 🔗 Link States & Target Routing
* **Comprehensive Link Styling:** Mastered the full anchor lifecycle lifecycle by explicitly styling individual `:hover`, `:active`, `:focus`, and `:visited` interactive states.
* **CSS-Only State Toggles:** Implemented a clever `display: none;` layout that reveals hidden informational panels exclusively when their corresponding link anchor triggers the `:target` pseudo-class.
* <img width="1920" height="1080" alt="Screenshot 2026-07-10 210108" src="https://github.com/user-attachments/assets/8e0abc29-6b12-4c6a-a8b9-732aedcee826" />
<img width="1920" height="1080" alt="Screenshot 2026-07-10 210217" src="https://github.com/user-attachments/assets/caacf01f-481b-41c0-9681-227251cc9102" />
<img width="1920" height="1080" alt="Screenshot 2026-07-10 210654" src="https://github.com/user-attachments/assets/8ce4afcb-125f-4293-b562-911ba96144b5" />

# 🏫 Parent Teacher Conference Form

A meticulously structured, responsive registration form designed to handle scheduling coordination between parents and educators with precise layout control and visual harmony.

---

## 🎯 Core Concepts Mastered

### 🛠️ Strategic Form Alignment
* **Vertical Line Tracking:** Solved traditional baseline offset problems by implementing `vertical-align: bottom;` on customized `.contact-method-radio-btn` classes, locking elements cleanly inline with standard paragraph text.
* **Native Control Styling:** Leveraged `appearance: none;` on form checkboxes and radio items to remove default operating system skins, permitting bespoke brand borders and dimensions.

### 📐 Scoped Styling Architecture
* **Structural Isolation:** Isolated styling configurations safely down separate selector streams without repeating component declarations unnecessarily.
* **Component-Safe Scaling:** Used fluid constraints alongside standard grid/flex components to ensure responsive adaptability on form layouts across all display configurations.
* <img width="1920" height="1080" alt="Screenshot 2026-07-10 224614" src="https://github.com/user-attachments/assets/9635cfed-3947-49a2-b505-2ab2791c4325" />
<img width="1920" height="1080" alt="Screenshot 2026-07-10 224647" src="https://github.com/user-attachments/assets/7c5157e4-d66c-4968-9d59-657d51452c28" />
  
## Job Application form
* **code uses the `:has()` selector (`.radio-group label:has(...)`). This is a fantastic modern CSS feature that style a parent element based on its children! It is fully supported in all major modern browsers
<img width="1920" height="1080" alt="Screenshot 2026-07-11 222833" src="https://github.com/user-attachments/assets/6bef3bd6-a753-481d-b2c1-cf1d585e9822" />

## Color Marker 

A simple CSS project demonstrating color gradients, color formats (`rgb`, `rgba`, `hex`, `hsl`, `hsla`), and custom `box-shadow` styling on HTML markers.

---
**Linear Gradients:** Uses 3-stop gradients for a 3D cylindrical marker effect.
* **Color Models Used:**
  * **RGB / RGBA:** `rgb()` for solid red values and `rgba()` for transparent shadows/sleeves.
  * **HEX:** Standard 6-digit hex and 8-digit hex (`#3B7E20CC`) with alpha channel transparency.
  * **HSL / HSLA:** Hue, saturation, and lightness color stops for the blue marker.
  * 🛠️ Box-Shadow Requirements Breakdown

The `box-shadow` property adds a drop shadow effect around the marker elements using the syntax:
`box-shadow: [offsetX] [offsetY] [blurRadius] [spreadRadius] [color];`

| Selector | `offsetX` | `offsetY` | `blurRadius` | `spreadRadius` | Color Model & Value | Alpha / Transparency |
| :--- | :---: | :---: | :---: | :---: | :--- | :---: |
| `.red` | `0` | `0` | `20px` | `0` | **RGBA:** `rgba(83, 14, 14, 0.8)` | `80%` |
| `.green` | `0` | `0` | `20px` | `0` | **8-Digit Hex:** `#3B7E20CC` | `CC` (~80%) |
| `.blue` | `0` | `0` | `20px` | `0` | **HSLA:** `hsla(223, 59%, 31%, 0.8)` | `80%` |

---
  * * **Glow Effect:** Setting both horizontal (`offsetX`) and vertical (`offsetY`) offsets to `0` along with a positive `blurRadius` creates a soft, centered glow around each marker rather than a directional drop-shadow.
* **Alpha Channel Color Formats:** Demonstrates three distinct syntax patterns (`rgba`, 8-digit `#RRGGBBAA` Hex, and `hsla`) to apply identical semi-transparent shadow thresholds (`0.8` / `80%`).


