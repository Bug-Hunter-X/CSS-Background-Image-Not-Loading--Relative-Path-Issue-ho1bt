# CSS Background Image Loading Issue

This repository demonstrates a common, yet often overlooked, error in CSS: the failure to load a background image due to an incorrect relative path.  The `bug.css` file contains the flawed CSS, while `bugSolution.css` provides the corrected version.

## Problem
The initial CSS attempts to set a background image, but it fails because the path to the image is not correctly specified. This results in a blank background. 

## Solution
The solution involves ensuring that the relative path to the image is accurate and points to the image's correct location relative to the CSS file.  The updated CSS in `bugSolution.css` demonstrates this.