# React Introduction

## What is React?

React is a popular **JavaScript library for building user interfaces (UI)**, especially for **single-page applications (SPAs)** where content updates dynamically without reloading the page. It allows developers to build **reusable UI components**, making development faster, more organized, and easier to maintain.

React focuses only on the **view layer** of an application. It efficiently updates the UI using a concept called the **Virtual DOM**, which improves performance by updating only the necessary parts of the page instead of reloading the entire page.

React is widely used in modern web development to build interactive applications such as dashboards, social media platforms, and e-commerce websites.

---

## Library vs Framework

| Aspect | Library | Framework |
|------|------|------|
| Definition | A collection of functions used when needed | A full structure that dictates how an application should be built |
| Control | Developer controls the flow | Framework controls the flow |
| Flexibility | Highly flexible | More structured |
| Example | React | Angular, Django |

React is considered a **library**, not a framework, because it focuses mainly on the **UI layer**.

---

## React Revolution

React changed frontend development by introducing **component-based architecture** and efficient UI updates.

### Before React
- Heavy manual DOM manipulation  
- Hard-to-maintain large codebases  
- Performance issues during frequent UI updates  

### React Innovations

1. **Component-Based Development**  
   Applications are divided into small reusable components.

2. **Virtual DOM**  
   React compares the virtual DOM with the real DOM and updates only the changed elements.

3. **Declarative UI**  
   Developers describe what the UI should look like, and React updates it automatically.

4. **Improved Performance**  
   Efficient rendering minimizes unnecessary updates.

---

## Founder and Release Date

React was created by **Jordan Walke**, a software engineer at **Facebook (Meta)**.

- **Initial Release:** May 2013  
- **Developed by:** Facebook  
- **Purpose:** Improve performance of dynamic user interfaces.

---

## Key Features of React

1. **Component-Based Architecture**  
   UI is divided into reusable components.

2. **Virtual DOM**  
   Improves performance by updating only necessary parts of the page.

3. **JSX (JavaScript XML)**  
   Allows writing HTML-like syntax inside JavaScript.

4. **One-Way Data Binding**  
   Data flows in a single direction.

5. **Reusable Components**  
   Components can be reused across different parts of the application.

6. **Strong Community Support**  
   Large ecosystem of libraries and tools.

7. **React Hooks**  
   Enables state and lifecycle features in functional components.

---

## Starting a React Project Using Vite

Vite is a modern frontend build tool that provides **faster development and instant server start** compared to traditional tools like Create React App.

---

### 1. Create a React Project with Vite

Run the following command to create a new Vite project:

```bash
npm create vite@latest my-app
```

You will be prompted to choose options:
Project name → my-app
Framework → React
Variant → JavaScript or TypeScript

### 2. Navigate to the Project Folder

```bash
cd my-app
```
### 3. Install Dependencies

```bash
npm install
```

### 4. Start the Development Server

```bash
npm run dev
```
The application will run at:

```bash
http://localhost:5173
```

## Basic Vite + React File Structure

```bash
my-app
│
├── node_modules
├── public
│   └── vite.svg
│
├── src
│   ├── assets
│   ├── App.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Important Files

* main.jsx – Entry point of the React     application

* App.jsx – Main React component

* index.html – Root HTML file

* vite.config.js – Vite configuration file

* package.json – Contains project dependencies and scripts


## Advantages of Using Vite

* Faster startup time
* Instant hot module replacement (HMR)
* Optimized production build
* Modern ES module support


## Conclusion

Using Vite with React makes development faster and more efficient. It provides instant server startup, fast hot reloading, and optimized builds, making it a popular choice for modern React development.