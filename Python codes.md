- š Hi, Iām @konik06
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
konik06/konik06 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# question_1: how to sum the N number and print the average.
# first add a variable for input a number
num = int(input(" How many number to add:"))
# let first total number =0
total =0
# for loop where we input the numbers follow the first
# variable
for n in range(num):
  numbers = int(input("enter a number:"))# number of time it print
  total +=numbers # numbers of value sum with numbers

print(total) # total number will be print

avg = total / num #find the average of total sum of number .

print(avg) #print the average.


