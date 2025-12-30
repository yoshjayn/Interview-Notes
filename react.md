
#### ⚛️ React Fundamentals
1. [What is React?](#q1-what-is-react)  
2. [What is a Single Page Application (SPA)?](#q2-what-is-a-single-page-application-spa)  
3. [What are components in React and how are they useful?](#q3-what-are-components-in-react-and-how-are-they-useful)  
4. [What is JSX and why is it used in React?](#q4-what-is-jsx-and-why-is-it-used-in-react)  
5. [What are props and state? (Difference)](#q5-what-are-props-and-state-difference)  
---

## Part 1: Read-Aloud Interview Questions

### Q1: What is React?
- **JavaScript library** used to build **fast, scalable user interfaces**
- Primarily used for **single-page applications**
- Maintained by **Facebook (Meta)** and focuses on the **View layer of MVC**
- Follows **component-based architecture** for **reusability and separation of concerns**
- Uses **Virtual DOM** with **efficient diffing** for optimized **performance**
- Implements **declarative UI** and **unidirectional data flow** for **predictable state management**
---

### Q2: What is a Single Page Application (SPA)?
- Web application that loads a **single HTML page once**
- UI updates happen via **JavaScript without full page reload**
- Uses **client-side rendering** and **asynchronous API calls**
- Enables **smooth navigation** and **better user experience**
- Reduces **server load** and provides **app-like behavior**

Initial Load → index.html
↓
JavaScript Bundle
↓
Component Rendering
↓
API Calls + UI Updates


---

### Q3: What are components in React and how are they useful?
- **Independent and reusable UI building blocks**
- Encapsulate **logic, state, and presentation** in a single unit
- Support **modular and scalable application architecture**
- Can be **nested, reused, and composed**
- Improve **code readability, testing, and maintainability**

Root Component
↓
Parent Component
↓
Child Components



### Q4: What is JSX and why is it used in React?
- **JSX (JavaScript XML)** allows writing **HTML-like syntax inside JavaScript**
- Improves **readability and maintainability** of UI code
- Transpiled by **Babel** into standard JavaScript
- Encourages **declarative UI development**
- Enables **compile-time error checking**

JSX Syntax
↓ (Babel)
JavaScript Code
↓
Virtual DOM
↓
Real DOM

---

### Q5: What are props and state? (Difference)
- **Props** are **read-only data** passed from **parent to child components**
- Props support **unidirectional data flow** and **component reusability**
- **State** represents **mutable internal data** managed within a component
- State changes trigger **re-rendering** of the UI
- Props are **externally controlled**, while state is **internally managed**




Parent Component
↓ (Props)
Child Component
↓
Internal State
