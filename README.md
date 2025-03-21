# Challenge 4 (Phase 1) - Batch 3

---

# Challenge 1

## Simple Book Management Application

### **Description:**

Create a simple book management application using TypeScript. This application should allow users to:

1. Create a type for book where each book has a title, author, and publication year
2. Create an array to store books
3. Implement a function named `addBook` to add new books to the collection
4. Implement a function named `listBooks` to display all stored books
5. Implement a function named `searchBook` to find books by title (should be an optional parameter)
6. All functions must return void

### **Example Input:**

```typescript
// Adding some books
addBook('The Great Gatsby', 'F. Scott Fitzgerald', 1925);
addBook('1984', 'George Orwell', 1949);

// Displaying all books
listBooks();

// Searching for a book by title
searchBook('1984');
```

### **Expected Output:**

```
> Book added: "The Great Gatsby" by F. Scott Fitzgerald (1925)
> Book added: "1984" by George Orwell (1949)
> All Books:
> - The Great Gatsby by F. Scott Fitzgerald (1925)
> - 1984 by George Orwell (1949)
> Search Results for "1984":
> - 1984 by George Orwell (1949)
```

---

# Challenge 2

## Simple Calculator Application with Various Arithmetic Operations

### **Description:**

Create a simple calculator application that supports various arithmetic operations such as addition, subtraction, multiplication, and division. This application should allow users to:

1. Define a type for arithmetic operations (addition, subtraction, multiplication, division)
2. Create a type for base input, named `BaseInput`
3. Create a type for numbers input, named `NumbersInput`
4. Create an intersection type combining `BaseInput` and `NumbersInput`
5. Implement a function to perform arithmetic operations that:
   - Uses parameter destructuring
   - Checks if the input is not empty
   - Performs addition, subtraction, multiplication, and division operations
   - Returns the calculated result

### **Example Input:**

```typescript
// Addition
const additionResult = calculate({
  operation: 'add',
  numbers: [1, 2, 3],
});
console.log(`Addition: 1 + 2 + 3 = ${additionResult}`);

// Subtraction
const subtractionResult = calculate({
  operation: 'subtract',
  numbers: [10, 2, 3],
});
console.log(`Subtraction: 10 - 2 - 3 = ${subtractionResult}`);

// Multiplication
const multiplicationResult = calculate({
  operation: 'multiply',
  numbers: [2, 3, 4],
});
console.log(`Multiplication: 2 * 3 * 4 = ${multiplicationResult}`);

// Division
const divisionResult = calculate({
  operation: 'divide',
  numbers: [20, 2, 2],
});
console.log(`Division: 20 / 2 / 2 = ${divisionResult}`);
```

### **Expected Output:**

```
Addition: 1 + 2 + 3 = 6
Subtraction: 10 - 2 - 3 = 5
Multiplication: 2 * 3 * 4 = 24
Division: 20 / 2 / 2 = 5
```

---

# How to Run the Test

### 1. Install Dependencies

Run the following command to install dependencies:

```
npm install
```

### 2. Run Tests

Run the tests using the following command:

```
npm run test
```

---

# Evaluation System

The evaluation for this challenge is based on the following four criteria:

### 1. Requirement Fulfillment & Correctness

### 2. Javascript Usage

### 3. Problem Solving Approach

### 4. Code Clarity

---

# How to Upload your Challange

Check this module: [click this](https://orchid-clematis-3e4.notion.site/Panduan-Penggunaan-Git-Untuk-Upload-Assignment-e2d80a19b3684f5d8f1a4209dcf85445?pvs=73)

---

## 🎉 Embrace the challenge and turn your tasks into a fun adventure—each step brings you closer to your goals! You've got this! 🚀 Remember, every small victory is a reason to celebrate! 🎈
