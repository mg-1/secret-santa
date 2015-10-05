# secret-santa

As inspired by Brent Simmons:
http://inessential.com/2015/09/25/a_secret_santa_solution
which references: http://rubyquiz.com/quiz2.html

The challenge is to implement a Secret Santa selection script, but I'll do it in Javascript.

The script is fed a list of names as a text file, or as input into a text field. 

The format for these names is:

FIRST_NAME space FAMILY_NAME space <EMAIL_ADDRESS> newline

To keep things simple assume that people only have two names.

The script should then choose a Secret Santa for every name in the list. Obviously, a person cannot be their own Secret Santa. In addition, people in the same family may not be Santas for each other.
