1. 3 is printed. This is because we declared i using var, which has no block scope, so we can access it outside of the block it was declared in. The reason it is three is because we incremented i by 1 each each price, and there were 3. 
2. 150 is printed. This is because we declared discountedPrice using var, which has no block scope, so we can access it outside of the block it was declared in. The reason it is 150 is because the last time is was assigned was when the price was 300, which was multiplied with 0.5, therefore giving us the value of 150. 
3. 150 is printed. This is because we declared finalPrice as a var, right under the function signature, which means that it is accessible. The reason finalPrice has a value of 150 is because finalPrice was assigned the value of Math.round(150 * 100) / 100, which is equal to 150. 
4. This function will return [50, 100, 150]. This is because the discount we input was .5, which essentially divides each thing in prices by 2 and returns a list that contains those prices divided by 2. So from [100, 200, 300], we get [50, 100, 150]. 
5. The code causes an error because the variable i cannot be accessed out of the scope it was defined in, since it was defined using let. So we are trying to access a variable outside of its scope in line 12, which is why there is an error. 
6. The code causes an error because the variable discountedPrice cannot be accessed outside of the scope it was defined in, since it was defined using let. So we are trying to access a variable that is not defined in line 13, which is why there is an error. 
7. 150 is printed. This is because finalPrice is defined in the scope and the final value it was assigned was Math.round(150 * 100) / 100, which is 150. 
8. This function will return [50, 100, 150]. This is because discounted is a variable that is in the scope, so we can return it.discounted was pushed a finalPrice for each price that was in prices, except that it was half of its original value. So from [100, 200, 300], we get [50, 100, 150]. 
9. The code will cause an error because we are trying to access i, which is only able to accessed in the scope it was defined in since it was defined using let. So when we try to access i at line 11, we get an error. 
10. 3 is printed, because we defined length to be the length of prices, which is 3 since it held three numbers. 
11. This function will return [50, 100, 150]. This is because the discounted value can have additional values added to it since we aren't reassigning to something. As per usual, the prices have all been halved, so from [100, 200, 300], we return [50, 100, 150]. 
12. A) student.name 
    B) student['Grad Year'] 
    C) student.greeting() 
    D) student['Favorite Teacher'].name 
    E) student.courseLoad[0]
13.  
    A) '32'; Integers can map to their exact string representation, so it concatenates as a string to '32'
    B) 1; '3' is converted to a number. Then we get 3 - 2, which is equal to 1. 
    C) 3; null becomes 0. 0 + 3 = 3
    D) '3null'; null becomes 'null', so '3' + 'null' = '3null'
    E) 4; true becomes 1, so 1 + 3 = 4
    F) 0; false becomes 0 and null becomes 0, so 0 + 0 = 0.
    G) '3undefined'; undefined becomes 'undefined', so '3' + 'undefined' = '3undefined'
    H) NaN; undefined is NaN as a number, which is why the final output is NaN. 
14. 
    A) true; string '2' becomes a number, so 2 > 1 is true
    B) false; It compares the strings letter by letter. '2' is greater than '1', so '2' < '12' evaluates to false. 
    C) true; '2' becomes a number, so 2 == 2. 
    D) false; This checks for exact equality, but since 2 is a number and '2' is a string, they are not exactly equal. 
    E) false; true becomes 1, and 1 != 2, so we get false. 
    F) true; Boolean(2) evaluates to true, so true == true evaluates to true. 
15. == and === both test for equality, but === tests for strict equality, so there will not be an attempt to convert any types. For example true == 1 evaluates to true, but true === 1 evaluates to false, becaue we don't attempt to convert true to 1 for ===. 