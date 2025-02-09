# Next.js 15 App Directory Bugs

This repository demonstrates some uncommon bugs that can occur in Next.js 15's `app` directory, along with their solutions.  These bugs primarily stem from the new features introduced in the `app` directory (React Server Components, streaming, data fetching) and how they interact with third-party libraries or custom code.

## Bug 1: Third-Party Library Incompatibility
The `bug.js` file showcases a hypothetical scenario where a third-party library is not compatible with the new rendering model, leading to unpredictable behavior or errors. 

## Bug 2: Improper Async/Await Handling
The `bug.js` file also illustrates a common problem of incorrect usage of `async/await` within `async` components, causing potential race conditions.  The solution uses proper error handling and data management techniques. 

## Bug 3: Loading State and Error Boundary Issues
The `bug.js` demonstrates issues caused by missing error boundaries or incorrect handling of loading states within the component structure.