# Asad Button Library 
> A comprehensive CSS/SCSS button library featuring 500+ unique button effects and animations
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CSS](https://img.shields.io/badge/CSS-SCSS-ff69b4.svg)](https://sass-lang.com/)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]()


##  Features

-  **500+ Unique Button Effects** - From simple hover states to complex 3D animations
-  **Modular SCSS Architecture** - Clean, maintainable, and customizable code structure
-  **BEM-inspired Class System** - Easy integration with existing projects
-  **Zero Dependencies** - Pure CSS/SCSS implementation


##  Button Categories

| Category | Description | Examples |

|----------|-------------|----------|

| **Basic Effects** | Simple hover states and transitions | Basic, Outline |
| **Slide & Movement** | Dynamic sliding animations | Slide Right/Left/Top/Bottom |
| **Scale & Animation** | Zoom, shake, and loading effects | Scale Up/Down, Shake, Loading |
| **Gradient & Color** | Beautiful gradient transitions | Gradient Shift, Flow, Border |
| **Border Effects** | Creative border animations | Border Grow, Pulse, Slide |
| **Fill & Transform** | Split fills and morphing effects | Vertical/Horizontal Split Fill |
| **Text Effects** | Typography animations | Text Change, Transform, Shake |
| **3D & Depth** | Three-dimensional effects | Press Button, Curved, Lighting |
| **Glass & Glow** | Modern glassmorphism and neon | Glass Gradient, Glow Pink/Neon |
| **Advanced** | Neumorphic, retro, and experimental | Neumorphic, Cyber Wobble |

##  Quick Start

### 1. Setup

- Basic Usage

<!-- Basic button -->
<button class="btn btn-basic">Click Me</button>
<!-- With slide effect -->
<button class="btn slide-in-btn slide-right">Slide Right</button>
<!-- With gradient effect -->
<button class="btn gradient-shift-btn">Gradient Shift</button>

📚 Documentation
Base Button Structure
All buttons require the base .btn class:

<button class="btn">Base Button</button>

Adding Effects
Combine base class with effect classes:

<!-- Slide effects -->
<button class="btn slide-in-btn slide-right">Slide Right</button>
<button class="btn slide-in-btn slide-left">Slide Left</button>
<!-- Gradient effects -->
<button class="btn gradient-shift-btn">Gradient Shift</button>
<button class="btn gradient-flow-btn">Gradient Flow</button>
<!-- Scale effects -->
<button class="btn scale-btn scale-up">Scale Up</button>
<button class="btn scale-btn scale-down">Scale Down</button>

Size Modifiers
<button class="btn btn-xs">Extra Small</button>    <!-- 8px 12px -->
<button class="btn btn-sm">Small</button>          <!-- 12px 16px -->
<button class="btn btn-md">Medium</button>         <!-- 16px 32px (default) -->
<button class="btn btn-lg">Large</button>          <!-- 24px 40px -->
<button class="btn btn-xl">Extra Large</button>    <!-- 28px 44px -->

Spacing Utilities
<!-- Padding block (top/bottom) -->
<button class="btn pb-1">4px top/bottom</button>
<button class="btn pb-3">12px top/bottom</button>
<button class="btn pb-6">24px top/bottom</button>
<!-- Padding inline (left/right) -->
<button class="btn pi-2">8px left/right</button>
<button class="btn pi-4">16px left/right</button>
<button class="btn pi-6">24px left/right</button>

Border Radius Options
<button class="btn radius-none">No Radius</button>
<button class="btn radius-xs">4px Radius</button>
<button class="btn radius-sm">8px Radius</button>
<button class="btn radius-md">12px Radius</button>
<button class="btn radius-lg">20px Radius</button>
<button class="btn radius-xl">32px Radius</button>
<button class="btn radius-pill">Pill Shape</button>
<button class="btn radius-square">Square</button>

Some Button Examples

Gradient Collection

<!-- Animated gradient shift -->
<button class="btn gradient-shift-btn">Gradient Shift</button>
<!-- Flowing gradient background -->
<button class="btn gradient-flow-btn">Gradient Flow</button>
<!-- Plain to gradient transition -->
<button class="btn plain-to-gradient">Plain to Gradient</button>
<!-- Gradient border effect -->
<button class="btn gradient-border">
  <span class="gradient-border-span">Gradient Border</span>
</button>

Slide Animations

<!-- Basic directional slides -->
<button class="btn slide-in-btn slide-right">Slide Right</button>
<button class="btn slide-in-btn slide-left">Slide Left</button>
<button class="btn slide-in-btn slide-top">Slide Top</button>
<button class="btn slide-in-btn slide-bottom">Slide Bottom</button>
<!-- Advanced slide effects -->
<button class="btn slide-in-btn left-to-right"><span>Left to Right</span></button>
<button class="btn slide-across">Slide Across</button>

3D & Special Effects

<!-- 3D press effect -->
<button class="btn press-btn">Press Button</button>
<!-- Neumorphic design -->
<button class="btn btn-neumorphic">Neumorphic</button>
<!-- Neon glow effect -->
<button class="btn glow-neon">Glow Neon</button>
<!-- Glass effect -->
<button class="btn glass-gradient">Glass Gradient</button>

Customization

SCSS Variables
Customize colors, spacing, and animations in _variables.scss:

// Primary Colors
$color-org: #ff8c00;      // Primary orange
$white: #fff;
$black: #000;

// Button Sizing

$padding: 16px 32px;       // Default padding
$padding-lg: 24px 40px;    // Large padding
$padding-xs: 8px 12px;     // Small padding

// Border Radius

$radius20: 20px;           // Default radius
$radius15: 15px;
$br-4: 4px;               // Small radius

// Animations

$btn-transition: all 0.3s ease-in-out;
$btn-transition-long: all 0.4s ease-in-out;

// Typography

$text-base: 16px;
$font-medium: 500;
$ls-1: 1px;               // Letter spacing


📁 Project Structure
buttonica/
├── index.html                  # Live demo with all 500+ buttons
├── index.scss                  # Main SCSS entry point
├── _variables.scss             # Customizable variables
├── _base.scss                  # Base button foundation
├── _all-button.scss            # Complete button implementations
├── _animations.scss            # Keyframe animations library
├── _spacing.scss               # Spacing utility classes
├── _sizes.scss                 # Size modifier classes
├── _mixins.scss                # SCSS helper mixins
├── _reset.scss                 # CSS reset and base styles
└── dist/
    └── buttonica.css           # Compiled production CSS


--  Showcase

Perfect for:
-  UI/UX Portfolios - Demonstrate animation and design skills
- Web Applications - Enhance user interaction and engagement
-  Landing Pages - Create compelling call-to-action buttons
- Interactive Projects - Add polished button interactions
- Learning Resource - Study modern CSS animation techniques



--  Contact

Your Name - asadusama121@gmail.com

