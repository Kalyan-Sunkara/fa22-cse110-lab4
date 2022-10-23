1) At line 12 we will print the length of the array prices which is 3, since 'i' was defined with var it is still accessible outside the for loop block.
2) At line 13 we will print out the number 150, the discounted price of the last element in the prices array because the variable discountedPrice was defined by var and thus is accessible outside the loop. Since the last iteration of the loop updates discountedPrice with the discounted price of the last element of Prices, we get 150.
3) At line 14 we will print out the number 150, the discounted price of the last element in the prices array because the variable finalPrice was defined by var and thus is accessible outside the loop. Since the last iteration of the loop updates finalPrice with the discounted price of the last element of Prices, we get 150.
4) This function will return an array of the discounted prices of the prices given in the prices array. This is because it runs without errors and does indeed produce correctly discounted prices.
5) We receive a reference error at line 12, due to the variable 'i' only having scope within the for loop since it was defined by let. Thus accessing it outside of the for loop will cause a scope issue, since the variable does not exist outside the for loop block.
6) We receive a reference error at line 13, due to the variable 'discountedPricee' only having scope within the for loop since it was defined by let. Thus accessing it outside of the for loop will cause a scope issue, since the variable does not exist outside the for loop block.
7) At line 14 we will print out the number 150, the discounted price of the last element in the prices array because the variable finalPrice was defined by let at the global level and thus is accessible outside the loop. Since the last iteration of the loop updates finalPrice with the discounted price of the last element of Prices, we get 150.
8) This function will return an array of the discounted prices of the prices given in the prices array. This is because it runs without errors and does indeed produce correctly discounted prices. Furthermore, the array 'discounted' ,even though defined by let, is on defined at a global level, which allows us to access the variable anywhere in our code, thus being updated and run accordingly.
9) There is an error as we are trying to access the variable 'i' outside of the for loop. Since 'i' is defined by let keyword, then we cannot access it outside the block it is defined in.
10) Line 12 will print out the number 3, the length of the price array. This is because we defined on initialization that the variable would contain the value of the length of the price array.
11) The function will return [50,100,150] or the appropriate output array which applies a discount on the elements of the prices array. Even though we made the array a constant variable, this just means that the variable itself cannot be assigned to a different array, thus meaning we can still update the contents of the array. Therefore our code will update the discounted array appropriately and return [50,100,150]
12a) student.name
12b) student["Grad Year"]
12c) student.greeting()
12d) student['Favorite Teacher'].name
12e) student.courseLoad[0]
13a) "32" is returned since the integer 2 is converted to a string
13b) 1 is returned since the string '3' is converted to an integer
13c) 3 is returned since null is converted to 0
13d) "3null" is returned since null is converted to a string
13e) 4 is returned because true is converted to 1.
13f) 0 is returned because false is converted to 0, and null is converted to 0 aswell
13g) '3undefined' is returned because undefined is converted to a string
13h) undefined is returned because 3 is turned to an integer and therefore will result in undefined if subtracting by undefined.
14a) True because '2' is converted to an integer
14b) False
14c) True because we are only checking if the values are the same, not the type.
14d) False because '2' and 2 are not of the same type
14e) False because true converts to integer 1, and thus is not equal to 2.
14f) True because a non zero value when converted to a boolean results in true, thus true == true returns true
15) The === checks to see if the two elemnts are equal without converting the elements, thus taking into consideration of the data type of the element, == on the other hand converts the elements appropriately and then checks for equality, thus data type does not matter for ==
17) The result will be an array with each element multiplied by 2. I got to this answer because we are applying the callback parameter ,which is a function that doubles a number, on every element of the array and then pushing them into a new array which we return.
19) The output of the above code is the number 1,4,3,2 in that order. This is because 1 and 4 are console logged immediately, then 3 has a timeout of zero but is processed after the immediate console logs, and finally the number 2 is given a timeout of 1 second and thus appears last.
20) 