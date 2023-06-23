#  Student examination information management system
💡Requirement analysis 

1.1 Analysis of basic functional requirements

Student achievement management system, need to achieve find, add, delete, sort and other functions, so as to achieve the output of student information about the function.

The student performance management system needs to have a student information, management system category. 

The student information category includes the student's name, student number, class number, grades, gender, etc.

The password, name grades can be added, deleted and modified, but this can only be done in administrator mode. 

Within this class there are statistics on class averages and the number of failures, the ability to add, delete, sort and other student information within the class and perform input and output modes such as search. There is also a file read option, exit, continue input, and the ability to input around 100,000. 

1.2 Analysis of personalised functional requirements       

In the student information management system, I have added a help screen and login/logout settings.

The management system class also introduces the virtual inheritance function virtual, which allows for the selection of different user categories. 

In summary, the functions I can implement are: 

1: find student information, including name, class, number, gender and marks 

2: modify student information, including adding and deleting information, etc. 

3: Sorting grades, single subject grades, total and average grades

4: Display student information as required

5: Input information about a student and output specific information about him 

6: Storage of student information

7: Help and logout screens

💡Test results

Selecting Administrator mode brings up the Find, Sort, Change, Delete, Add, Logout and Help functions.

 ![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/30f28b78-8dfc-4135-b9c8-1c0ecaca0b22)

A similar function appears when you select Administrator Mode #2.

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/af30dd2a-a636-419a-9ace-c984a79097fb)

When in guest mode, there are only three functions.

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/4b0ab75b-0b6a-4eae-83e4-c844d5f5c9ab)

💡Demonstration of specific features

Find function:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/157ce338-cf52-42e1-92d1-88c3d75e57c2)

Sorting function:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/9f62a8b3-f77e-418d-bb69-1ac85aba959f)

Modified functions:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/523493ff-b3b5-4100-87ca-d0ff99cebc6f)

Delete function:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/f1f7c241-9862-4ae8-9d31-e7bd95fc5eeb)

Added features:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/ee528fa7-73e5-49e1-a58f-ab23f2c4de3e)

Storage function:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/00cacd59-3dd3-48a5-bab8-8e27518ef112)

Help screen:

![image](https://github.com/Frannie1020/Student-examination-information-management-system/assets/137517674/f16d04a4-e14b-436e-add6-620346ff165c)

💡Thoughts

1, in the design of the function class, the use of the loop structure can be more simple, in fact, the conditional judgment statement can be handled, do not need to use if ... else ... statement to write, can increase the efficiency of the algorithm.

2、Learned to use object-oriented programming methods, learned the introduction of friend functions, private and public members, and also learned to encapsulate the principle of inheritance.

3、When using virtual inheritance, learn to separate the permissions of different users.

4、When writing to a file again, write the file in advance and carry out the necessary checks.

5、When writing a program, it is more important to check the content after writing a paragraph to avoid frequent errors.

