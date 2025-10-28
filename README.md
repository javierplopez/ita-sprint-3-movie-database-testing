# 📑 IT Academy - Sprint 3 - Movie Database Testing

## Introduction

A company in the audiovisual sector has asked us for a web application that will allow their employees to quickly find movies from a large database they have, since the process is currently done manually.

The goal is to develop the necessary logic to achieve effective data handling through array method exercises and testing.

**Array Methods Used:** `map()`, `filter()`, `reduce()`, `sort()`, `slice()`, `includes()` + Regular Expressions and Spread Operator for advanced data manipulation.

---

## 📋 Exercises Overview

1. **Get all directors** - Extract array of movie directors
2. **Filter by director** - Get movies from specific director
3. **Calculate director average** - Average score of director's movies
4. **Alphabetical order** - Sort movie titles alphabetically
5. **Order by year** - Sort movies by year and title
6. **Category average** - Calculate average score by genre
7. **Duration converter** - Convert duration to minutes
8. **Best film of year** - Find highest rated movie per year

---

## 🎯 Project Structure

```
├── src/
│   ├── films.js          # Main exercise functions
│   └── data.js           # Movie database
├── tests/
│   └── films.spec.js     # Test specifications
├── test-results.html     # Generated test results
└── README.md
```

---

## 📥 Setup & Usage

Clone the repository and open the project in your browser or a local development server:

```bash
git clone https://github.com/javierplopez/ita-sprint-3-movie-database-testing.git
cd ita-sprint-3-movie-database-testing
```

---

## 🛠️ Installation

Install the project dependencies:

```bash
npm install
```

---

## 💥 Tests

Run the tests in watch mode:

```bash
npm run test:watch
```

And last, open the generated `test-results.html` file with the "Live Server" VSCode extension to see test results.