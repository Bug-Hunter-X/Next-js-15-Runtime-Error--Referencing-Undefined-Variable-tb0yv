# Next.js 15 Runtime Error: Referencing Undefined Variable

This repository demonstrates a common runtime error in Next.js 15 applications caused by referencing an undefined variable within a page component.  The error occurs because the variable `undefinedVariable` is used in `pages/about.js` without being declared or assigned a value.

## Bug
The `pages/about.js` file attempts to access a variable that hasn't been declared, resulting in a runtime error when the page is rendered. This is a common mistake, particularly when working with complex applications or when variables aren't properly scoped.

## Solution
The solution involves correctly declaring and assigning a value to the `undefinedVariable` before referencing it.  The provided solution ensures that `undefinedVariable` is defined and prevents the runtime error.