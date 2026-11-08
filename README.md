# 🎡 CSS Ferris Wheel Animation — Pure CSS Motion & Illustration

> A colorful, continuously rotating Ferris wheel illustration built entirely with HTML5 and CSS3. This project demonstrates modern CSS animation techniques, including keyframes, transforms, transform origins, geometric positioning, custom properties, and responsive design.

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/CSS-Animations-8A2BE2?style=for-the-badge" alt="CSS Animations">
  <img src="https://img.shields.io/badge/Responsive-Design-26C6B5?style=for-the-badge" alt="Responsive Design">
  <img src="https://img.shields.io/badge/JavaScript-Not%20Required-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="No JavaScript">
</p>

---

## 📖 Overview

**CSS Ferris Wheel Animation** is a creative front-end development project that recreates a colorful Ferris wheel using pure HTML5 and CSS3.

The illustration features a rotating wheel, multiple passenger cabins, geometric support structures, decorative clouds, a sun, and a colorful outdoor background.

The wheel continuously rotates using CSS keyframe animations, while individual cabins use counter-rotation transformations to maintain their upright orientation throughout the movement.

Built without JavaScript, external animation libraries, or CSS frameworks, this project explores how modern CSS techniques can create engaging animated illustrations and interactive visual experiences.

## ✨ Key Features

- **Continuous Wheel Rotation:** Uses CSS keyframes to create smooth, uninterrupted 360-degree rotation.
- **Upright Passenger Cabins:** Applies counter-rotation transformations to keep all cabins vertically aligned while the wheel moves.
- **Geometric Wheel Structure:** Uses circular borders, CSS positioning, and transformed elements to construct the Ferris wheel.
- **Multiple Passenger Cabins:** Features eight individually styled cabins with different colors.
- **Custom CSS Properties:** Uses reusable variables to manage colors, dimensions, and animation speed.
- **Transform Effects:** Demonstrates rotation, translation, and transform-origin techniques.
- **Decorative Sky Background:** Includes a sun, clouds, and gradient-based sky styling.
- **CSS-Generated Support Structure:** Creates the wheel's supporting framework using positioned elements and geometric transformations.
- **Responsive Layout:** Adjusts wheel dimensions, cabin sizes, and structural proportions on smaller screens.
- **Reduced Motion Support:** Respects the user's reduced-motion preference by pausing animations.
- **Lightweight Implementation:** Requires no JavaScript, external frameworks, or third-party animation dependencies.

## 🎡 Project Components

The illustration is organized into several visual components.

### 1. Sky Background

The background establishes the outdoor environment surrounding the Ferris wheel.

| Component | Description |
|---|---|
| Sky | Gradient-based blue background. |
| Sun | Circular decorative element with a glowing effect. |
| Clouds | CSS-generated cloud shapes using pseudo-elements. |
| Ground | Green gradient surface representing the ground. |

### 2. Ferris Wheel Structure

The central wheel consists of several architectural elements.

| Component | Description |
|---|---|
| Wheel Rim | Creates the outer circular structure. |
| Inner Rim | Adds additional detail to the wheel. |
| Spokes | Connect the central axle to the outer wheel. |
| Center Axle | Forms the central rotating connection. |
| Passenger Cabins | Eight colorful cabins positioned around the wheel. |

### 3. Support Structure

The support structure provides the visual foundation of the Ferris wheel.

It consists of:

- Left support beam.
- Right support beam.
- Horizontal crossbar.
- Bottom support base.

### 4. Passenger Cabins

The Ferris wheel features eight differently colored cabins.

| Cabin | Color |
|---|---|
| Cabin 1 | Red |
| Cabin 2 | Blue |
| Cabin 3 | Yellow |
| Cabin 4 | Green |
| Cabin 5 | Purple |
| Cabin 6 | Orange |
| Cabin 7 | Pink |
| Cabin 8 | Teal |

Each cabin includes a decorative roof, window, and bottom section.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Provides the structural elements used to construct the illustration. |
| CSS3 | Controls visual styling, dimensions, positioning, and effects. |
| CSS Custom Properties | Defines reusable colors, dimensions, and animation settings. |
| CSS Keyframes | Creates continuous Ferris wheel rotation and cabin counter-rotation. |
| CSS Transforms | Controls rotation and geometric positioning. |
| Transform Origin | Defines the pivot points for animated elements. |
| CSS Flexbox | Organizes and aligns visual components. |
| Linear Gradients | Creates sky, ground, and decorative backgrounds. |
| CSS Positioning | Arranges the wheel, cabins, and supporting structures. |
| CSS Media Queries | Adjusts the illustration for smaller screen sizes. |

## 🎨 Design & Implementation

The project uses a colorful amusement park-inspired design with contrasting cabin colors, a bright sky, and a structured Ferris wheel.

### Color Palette

| Element | Color | Hexadecimal |
|---|---|---|
| Sky | Light Blue | `#b9e6ff` |
| Ground | Green | `#7bc67b` |
| Wheel Structure | Dark Navy | `#26364d` |
| Wheel Accent | Golden Yellow | `#e5a83e` |
| Red Cabin | Red | `#f05d5e` |
| Blue Cabin | Blue | `#3985d6` |
| Yellow Cabin | Yellow | `#f5c542` |
| Green Cabin | Green | `#35a879` |
| Purple Cabin | Purple | `#8864c9` |
| Orange Cabin | Orange | `#ed8a42` |
| Pink Cabin | Pink | `#df75a8` |
| Teal Cabin | Teal | `#36aaa5` |

