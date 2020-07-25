# Template-Engine
Generates a web page that displays basic team information.

# On he command line, enter node and the file name.

douglaslivingston@Douglass-MBP-2 Template-Engine % node app.js

# The first line of output.

Let's make a great team.

# It first asks how many people will be on the team.

? How many members are on your team? 3

# Each employee will be queried  about name, id, and email and title.

? What is employee (1)'s name? Bob Smith

? What is employee (1)'s id? 12345

? What is the employee (1)'s Email? someone@email.com

? What is the employee (1)'s title? (Use arrow keys)
❯ Manager 
# If the employee is the manager, then office number is asked for.

? What is the Manager's office number? A1


# Second employee questions
? What is employee (2)'s name? Sally Jones

? What is the employee (2)'s title? 
  Manager 
❯ Engineer 
  Intern 
# If the employee is an engineer, then their Github address is asked for.

? What is the Engineer's gitHub? sj8545

? What is employee (3)'s name? Tommy T


? What is the employee (3)'s title? 
  Manager 
  Engineer 
❯ Intern 

# If the employee is an intern, then their school is asked for.
? Where does this Intern go to school? State University





