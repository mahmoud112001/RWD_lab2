# Responsive Web Design - Lab 2: CSS Grid Layout

This is a lab exercise from ITI (Information Technology Institute) focused on **Responsive Web Design** using CSS Grid.

## Overview

This lab demonstrates the fundamentals of CSS Grid layout techniques for creating responsive and flexible web page layouts. The exercise includes two main approaches to building grid-based layouts and showcases responsive design principles.

## Files

### 1. **gridAreaPage.html**
A complete page layout using **CSS Grid with `grid-template-areas`**. This demonstrates:
- Using named grid areas for semantic layout
- Building a classic webpage structure with header, footer, sidebars, and main content
- Responsive design that stacks vertically on mobile devices (max-width: 600px)
- Three-column layout on desktop and single-column on mobile

**Layout Structure:**
```
Header (full width)
Sidenav | Main Content | Sidebar
Footer (full width)
```

### 2. **gridBoxes.html**
A grid layout using **explicit row and column placement** with an animation effect. This demonstrates:
- Using `grid-template-columns` and `grid-template-rows`
- Spanning multiple columns and rows with `grid-row` and `grid-column`
- CSS animations and transformations
- Responsive color changes on smaller screens (max-width: 700px)
- 3x3 grid with custom box placements

**Features:**
- Rotation animation that continuously rotates boxes 45 degrees
- Color scheme changes for mobile responsiveness
- Various box sizes using grid span properties

## Key Concepts Covered

- ✅ CSS Grid display
- ✅ Grid template areas for semantic layouts
- ✅ Grid row and column spanning
- ✅ Grid gaps and spacing
- ✅ Media queries for responsive design
- ✅ CSS animations
- ✅ Flexbox centering

## Resources

- **Screen Recording (Grid Areas):** [https://screenrec.com/share/PHW9s1nob7](https://screenrec.com/share/PHW9s1nob7)
- **Screen Recording (Grid Rows/Columns):** [https://screenrec.com/share/FrNWhUGSfy](https://screenrec.com/share/FrNWhUGSfy)
- **GitHub Repository:** [https://github.com/mahmoud112001/RWD_lab2](https://github.com/mahmoud112001/RWD_lab2)

## How to Use

1. Open either HTML file in a web browser
2. Resize the browser window to see responsive behavior
3. For desktop vs mobile layouts, use browser developer tools (F12) to toggle responsive design mode

## Learning Outcomes

By completing this lab, you will understand:
- How to create responsive layouts using CSS Grid
- Different approaches to grid design (template areas vs explicit placement)
- How to implement mobile-first or desktop-first responsive design
- How to combine modern CSS with animations
