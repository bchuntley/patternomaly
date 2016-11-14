# Patternomaly

Easily generate patterns for use in data graphics.

<img src="./assets/example.png" alt="Pattern example" width="650">

## But why?

[Color-blindness](http://betweentwobrackets.com/data-graphics-and-colour-vision/), that's why.

This library came about as part of [an issue in Chart.js](https://github.com/chartjs/Chart.js/issues/1323).

## Usage

    npm install patternomaly

Generate a single canvas pattern

    pattern.draw('square', '#1f77b4');

Generate an array of canvas patterns

    pattern.generate([
      '#1f77b4',
      '#ff7f0e',
      '#2ca02c',
      '#d62728'
    ]);
