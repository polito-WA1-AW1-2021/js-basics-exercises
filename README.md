# JavaScript Exercises

## Improve my scores

Develop a small JS program to manage the scores of your exams that you got in you Bachelor degree. You should:
- Define an array with all your scores, in chronological order
  - For the time being, embed the scores directly in the source code
  - For the time being, ignore the course name, CFUs and date
  - For the time being, ignore the 30L
- Eliminate the two lowest-ranking scores
- Add two new scores, at the end, equal to the (rounded) average of the existing scores
-  Print both arrays

A possible solution: [`scores.js`](scores.js)

## My courses list

Develop a small JS program to manage a list of your courses.
- Define the names of your courses, as a comma-separated list
  - E.g.: "Web Applications I, Computer Architectures, Data Science and Database Technology Computer network technologies and services, Information systems security, Software engineering, System and device programming"
- Create an array containing the names, one name per array position.
  - Ensure that there are no extra spaces.
- Create a second array by computing the acronyms of the courses (the initial letters of the name)
  - E.g., Computer Architectures -> CA
  - Acronyms should be all-capital letters
- Print the resulting list of acronyms and full names
  - Extra: in alphabetical order of acronym

A possible solution: [`courses.js`](courses.js)
