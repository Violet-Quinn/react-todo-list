# React + Vite Todo List Application

This is a simple **Todo List** application built with **React** and **Vite**. It allows users to:

- **Add** new todo tasks  
- **Edit** existing tasks  
- **Delete** tasks  
- Persist tasks using **localStorage**, so they remain even after refreshing the page  

## Features

- Minimal and fast setup using **Vite** for development with Hot Module Replacement (HMR)  
- Functional React components with **hooks** (`useState` and `useEffect`)  
- Persistent storage with **localStorage**  
- Clean and maintainable code structure  

## Installation

Clone the repository:

```bash
git clone <your-repo-url>
cd <your-project-folder>
npm install
```

Start the development server:
```bash
npm run dev
```

Open your browser and navigate to the provided URL to see Todo List in action.

## Folder Structure
```bash
src/
├── components/
│   ├── TodoInput.jsx      # Component to add new todos
│   ├── TodoList.jsx       # Component to display all todos
│   └── TodoCard.jsx       # Single todo item with edit & delete
├── App.jsx
└── main.jsx
```

## Usage

1. Add a task: Type a task in the input field and press "Add".
2. Edit a task: Click the edit icon on a task, modify the text, and save it.
3. Delete a task: Click the delete icon on a task to remove it.

Persistence: All tasks are stored in localStorage, so they remain after refreshing the page.