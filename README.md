# React Native FlatList Rendering Issue

This repository demonstrates a common bug encountered when using the FlatList component in React Native with large datasets.  The issue is characterized by incorrect item rendering during fast scrolling, leading to visual glitches and potentially incorrect data display.

## Problem

When scrolling rapidly through a FlatList containing a substantial amount of data, the component fails to render items correctly. This may manifest as blank spaces, duplicated items, or items showing the wrong data.

## Solution

The solution involves ensuring efficient key extraction and potentially optimizing data handling.  See `bugSolution.js` for a corrected implementation.