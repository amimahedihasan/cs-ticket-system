# 🎟️ CS-Ticket-System

একটি আধুনিক এবং রেসপন্সিভ কাস্টমার সাপোর্ট টিকেট ম্যানেজমেন্ট সিস্টেম। এটি React এবং Tailwind CSS ব্যবহার করে তৈরি করা হয়েছে।

---

## 🔗 Project Links
- **Live Website:** [Click Here to View Live]()
- **GitHub Repository:** [View Source Code](https://github.com/amimahedihasan/cs-ticket-system.git)

---

## 📖 React Interview Q&A

### 1. What is JSX, and why is it used?
* **Definition:** JSX (JavaScript XML) is a syntax extension that allows writing HTML-like structures directly inside JavaScript code.
* **Why use it?**
    * **Readability:** It makes UI code easier to read and maintain by keeping structure and logic together.
    * **Dynamic Content:** It allows embedding JavaScript expressions using curly braces `{}`.

### 2. Difference between State and Props
* **State:** Data managed *inside* a component. It is mutable, meaning the component can update its own state to trigger a UI re-render.
* **Props:** Data passed *into* a component from a parent. It is read-only for the child component.

### 3. What is the `useState` hook?
* `useState` is a built-in React hook used to add dynamic state to functional components.
* **Mechanism:** It returns an array containing the current state value and a function to update it.
* **Initialization:** It accepts an initial value (e.g., `0`, `[]`, or `{}`) to define the state's starting condition.

### 4. How to share state between components?
* **Lifting State Up:** Moving state to a common parent and passing it down via props.
* **Context API:** A global way to share data across the component tree without prop-drilling.
* **State Management:** Using tools like **Redux** or **Zustand** for complex global state requirements in larger projects.

### 5. Event handling in React
* **Syntax:** Uses `camelCase` attributes like `onClick` or `onChange`.
* **Function Calls:** You must pass a function reference rather than a string.
* **Arguments:** To pass arguments, use an arrow function (e.g., `onClick={() => handleClick(args)}`) to prevent the function from executing immediately upon rendering.

---

## 👤 Author
**Md. Mahdei Hasan**
* GitHub: [amimahedihasan](https://github.com/amimahedihasan)
* Role: Frontend Developer

---
*Built with ❤️ using React, Tailwind CSS, and DaisyUI.*