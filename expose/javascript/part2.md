part2-question1: 
    print 3 because i is a var, so can be used outside for scope, and in the for loop, it increments until reaches 3 that exit the for loop.

part2-question2:
     print 150, because the very last time it was when i=2 with 300*0.5 = 150.

part2-question3: 
    print 150, because the very last time it was when discountedPrice is 150.

part2-question4: 
    it will return an array [50,100,150] because this valid function will return half of the original prices array.

part2-question5: 
    code will return error because i is only defined in the for loop, here it's outside i's scope

part2-question6: 
    error, because discountedPrice is only defined in the for loop, here it's outside the scope

part2-question7: 
    it will print 150, because the very last time it was when discountedPrice is 150.

part2-question8: 
    it will return an array [50,100,150] for same reason as in 13 and 4 that return half of the original prices array.

part2-question9: 
    code will return error because i is only defined in the for loop, here it's outside i's scope

part2-question10: 
    code will return 3 since it's constant with length of 3 of the array

part2-question11: 
    it will print an array [50,100,150] because this valid function will return half of the original prices array.

part2-question12: 
                a) student.name
                b) student['Grad Year']
                c) student.greeting() 
                d) student['Favorite Teacher'].name 
                e) student.courseLoad[0]

part2-question13:
                a) 32, when 3 is a string, so 2 is converted to a string and then contatenate.
                b) 1, since it's '-', so string 3 is converted to number 3 and performed arithmetic calculation.
                c) 3, null is treated as a number 0
                d) 3null, null is converted to string
                e) 4, true is converted to 1
                f) 0, both false and null are 0 in number
                g) 3undefined, undefined is now a string
                h) NaN, undefined can't be converted to a number, so arithmetic will cause Not a Number.

part2-question14:
                a) true, string 2 will be converted to number 2
                b) false, for string comparison, 2 is bigger than 1
                c) true, '2' will be converted to number 2.
                d) false, since they're different type
                e) false, true is converted to 1
                f) false, they're different types.

part2-question15:
    the diference is '===' is a strict equality check that when (null === undefined) will return false since these values are different, because each of them is a different type.
    while '==' is a non-strict check, it will checks for equality after performing any necessary type conversions, and will return true when (null == undefined).

part2-question17: 
    it will display array [2,4,6], when iterating through array[1,2,3] in modifyArray, and it calls back doSomething function for each element, and inside doSomething function, elements are doubled in array and pushed into new array and returns.

part2-question19:
    1, 4, 3, 2
