#student-grade-generator

prompt the user to input student marks.  The marks should be (between 0  and 100)
' let marks = parseFloat(prompt("Enter the student's marks (between 0 and 100):")); '

Defination of paremeters of operation of the function to decide on what to award to each mark recorded
'let grade;
    if (marks > 79) {grade = 'A';
    } else if (marks >= 60) {grade = 'B';
    } else if (marks >= 50) {grade = 'C';
    } else if (marks >= 40) {grade = 'D';
    } else {grade = 'E';
    }'


Display the student grade according to marks input
'  alert(`The student's grade is: ${grade}`);
}'