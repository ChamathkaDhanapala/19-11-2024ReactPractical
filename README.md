# React Parent-Child Communication Example

This project demonstrates how to handle parent-child communication in React using props and state. The parent component (`App.js`) sends a function to the child component (`ChildComp`) as a prop, and the child component communicates back with the parent.

## Features

- Parent component renders a message.
- Child component receives a function as a prop to send data back to the parent.
- State management using `useState` to dynamically update content in the parent component based on the child's input.

## File Structure

my-app/         
├── src/
│   ├── App.js              
│   ├── App.css 
    ├── ChildComp.js
├── README.md                
├── package.json             

## Installation

1. Clone the repository:
   -git clone https://github.com/ChamathkaDhanapala/19-11-2024ReactPractical
2.Navigate to the project directory:
   -cd myapp
3. Install dependencies:
   -npm install
4.Start the development server:
   -npm start

 ## Usage
-The App component initializes a state variable (childname) with a default value.
-The ChildComp component uses the setfun prop to send a message ("My Name is Bob") back to the parent.
-The parent's state updates dynamically, and the new message is displayed on the UI.

## Output
![Screenshot (314)](https://github.com/user-attachments/assets/ee10fe70-af3d-4623-afa7-cb30eb267441)
