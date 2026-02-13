# Version History

## v1.0.0 - Initial Release
- **Date**: 2026-02-13
- **Features**:
  - Initial project structure.
  - Basic HTML5 semantic layout (Hero, About, Skills, Experience, Projects, Contact).
  - Dark mode aesthetic with purple/neon green accents (.NET theme).
  - Responsive design basics.

## v1.1.0 - Enhanced UI/UX
- **Date**: 2026-02-13
- **Features**:
  - Added "Glassmorphism" styling to cards.
  - Implemented smooth scrolling and scroll animations (Intersection Observer).
  - Added custom cursor glow effect.
  - Mobile responsiveness improvements (Hamburger menu).

## v1.2.0 - Theme System (Deprecated)
- **Date**: 2026-02-13
- **Features**:
  - Added Light/Dark mode toggle.
  - Introduced CSS variables for theming (`--bg-color`, `--text-color`, etc.).
  - *Note: Removed in v1.3.0 to focus on a premium Dark Mode experience.*

## v1.3.0 - Premium Dark Mode Optimization
- **Date**: 2026-02-13
- **Changes**:
  - **Removed** Light Mode to maintain brand consistency and premium feel.
  - **Refined** Color Palette: High-contrast text for better readability.
  - **Fixed** Navigation Visibility: Menu items are now strictly white/bright against the dark header.
  - **Cleanup**: Removed unused toggle logic and buttons.

## v1.3.1 - Critical Visibility Fixes (Current)
- **Date**: 2026-02-13
- **Fixes**:
  - **Restored** missing CSS variables (`--text-color`, `--heading-color`) that caused invisible text.
  - **Enhanced** Project Cards: Added dark gradient background and borders for better separation.
  - **Forced Visibility**: Applied `!important` white color rules for `h3` headings in Experience/About sections and Project links.
  - **Contrast**: 
    - Brightened primary color (`#8c52ff`) for better visibility.
    - Lightened footer text and input backgrounds.
    - Increased opacity of glass effect for better component definition.
