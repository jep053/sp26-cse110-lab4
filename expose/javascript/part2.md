# Part 2

## Question 1
Answer: It will print 3, because i is declared with var, so even though it is a counter variable inside the for block, we can access it outside.

## Question 2
Answer: It will print 150, because discountedPrice is declared with var, and it will save the last price[i]*(1-discount) which is price[2]*0.5.

## Question 3
Answer: It will print 150, becasue Math.round(discountedPrice*100)/100, the discountedPrice is 150, due to Q2 reason, and Math.round(15000)/15000 = 150.

## Question 4
Answer: It will return [50, 100, 150]. We are saving each finalPrice in discount, so it will return like this.

## Question 5
Answer: It will return an error because i is declared with let, and it is inside the for block. We are trying to reach from outside of the for block and this will cause an error.

## Question 6
Answer: It will return an error because discountedPrice is declared with let, and it is inside the for block. We are trying to reach from outside of the for block and this will cause an error.

## Question 7
Answer: It will print 150, becasue Math.round(discountedPrice*100)/100, the discountedPrice is 150, due to Q2 reason, and Math.round(15000)/15000 = 150. Also, the finalPrice is declared not inside the for block so we can still reach it without an error.

## Question 8
Answer:  It will return [50, 100, 150]. We are saving each finalPrice in discount, so it will return like this. Also, even though it is declared with let, it is the local variable of function so reaching from the inside will have no error.

## Question 9
Answer: It will return an error because i is declared with let, and it is inside the for block. We are trying to reach from outside of the for block and this will cause an error.

## Question 10
Answer: It will print 3 because we are not changing the value.

## Question 11
Answer: The function returns [50, 100, 150]. Even though it is declared with const, push() only modifies the contents of the array, not the reference itself, so no error occurs.

## Question 12 
A: student.name
B: student['Grad Year']
C: student.greeting()
D: student['Favorite Teacher'].name
E: student.courseLoad[0]

## Question 13
A: '32', because when using the + operator, if one of the operands is a string, the other converts to a string and adds them
B: 1, because the - operator only works with numbers.
C: 3, because null is coverted to the number 0 when using arithmetic.
D: '3null', because when using the + operator, if one of the operands is a string, the other converts to a string and adds them
E: 4, because true is converted to the number 1 when used in arithmetic.
F: 0, because false is converted to 0, and null is also converted to 0.
G: '3undefined', because when using the + operator, if one of the operands is a string, the other converts to a string and adds them
H: NaN, it means it is not a number. - operator converts both operands to numbers, but undefined cannot be converted into a number.

## Question 14
A: true, because when comparing a string with a number, the string converts to a number.
B: false, comparing strings with the alphabetical order, so '2' > '1'.
C: true,  because when comparing a string with a number, the string converts to a number.
D: false, === compares two values without changing the data type. So, two different data types are false.
E: false, because ==, true is converted to 1
F: true, Boolean(x) where x != 0 is all true

## Question 15
The difference between == and === is == changes the datatypes and === don't. So, like 14 problem C and D, when using 2=='2' is true because string coverts to a number, but in D === doesn't change the datatype so it is false.
