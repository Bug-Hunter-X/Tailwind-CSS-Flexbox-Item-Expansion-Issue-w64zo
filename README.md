# Tailwind CSS Flexbox Unexpected Behavior

This repository demonstrates a common issue encountered when using Tailwind CSS's flexbox utilities.  The problem arises when developers expect flex items to automatically expand to fill the available space within the container, without explicitly setting the necessary Tailwind classes.

## The Bug
The `bug.html` file shows a simple example of two divs within a flex container.  While the divs are styled with background colors, they only take up the space needed to display their text content. This might not be the desired behavior.

## The Solution
The `solution.html` file provides a fix by adding the `flex-1` class to each div. This ensures that each item expands to take up an equal share of the available space within the flex container.