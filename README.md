# CampusID-Badge
🎓 Campus ID Badge

A simple Campus ID Badge generator built with HTML, CSS, and JavaScript.
It dynamically displays student details (Name, Department, Seed Value) and generates a Check Code based on the seed.

🚀 Features

Clean and minimal UI

Displays student information:

Name

Department

Seed value

Check Code (calculated using seed digits)

Responsive and styled with CSS

⚡ Working

Enter a student’s Name, Department, and Seed value in the script.

The script extracts digits from the seed and calculates a Check Code as:

Check Code = ( (digit1 + digit2) * 7 ) % 97


The values are dynamically inserted into the badge
