# Sort-Simulator

An interactive web application designed to visualize and understand how different sorting algorithms work through step-by-step animations.

The project provides a visual representation of sorting operations, making it easier to understand how algorithms rearrange elements and how their performance differs.

## Features

* Interactive visualization of sorting algorithms
* Step-by-step animation of sorting operations
* Visual representation of array elements
* Adjustable sorting speed
* Ability to generate and work with different arrays
* Simple and responsive user interface
* Real-time visualization of the sorting process

## Sorting Algorithms

The simulator demonstrates commonly used sorting techniques, including:

* Bubble Sort
* Selection Sort
* Insertion Sort
* Merge Sort
* Quick Sort

Each algorithm can be visualized to understand how elements are compared, swapped, and positioned during the sorting process.

## How It Works

The application represents the input data as visual elements on the screen.

When a sorting algorithm is selected, the application processes the elements step by step and updates the visualization after each operation.

This allows users to observe:

1. How elements are compared
2. How elements are swapped or moved
3. How the algorithm progresses
4. How the array becomes sorted

## Tech Stack

* HTML5
* CSS3
* JavaScript
* Vercel

The application uses vanilla HTML, CSS, and JavaScript to implement the interface, sorting logic, and visualization without relying on a large frontend framework.

## Project Structure

```text
Sort-Simulator/
├── css/
│   └── Stylesheets and UI styling
├── scripts/
│   └── Sorting algorithms and application logic
├── .vscode/
├── index.html
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## Running the Project Locally

### 1. Clone the repository

```bash
git clone https://github.com/snehazsingh123-create/Sort---simulator.git
```

### 2. Navigate to the project

```bash
cd Sort---simulator
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the application

```bash
npm start
```

If the project uses a different development command, use the script defined in `package.json`.

## Live Demo

[View the live application](https://sort-simulator.vercel.app/)

## Purpose

The main goal of this project is to make sorting algorithms easier to understand by converting algorithmic operations into an interactive visual experience.

It can be used as a learning tool for students and developers who want to understand the working and behavior of different sorting algorithms.

## Future Improvements

* Add more sorting algorithms
* Display time and space complexity
* Add comparison counters
* Add swap counters
* Improve mobile responsiveness
* Add algorithm complexity information
* Provide controls for array size and generation

