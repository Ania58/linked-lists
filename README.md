# 🔗 Linked List in TypeScript

This project is a simple **Linked List implementation using TypeScript**, created as part of a step-by-step learning process. The list supports basic operations such as adding, inserting, removing elements, and printing the list content.

---

## 📚 What is a Linked List?

A **linked list** is a linear data structure where each element (called a "node") points to the next one. This implementation is a **singly linked list**, meaning each node points only to the next node, not backward.

---

## 🚀 Features

- ✅ Generic `LinkedList<T>` implementation (works with any data type)
- ✅ Add elements to the end of the list
- ✅ Insert elements at any valid position
- ✅ Remove elements by position
- ✅ Print all elements in the list
- ✅ Keep track of the list length

---

## 🛠 Technologies

- **TypeScript**
- Basic Node.js setup (for running and compiling TypeScript)

---

## 📂 Project Structure



```plaintext
linked-list/
├── linked-list.ts      # TypeScript source code
├── linked-list.js      # Compiled JavaScript output (from tsc)
├── tsconfig.json       # TypeScript compiler settings
└── README.md           # You're here!

```

## ⚙️ How to Run the Project

1. **Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

2. **Install TypeScript (if not already installed)**

```bash
npm install -g typescript
```
3. **Compile the code**
```bash
tsc
```

4. **Run the code**
```bash
node linked-list.js
```

## 📌 Example Output
```
Length: 3
10
5
-3
--- NOW REMOVING INDEX 1 ---
Length: 2
10
-3
--- NOW INSERTING AT INDEX 1 ---
Length: 3
10
100
-3
```