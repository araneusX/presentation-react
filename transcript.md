
# Slide 1. 

Hi, everyone, lets talk about one JavaScript library for building user interfaces called React or React.js.

---

# Slide 2.

React is an open source JavaScript library for building user interfaces.
React is a small library. It is not exactly a "framework". React focuses on just building user interfaces and on doing that extremely well.  React  has no powerful out-of-the-box solutions, and the developers have to find other libraries they need on their own.

---

# Slide 3.

React was created by Jordan Walke, a software engineer at Facebook. Facebook released React in 2013. The React team at Facebook tests all improvements and new features that get introduced to React right there on facebook.com, which increases the trust in the library among the community. It’s rare to see big and serious bugs in React releases because they only get released after thorough production testing at Facebook. React also powers other heavily used web applications like Netflix, Twitter, Airbnb, and many more.

---

# Slide 4.

React is a declarative, component based library. With React we create interfaces from components. Reacts rendering system manages these components and keeps the application view in sync.

---

# Slide 5.

We describe user interfaces with React and tell it <b>what</b> we want. React translate our declarative descriptions (which we write in the React language) to actual user interfaces in the browser. React shares this simple declarative power with HTML itself, but with React we get to be declarative for HTML user interfaces that represent dynamic data, not just static data.

---

# Slide 6.

In React, we describe user interfaces using components that are reusable, composable, and stateful. We define small components and then put them together to form bigger ones. All components small or big are reusable, even across different projects.
Conceptually, components are like JavaScript functions. They accept arbitrary inputs (called “props”) and return React elements describing what should appear on the screen. Also React lets we define components as classes.

---

# Slide 7.

In addition to providing reusable React library code, React comes with two key features that add to its appeal for JavaScript developers. They are Virtual DOM and JSX.

---

# Slide 8.

When we tell React to render a tree of elements in the browser, it first generates a virtual representation of that tree and keeps it around in memory for later. Then it’ll proceed to perform the DOM operations that will make the tree show up in the browser.
When we tell React to update the tree of rendered  elements, it generates a new virtual representation, computes the resulting differences, and then updates the browser's displayed DOM efficiently. This allows the programmer to write code as if the entire page is rendered on each change, while the React only render subcomponents that actually change. This selective rendering provides a major performance boost. 

---

# Slide 9.

React support JSX. It is an extension to JavaScript that allows us to write function calls in an HTML-like syntax.
After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects. This means that you can use JSX inside of if-statements and loops, assign it to variables, accept it as arguments, and return it from functions.
React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

---

# Slide 10.

React has become the industry standard for building modern web applications. With React, you can build anything from simple marketing splash pages to full-fledged web applications on the scale of Facebook. It's flexible tool that is easy to learn and use.