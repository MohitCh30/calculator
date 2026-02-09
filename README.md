# React Calculator

A simple calculator application built using React and Vite, focused on demonstrating correct usage of React fundamentals such as state management, controlled components, and event-driven UI updates.

## Overview

This project implements a basic calculator UI using React. The primary objective is not feature complexity, but clarity in component structure, predictable state updates, and clean separation between logic and presentation.

## Objectives

- Demonstrate practical usage of the useState hook
- Implement controlled components for predictable UI behavior
- Maintain a single source of truth for application state
- Handle user interactions using proper DOM events
- Follow clean and maintainable project structure

## Tech Stack

- React
- JavaScript (ES6+)
- Vite
- CSS Modules

## State Management

The application uses React’s useState hook to manage the calculator’s internal state.

- Calculator value is stored in state
- Button interactions update state via handlers
- Display renders purely from state
- No direct DOM manipulation is used

## Architecture

The application is structured using small, focused components.

- App  
  Owns the calculator state and business logic

- Display  
  Renders the current calculator value via props

- ButtonsContainer  
  Renders calculator buttons dynamically and forwards user actions

State is lifted to the App component to ensure predictable data flow.

## Features

- Controlled display component
- Event-driven input handling
- Dynamic button rendering
- Scoped component-level styling

## Design Decisions

The calculator is intentionally kept simple to emphasize correctness, clarity, and maintainability over feature richness.

## Limitations

- No keyboard input
- No scientific operations
- No calculation history

These limitations are intentional to keep the implementation focused.

## Getting Started

Clone the repository:

git clone https://github.com/MohitCh30/calculator

cd react-calculator

Install dependencies:

npm install

Start the development server:

npm run dev

The application will be available at http://localhost:5173

## Project Status

Core functionality complete.  
Structure is stable and extensible.

## Conclusion

This project demonstrates clean React fundamentals, effective use of useState, and disciplined component design suitable for hackathon or learning purposes.
