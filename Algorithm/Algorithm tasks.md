# _**Algorithm Tasks**

### Task: design an algorith for each of the following tasks in both ( pesudo code and flowchart )

#### 1. reverse a string     
###### note: i is pointer

**pesudo**

1. start
2. declare word, z, len_word, len_z, pointer_word
3. input: word = input("input your world")
4. z = new list, len_word = length of word, len_z = length of z,     
   pointer_word = len_word -1
5. if len_z < len_word
6. add word[pointer_word] to z
7. pointer_word = pointer_word -1
8. return z
9. end

 **Flowchart**

![Reverse String](<reverse a string.png>)

**TestAlgorithm**
![Test Reverse Algorithm with two examples](<test reverse stering algorithm ex1-2.jpeg>)

 #### 2.search in list of student marks for the highest one
 ###### note: i is pointer
**pesudo**
1. start
2. declear num
3. enter num
4. declear marks, L=0, pointer_marks=0, len_marks= length of marks
5. is pointer_pointer_marks < num
6. enter the num to marks[pointer_marks]
7. pointer_marks = pointer_marks +1
8. pointer_marks = 0
9. if pointer_marks < len_marks
10. if L> Marks[pointer_marks]
11. set current L
12. pointer_marks= pointer_marks+1
13. set new L = marks[pointer_marks]
14. end 

**Flowchart**
![Search highest number](<search highest number.png>)

**TestAlgorithm**
![test search highest number with tow examples](<test search highest number algorithm ex1-2.jpeg>)

#### 3. Sort the students marks from highest to lowest    
###### note: first loop forn selest the number of loop, second loop foe com
**Pesudo""
1. start
2. declear num
3. enter num
4. declear marks, L=0, pointer_marks=0,index_loop= 0 size_marks= length of marks
5. is pointer_pointer_marks < num
6. enter the num to marks[pointer_marks]
7. pointer_marks = pointer_marks +1
8. pointer_marks = 0
9. if pointer_marks < size_marks-index_loop - 1
10. if marks[pointer_marks] < marks[pointer_marks+1]
11.mark_hold = marks[pointer_marks]
marks[pointer_marks] = marks[pointer_marks+1]
marks[pointer_marks+1] =hold

12. pointer_marks = Pointer_marks+1
13.pointer_marks = 0
index_loop= index_loop+1
14. index_loop < size_num -1
15. return marks
16.end
 

**Flowchart**
![Sort From Highest to lowest](<sort from higthest to lowest.png>)

**TestAlgorithm**
**Example 1**
![test sort numvers from hiest to lowest example 1](<test sort the number from highest to lowest ex1.jpeg>)
**Example 2**
![test sort numbers from hiest to lowest example 2 part one](<test sort the number from highest to lowest ex2.1.jpeg>)
![test sort numbers from hiest to lowest example 2 part two](<test sort the number from highest to lowest ex2.2.jpeg>)

#### 4.check if number is palindrome ( ex: 3443 is palindrome , 56 is not palindrome , 454 is palindrome )
**Pesudo""

1. start
2. declare num, ReverceNum, len_num, len_ReverceNum, pointer_num
3. input num 
4. ReverceNum = [ ]
len_num = length of num
len_ReverceNum = length of ReverceNum 
pointer_num= len_num-1

5. if len_ReverseNum < len_num
6. add num[pointer_num] to ReverceNum
7. pointer_num = pointer_num-1
8. pointer_num = 0
pointer_ReverceNum = 0
9. if num[pointer_num]= =ReverceNum[pointer_ReverceNum]
10. 
pointer_num = pointer_num+1
pointer_ReverceNum = pointer_ReverceNum +1

11.if pointer_num< len_num
12. the number is not palindrome
13.the number is palindrome
14. end

**Flowchart**
![check number is palindrome or not](<number is palindrome.png>)

**TestAlgorithm**
**Example 1**
![test check number is palindrome algorithm example 1](<test check number is palindrome algorithm Ex1.jpeg>)
**Example 2**
![test check number is palindrome algorithm example 2](<test check number is palindrome algorithm Ex2.jpeg>)