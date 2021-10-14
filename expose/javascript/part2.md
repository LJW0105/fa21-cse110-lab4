## Part2 Answers
1. It will print i, because i is defined by var, which scope is the entire function
2. It will print discountedPrice, because discountedPrice is defined by var, which scope is the entire function
3. It will print finalPrice, because finalPrice is defined by var, which scope is the entire function
4. [50, 100, 150], because all the variables are defined by var, so they can be accessed within the whole function, and discounted contains all the finalPrice
5. error, because i is defined by let, which only exists in the for loop block, so it can't be access from outside the loop.
6. error, because discountedPrice is defined by let, which only exists in the for loop block, so it can't be access from outside the loop.
7. it will print the finalPrice, because it is defined in this function and outside the loop, so the scope is within the whole function.
8. [50, 100, 150],  because discounted is defined in this function and outside the loop, so the scope is within the whole function.
9. error, because i is defined by let, which only exists in the for loop block, so it can't be access from outside the loop.
10. It will print length, because the scope of it is the whole funtion and it hasn't been modified after declared.
11. It will return discounted, because it hasn't been reassigned. Also, the scope of discountedPrice is within each loop, so it will create new one for each loop.
12. - student.name
    - student['Grad Year']
    - student.greeting()
    - student['Favorite Teacher'].name
    - student.courseLoad[0]
13. - '32' because 2 converted to string '2'
    - 1 because '3' converted to integer 3
    - 3 because null is converted to 0
    - '3null' because null is converted to string
    - 4 because true is evaluated as 1
    - 0 because false and null are all mapped to 0
    - '3undefined' because undefined is mapped to string
    - NaN because it is not a number
14. - true because 2 is converted to int
    - false because they are strings and ascii of 1 < 2
    - true because '2' is mapped to int
    - false because === don't do type conversion
    - false because true is converted to 1
    - true because 2 is not 0 boolean(2)=true
15. == do type conversion, but === doesn't do type conversion
16. code
17. return [2, 4, 6] the function get each element in the array and send the element to the callback function and store it in the newArr
18. code
19. 1 4 3 2