# Tailwind CSS - Styles Not Picking Up

This repository demonstrates a common issue when using Tailwind CSS: styles not being applied to components. The problem often lies in misconfiguring the `content` array in your Tailwind configuration file.

## Problem

The `bug.js` file shows a potential misconfiguration that causes Tailwind to ignore styles defined in your component files.  This happens when the paths specified in the `content` array do not accurately reflect the location of your components.

## Solution

The `bugSolution.js` file shows the correct way to configure the `content` array.  It ensures that Tailwind correctly scans through your project's files to pick up your custom styles.

## Steps to reproduce

1. Clone the repository
2. Install dependencies (if applicable) 
3. Run your build/development process, and observe that the styles are not correctly applied in the original example (bug.js). 
4. Update your Tailwind config file with the corrected `content` array (bugSolution.js).
5. Re-run your build/development process to confirm the styles are now correctly applied. 