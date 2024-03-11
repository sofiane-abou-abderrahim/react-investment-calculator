# React Essentials - Practice Project

## Apply Your Knowledge & Practice What You Learned

# Project Plan

## Build an "Investment Calculator" Web App

- Build, Configure & Combine Components
- Manage Application State
- Output List & Conditional Content

# Task

## Build an "Investment Calculator" Web App

- Use the starting project attached to the first lecture
- Add components for displaying a header, fetching user input & outputting the results table
- Fetch & store user input (i.e. the entered investment parameters)
- Derive investment results with help of the provided utility function (in the starting project)
- Display investment results in a HTML table (use `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`)
- Conditionally display an info message if an invalid duration (<1) was entered

# Steps

## 0. Setting up the Project

1.  Run "npm install"
2.  Run "npm run dev"

## 1. Module Introduction & A Challenge For You!

1. Create README.md

## 2. Adding a Header Component

1. Create Header Component
2. Import Header Component into App.jsx

## 3. Getting Started with a User Input Component

1. Create UserInput Component
2. Import UserInput Component into App.jsx

## 4. Handling Events & Using Two-Way-Binding

1. Get hold of the Value Entered by the User with UseState()
2. Reflect that Value Back into the Input Field with the value attribute

## 5. Lifting State Up

1. Lift the `userInput` State Up from the UserInput Component to the App Component
2. Pass `onChange` & `userInput` as props in UserInput Component to Get the Object from the State & use the `handleChange` function
3. Create the Results Component
4. Pass also the `userInput` as props in the Results Component
5. Output the Results Component

## 6. Computing Values & Properly Handling Number Values

1. Derive the Results Data in the Results Component
   1. Import & use the `calculateInvestmentResults` function from `util/investment.js`
   2. Compute Values based on the `input` state
2. Convert the `newValue` into a number

## 7. Outputting Results in a List & Deriving More Values

1. Output results data in a table dynamically as a list based on the `resultsData` array
2. Use `formatter.format()` to make numbers prettier
