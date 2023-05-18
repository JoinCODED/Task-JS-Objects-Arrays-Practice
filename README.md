# Task-JS-Objects-Arrays-Practice

Define the students array, where each object represents a student and contains the properties name and grades. Assign appropriate values to these properties. For example:
```
const students = [
  { name: 'John', grades: [{ numeric: 85, letter: 'B' }, { numeric: 90, letter: 'A-' }, { numeric: 92, letter: 'A' }] },
  { name: 'Jane', grades: [{ numeric: 78, letter: 'C+' }, { numeric: 88, letter: 'B+' }, { numeric: 95, letter: 'A' }] },
  // ... add more student objects
];
```
1. Define the calculateAverage function that takes an array of grade objects as a parameter. Within the function, calculate the average of the numeric grades and return the result. You can use the reduce method to sum up the numeric grades and divide it by the length of the grades array.

1. Define the findHighestAverage function that iterates through the students array. Within the loop, calculate the average grade for each student using the calculateAverage function. Keep track of the highest average grade and the corresponding student object. Finally, return an object representing the student with the highest average grade, containing the properties name and average.

1. Define the addGrade function that takes the student's name, numeric grade, and letter grade as parameters. Use the find method to locate the student object in the students array based on the provided name. If the student is found, add a new grade object with the provided numeric and letter grades to the student's grades array.

1. Define the removeLowestGrade function that takes the student's name as a parameter. Use the find method to locate the student object in the students array based on the provided name. If the student is found, use the reduce method on the grades array to find the lowest numeric grade. Then, use the indexOf method to find the index of the lowest grade object in the grades array and remove it using the splice method.

1. Define the getStudentGrades function that takes the student's name as a parameter. Use the find method to locate the student object in the students array based on the provided name. If the student is found, return the grades array of the student. Otherwise, return an empty array.

1. Define the updateStudentName function that takes the current name and new name of the student as parameters. Use the find method to locate the student object in the students array based on the current name. If the student is found, update the name property of the student object with the new name.

1. Test your code by calling the functions and printing the results. For example:
