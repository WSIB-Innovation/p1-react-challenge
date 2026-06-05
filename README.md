This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules. On to the Challenge!

# React Coding Challenge

## Overview

This challenge is divided into two phases and is intended to evaluate your understanding of React fundamentals, component design, state management, and working with external APIs.

We are primarily evaluating **code quality** - namely readability, reusability, maintainability, and functionality.

---

## Phase 1: Parent & Child Components

Create a reusable React button component using a functional component structure.

### Requirements

* Create a reusable button component that can be rendered multiple times.
* Use a parent component to:

  * Pass props to each button.
  * Pass a function that allows each button to manage its own background colour.
* Render **two buttons** in total.
* Each button must have a unique initial background colour.
* Clicking a button should change **only that button's** background colour.
* The colour change implementation is up to you.

---

## Phase 2: Working with an API

You will be responsible for fetching data from the following API endpoint:

```text
https://jsonplaceholder.typicode.com/posts/1/comments
```

This endpoint returns JSON containing five comments.

Additional API documentation can be found here:

```text
https://jsonplaceholder.typicode.com/
```

### Requirements

Using the button component created in Phase 1:

* Label one button **"Fetch"**
* Label one button **"Hide"**

#### Fetch Button

When the **Fetch** button is clicked:

* Fetch data from the API endpoint above.
* Display the returned JSON data within the application.
* The button should continue to change colour when clicked.

#### Hide Button

When the **Hide** button is clicked:

* Hide the displayed JSON data.
* The button should continue to change colour when clicked.

---

## Evaluation Criteria

We are particularly interested in:

* React best practices
* API fetch logic
* Component reusability
* State management
* Clean and readable code
* Separation of concerns

Bonus points for:

* Thoughtful project structure
* Error handling for API requests
* Loading states
* Recommendations on further enhancements

Good luck!
