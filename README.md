## Aim: 
Study of dictionary in python.

## Theory:
Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and do not allow duplicates.   
You can retirive values from dictionaries using command print(dict["key"]).   
Dictionary takes the latest value given for key. It will not allow duplicates.   
You can change or add key:value in dictionary using dictionary["key"] = "value".   
You can display values using dictionary.values().   
dictionary.pop("key") removes the value from the dictionary.   
print(student.get(name, "student not found")) searches for that name in the dictionary named student.   

## Algorithm:
    A: Update Product Price
    1)Initialize the dictionary "product" with names as keys and prices as values.
    2)Display the "product" dictionary to show the "Original price".
    3)Update the value of a specific key using the syntax product["Book"] = "55 Rupees".
    4)Display the updated product dictionary.
    
    B: Search Student Marks
    1)Initialize the dictionary "student" with names and marks.
    2)Input a string from the user and store it in the variable name.
    3)Search for the name in the "student" dictionary using the student.get(name,"Student not found" command.
    4)Output the mark if the name exists; otherwise, return the default message "Student not found".
    
    C:User Login Validation
    1)Initialize the dictionary "users" with usernames as keys and passwords as values.
    2)Input data from the user for variables username and password.
    3)Validate by checking if users.get(username) matches the entered password.
    4)If they match, Display "Login successful".
       Else, Display "Invalid username or password".
       
    D:Find Highest Scorer
    1)Initialize the dictionary "student" with student names and their respective marks.
    2)Identify the key with the highest value using max(student, key=student.get) and store it in the variable topper.
    3)Access the score of the topper using the syntax student[topper].
    4)Display the name of the topper and their corresponding marks.

# Conclusion:
Hence dictionary was implemented in python and operations were done on them.
