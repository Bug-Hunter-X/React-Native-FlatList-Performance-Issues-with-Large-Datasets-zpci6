# React Native FlatList Performance Bug

This repository demonstrates a common performance issue encountered when using React Native's `FlatList` component with extensive datasets.  The example showcases slow scrolling and janky animations due to inefficient rendering within the `renderItem` method.

The solution provided optimizes rendering by implementing techniques like item memoization and virtualization to drastically improve performance.  Explore the `FlatListSolution.js` file to learn how to effectively manage large datasets in `FlatList`.

## Bug Reproduction Steps

1. Clone this repository.
2. Run `npm install`.
3. Run `npx react-native run-android` or `npx react-native run-ios`.
4. Observe the slow and janky scrolling behavior of the FlatList.