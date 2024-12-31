# React Native Dimensions API Not Updating on Orientation Change

This repository demonstrates a bug and its solution related to the `Dimensions` API in React Native. The bug occurs when the screen dimensions don't update correctly after an orientation change. This can lead to layout issues and incorrect rendering.

## Bug
The original code uses `Dimensions.get('window')` to get screen dimensions, which might not always reflect the changes after orientation change.

## Solution
The solution involves using the `Dimensions` API's event listener to detect changes. This ensures that the component re-renders with the updated dimensions.