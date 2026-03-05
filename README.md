# Sorting Algorithm Visualizer

An interactive web application to visualize popular sorting algorithms. It helps learners understand how algorithms like Bubble Sort, Insertion Sort, and Selection Sort work, by showing the process in real-time with dynamic bars, metrics, and pseudo-code.

## Features

- Visualizes **Bubble Sort**, **Insertion Sort**, and **Selection Sort**
- Real-time **comparisons** and **swaps** metrics
- Adjustable **array size** and **sorting speed**
- Step-by-step **pseudo-code** display for each algorithm
- Modern, responsive UI with gradient backgrounds and animations

## Demo

You can see the sorting visualizer in action by opening `index.html` in your browser.

## Usage

1. Open `index.html` in your web browser.
2. Use the controls to:
   - Select an algorithm
   - Adjust array size and speed
   - Generate a new random array
3. Click **Start Sorting** to watch the visualization.

## How It Works

- Each bar represents an array element.
- The height of the bar corresponds to the element’s value.
- During sorting:
  - Red bars indicate the elements being compared.
  - Swaps and comparisons are tracked and displayed in real-time.

## Technologies Used

- HTML, CSS, JavaScript
- DOM manipulation for visual updates
- Async functions and `await sleep()` for smooth animations