### CSS Animation Techniques

**1. CSS Keyframes**

The `@keyframes` rule defines the animation sequences used to rotate the Ferris wheel and maintain the orientation of individual cabins.

**2. Transform Rotation**

The `rotate()` transformation rotates the wheel through a complete 360-degree cycle.

**3. Cabin Counter-Rotation**

Individual cabins use an opposite rotation angle to compensate for the wheel's movement and maintain their upright appearance.

**4. Transform Origin**

The `transform-origin` property controls the pivot point around which elements rotate.

**5. Animation Timing**

The `linear` timing function maintains a consistent rotation speed throughout the animation.

**6. CSS Custom Properties**

Variables make it easier to control the wheel's dimensions, cabin positioning, colors, and animation duration without repeating hardcoded values.

## ⚙️ Animation Configuration

The Ferris wheel's animation can be customized through CSS variables.

| Variable | Default Value | Purpose |
|---|---|---|
| `--wheel-size` | `360px` | Controls the wheel dimensions. |
| `--cabin-distance` | `170px` | Controls the distance between the wheel center and cabins. |
| `--animation-speed` | `20s` | Controls the wheel's rotation duration. |

To change the rotation speed, update the following variable:

```css
:root {
  --animation-speed: 20s;
}
```

For example:

- `10s` produces faster rotation.
- `20s` produces the default rotation speed.
- `30s` produces slower rotation.

The wheel completes one full rotation within the configured animation duration.

## 📱 Responsive Design

The illustration includes responsive adjustments to maintain its visual proportions across different screen sizes.

**Desktop:**

- Displays the full-size Ferris wheel.
- Uses larger passenger cabins.
- Maintains the complete support structure.
- Provides additional space for the decorative background.

**Mobile and Smaller Screens:**

- Reduces the wheel dimensions.
- Adjusts cabin sizes and positioning.
- Resizes the supporting structure.
- Maintains the overall illustration composition.

The project also includes a `prefers-reduced-motion` media query to accommodate users who prefer reduced animation.

## ♿ Accessibility Considerations

The project incorporates several accessibility-conscious practices:

- Uses a semantic HTML5 document structure.
- Includes descriptive page metadata.
- Provides an accessible label for the Ferris wheel illustration.
- Supports reduced-motion preferences through CSS media queries.
- Uses sufficient visual contrast between major illustration components.

## 📂 Project Structure

```text
CSS-Ferris-Wheel-Animation/
│
├── index.html       # HTML structure and illustration components
├── styles.css       # CSS styling, animations and responsive design
│
└── README.md        # Project documentation
```

## 🚀 Getting Started

Follow these steps to download and run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Regalson001/CSS-Ferris-Wheel-Animation.git
```

### 2. Navigate to the Project Directory

```bash
cd CSS-Ferris-Wheel-Animation
```

### 3. Open the Project

Open the project folder in Visual Studio Code.

```bash
code .
```

### 4. Run the Website

Open `index.html` directly in your preferred web browser.

Alternatively, install the **Live Server** extension in Visual Studio Code and select **Open with Live Server**.

No additional dependencies or installation steps are required.

## 🧠 Skills Demonstrated

This project demonstrates practical knowledge and application of:

- HTML5 document structure and semantic elements.
- CSS3 styling and visual composition.
- CSS animations and keyframe sequences.
- Transform properties and geometric positioning.
- Transform-origin manipulation.
- Animation timing functions.
- CSS custom properties and reusable variables.
- Flexbox layout and alignment.
- Circular structures and geometric shapes.
- Gradient backgrounds and decorative effects.
- Responsive design using CSS media queries.
- Accessibility-conscious motion preferences.
- Clean, organized, and maintainable CSS code.

## 🔮 Future Improvements

Potential enhancements for future versions include:

- Introduce additional passenger cabins and wheel designs.
- Add more sophisticated lighting and shadow effects.
- Create alternative daytime, sunset, and nighttime themes.
- Add decorative amusement park elements.
- Introduce adjustable animation speeds.
- Develop additional CSS-only motion effects.
- Improve responsive proportions for smaller devices.
- Experiment with advanced cubic-bezier animation timing functions.

## 🎯 Project Objective

The objective of this project is to demonstrate how modern CSS animation and transformation techniques can be combined with HTML5 to create visually engaging illustrations without JavaScript or external animation frameworks.

It reinforces the importance of understanding keyframes, transforms, transform origins, positioning, animation timing, and responsive styling while developing practical front-end animation skills.

## 👨‍💻 Author

**Stephen Oyugi**

Front-End Developer | HTML5 & CSS3

Passionate about building clean, responsive, accessible, and user-friendly web experiences through modern front-end development practices.

- **GitHub:** [@Regalson001](https://github.com/Regalson001)
- **GitHub Profile:** [github.com/Regalson001](https://github.com/Regalson001)
- **Repository:** [CSS-Ferris-Wheel-Animation](https://github.com/Regalson001/CSS-Ferris-Wheel-Animation)

---

<p align="center">
  <strong>Building better web experiences, one project at a time.</strong>
  <br><br>
  ⭐ If you find this project useful, consider giving it a star!
</p>
