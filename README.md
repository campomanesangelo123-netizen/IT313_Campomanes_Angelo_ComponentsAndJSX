# IT313 LastName FirstName Components and JSX

## Student Roster Card Renderer

This project is a React Native Expo application that demonstrates React components and JSX.

The application displays a student roster using reusable StudentCard components. Each card shows the student's name, course, and number of units. The "Full Load" label is displayed only when the student is marked as a full-load student.

## Component Structure

### StudentRoster

The StudentRoster component contains the student data and renders the list of students using the map() function.

It also displays the total number of students and includes a button that reverses the roster.

### StudentCard

The StudentCard component is a reusable functional component.

It receives these props:

- name
- course
- units
- isFullLoad

The props are destructured in the function parameter.

## JSX Features Used

- JSX expressions
- Conditional rendering
- Props
- Props destructuring
- Array map()
- Stable keys using student.id
- Computed student count using students.length

## Running the Project

Install the project dependencies:

npx expo install

Start the Expo development server:

npx expo start

The application can be opened in a web browser, Expo Go, or an emulator.

## Key Experiment

The project temporarily uses the array index as a key to demonstrate the difference between an index key and a stable student ID key.

After testing the roster reversal, the project restores student.id as the key.
