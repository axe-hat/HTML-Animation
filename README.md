# CSS Animation Showcase

A collection of pure CSS animations demonstrating keyframe techniques, transforms, and visual effects -- no JavaScript required.

## Animations Included

### Netflix Logo Animation (`netflix.html`)
A recreation of the Netflix logo intro animation. Three vertical bars grow sequentially with staggered delays, creating the iconic "N" shape using CSS transforms (skewX) and keyframe animations.

### Geometric Pendulum Animation (`project1.html`)
An abstract kinetic animation featuring:
- A swinging pendulum bar that rotates back and forth
- A bouncing ball that slides along the pendulum arm
- A large circle element that drifts horizontally
- A background sphere for visual depth

## How to View

Open any `.html` file directly in your browser -- no build tools or server needed.

```
# Clone and open
git clone https://github.com/axe-hat/HTML-Animation.git
cd HTML-Animation
open netflix.html       # macOS
xdg-open netflix.html   # Linux
```

## Browser Compatibility

These animations use standard CSS3 features supported by all modern browsers:

- Chrome 43+
- Firefox 16+
- Safari 9+
- Edge 12+

CSS custom properties (used in animations.css) require:
- Chrome 49+
- Firefox 31+
- Safari 9.1+
- Edge 15+

## Tech Stack

- **HTML5** -- semantic markup with accessibility attributes
- **CSS3** -- keyframe animations, transforms, custom properties, flexbox
- No JavaScript, frameworks, or build tools

## Project Structure

```
HTML-Animation/
├── netflix.html          # Netflix logo animation page
├── project1.html         # Geometric pendulum animation page
├── css/
│   ├── netflix.css       # Netflix animation styles
│   └── animations.css    # Geometric animation styles with CSS custom properties
├── .gitignore
└── README.md
```

## Accessibility

Both animations respect the `prefers-reduced-motion` user preference. When reduced motion is enabled, animations are paused and elements are displayed in their final/neutral positions.
