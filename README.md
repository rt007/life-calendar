# life-calendar
Life Calendar is a browser-based tool that visualises a person's life as a grid of small squares, where each square represents a unit of time (weeks, months, years) lived or remaining

## Overview
- Inputs: two number fields: current age (0–100, default 30) and life expectancy (1–100, default 80). A "Generate Calendar" button processes these values
- Outputs: three stat cards showing units lived, units remaining, and percentage of life lived. Below that, a colour-coded grid where purple squares represent time lived and grey squares represent time remaining. Hovering any square shows its unit number and lived/remaining status. A downloadable PDF containing the title, grid with Y-axis labels, and a quote on a clean white A4 page
- Functionalities: three view modes (weeks, months, years) that re-render the grid and recalculate stats dynamically. The weeks view shows 52 squares per row, months shows 12, and years shows 10. The grid is divided into 10-year blocks with visual spacing and labelled at every 5-year mark on the Y-axis. A light/dark theme toggle persists across interactions

## Tech Stack
- HTML5: structure and number inputs
- CSS3: styling, theme, layout,and animations
- Vanilla JavaScript: all logic, DOM manipulation, canvas rendering, and PDF generation

## Live Demo
https://lifecalendar.romalbuilds.com
*(Ctrl + Click to open in a new tab)*

---
