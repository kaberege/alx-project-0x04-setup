## StateCraft: Mastering State Management with Redux & Context API

# Project Overview
StateCraft is a hands-on React project that demonstrates different state management approaches by building a dynamic counter application. Starting with useState, then scaling up with the Context API, and finally integrating Redux, this project gives learners a clear path to mastering global state in React applications.

# Learning Objectives
Understand local vs. global state in React

Use React’s built-in useState for component-level state

Share state globally using the Context API

Implement Redux for scalable, predictable state management

Compare and evaluate different state management techniques

Apply the concept of a “single source of truth”

# Technologies Used
React 18+ with TypeScript

Next.js

Tailwind CSS

Redux Toolkit & react-redux

**Node.js v14+` and npm/yarn

# Project Structure
alx-project-0x04  # useState version
alx-project-0x05  # Context API version
alx-project-0x06  # Redux version

├── pages/
│   └── counter-app.tsx       # Main counter page
├── context/CountContext.tsx  # (Context API only)
├── store/store.ts            # (Redux only)
├── components/
│   ├── layouts/Header.tsx    # Header showing global count
│   └── common/Button.tsx     # Reusable button component


# Best Practices Followed
Typed components with TypeScript

State immutability and separation of concerns

Modular file organization for scalability

Redux best practices via Redux Toolkit

Custom hooks for cleaner context consumption