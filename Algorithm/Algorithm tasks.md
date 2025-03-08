# _**Algorithm Tasks**

### Task: design an algorith for each of the following tasks in both ( pesudo code and flowchart )

#### 1. reverse a string     
###### note: i is pointer

**pesudo**

1. input: string = input("input your world")
2. z = new list
3. FOR i FROM LENGTH(string) - 1 TO 0
4. add string[i] to z list 
5. end for
6. return z

 **Flowchart**

![Reverse_Straing](C:\Users\HP\Desktop\Full-Stack .net cohort\Course Documentaion\Algorithm\algorithm tasks-reverse a string.png)

 #### 2.search in list of student marks for the highest one
 ###### note: i is pointer
**pesudo**
1. input: marks 
2. L=0
3. for i in marks
4. if i>L
5. set new L = i
6. end for
7. return L

**Flowchart**

![Search Highest Number](C:\Users\HP\Desktop\Full-Stack .net cohort\Course Documentaion\Algorithm\algorithm-tasks-search-highest-number.png)


#### 3. Sort the students marks from highest to lowest    
###### note: first loop forn selest the number of loop, second loop foe com
**Pesudo""
1. input : list of marks
2. len_marks is length of marks list
3. for i from 0 to len_marks -1
4. fOR j FROM 0 TO len_marks-i-2
5. if IF marks[j] < marks[j+1] THEN
6. SWAP marks[j] WITH marks[j+1]
7. end for 
8. end for 
9. return marks

**Flowchart**
![Sort_Student_marks](C:\Users\HP\Desktop\Full-Stack .net cohort\Course Documentaion\Algorithm\algorithm tasks-sort from higthest to lowest.png)

#### 4.check if number is palindrome ( ex: 3443 is palindrome , 56 is not palindrome , 454 is palindrome )
**Pesudo""

1. input number
2. originalNum = number
3. reversedNum = new list
4. FOR i FROM LENGTH(number) - 1 TO 0
5. add number[i] to reversedNum list 
6. end for
7. if originalNum ==reversedNum
8. return palindrome
9. else return  not palindrome

**Flowchart**

![Numer_Palindrome](C:\Users\HP\Desktop\Full-Stack .net cohort\Course Documentaion\Algorithm\algorithm tasks-number is palindrome.png)