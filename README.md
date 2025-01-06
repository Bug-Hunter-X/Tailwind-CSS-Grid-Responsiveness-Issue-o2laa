# Tailwind CSS Grid Responsiveness Bug
This repository demonstrates a common issue encountered when using Tailwind CSS's grid system for responsive layouts.  The bug causes cards to overlap on smaller screens instead of stacking vertically.

## Bug Description
The provided HTML uses Tailwind CSS's `grid` utility to create a responsive card layout. However, on smaller screens (below the `md` breakpoint), the cards overlap instead of transitioning to a single-column layout.  This breaks the intended responsive design.

## Solution
The solution involves adjusting the `grid-cols` class to appropriately handle different screen sizes using Tailwind's responsive modifiers.

## How to reproduce the bug:
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Resize the browser window to observe the overlapping cards on smaller screens.

## How to use the solution:
1. Open `bugSolution.html` in your browser.
2. Resize the browser window to observe the correct responsive behavior.