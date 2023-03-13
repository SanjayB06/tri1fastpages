---
toc: true
layout: post
description: 39 Question MC
categories: [markdown]
title: 39 Questions Test Corrections - Evan Corrections
---
#  Questions Test Corrections
## This is my score, 32/39
![image](https://user-images.githubusercontent.com/111528360/224601944-da55e33b-61b4-41bb-a881-6e0f442c1e3d.png)
## 1).
![image](https://user-images.githubusercontent.com/111528360/213965497-7bba8400-248b-4b7a-9229-0b71856712b1.png)
![image](https://user-images.githubusercontent.com/111528360/213965505-2f95d743-ef36-4251-93a4-8fefb8c15d27.png)
When the initial value of choice is greater than or equal to 5 and also less than or equal to 10, the first two if tests fail in both code segments, causing "yellow" to be printed. Therefore, the two code segments produce the same output when choice has an initial value that is greater than or equal to 5 and also less than or equal to 10.
When choice is greater than 10, code segment A will print "blue" and the else statements are not executed. Code segment B will print "blue" but will then execute the next if statement and print "yellow", thereby giving different output for initial values that are greater than 10.
The Videos given to us are very helpful as they are given from the AP website itself so not only does it prep us for this class but for the Exam as well. It provides three different videos allowing for the mastery of variable choices.
## 2).
![image](https://user-images.githubusercontent.com/111528360/213965559-0caca3b0-679f-4120-b75a-d1b783db748d.png)
![image](https://user-images.githubusercontent.com/111528360/213965567-556181c2-48c2-4d23-b853-573ad0b18700.png)
This decleration that I chose is incorrect as the two code segments print different values for grades 80 and above. If i input 84% then Segment 1 will give me 3.0 and Segment 2 will give me 4.0
Code segment I uses else statements, points is only ever incremented once. Because code segment II does not use else statements, it is possible for multiple conditions to be true, causing points to be incremented multiple times. For grades lower than 70, both code segments print 0.0. For grades from 70 to 79, both code segments print 2.0. For grades from 80 to 89, code segment I prints 3.0 and code segment II prints 5.0. For grades 90 or above, code segment I prints 4.0 and code segment II prints 9.0.
The Videos given to us are very helpful as they are given from the AP website itself so not only does it prep us for this class but for the Exam as well. It provides three different videos allowing for the mastery of reading code.
## 3).
![image](https://user-images.githubusercontent.com/111528360/213965652-a1475994-064b-4041-9aa1-25526243a30d.png)
![image](https://user-images.githubusercontent.com/111528360/213965675-6eec0fd3-49d0-44a5-9272-034f3e6aaeee.png)
Code segment III does not produce the same output as the original code segment. It creates a local boolean variable and assigns it the result of x % 2 == 0, but when using it in the if statement, the wrong branch is taken so that "YES" is printed for even integers and "NO" is printed for odd integers.
The original code segment prints "YES" for odd integers and "NO" for even integers. Code segment I produces the same output as the original code segment because the result of evaluating the expression x % 2 has only two possible values: 0 if x is even and 1 if x is odd. Code segment II produces the same output as the original code segment because the second else clause that prints "NONE" is never reached. Code segment III does not produce the same output as the original code segment. It creates a local boolean variable and assigns it the result of x % 2 == 0, but when using it in the if statement, the wrong branch is taken so that "YES" is printed for even integers and "NO" is printed for odd integers.
By refering to the two different videos mentioned in the related videos this can intensely prep me for problem solving and seeing problems within code.
## 4).
![image](https://user-images.githubusercontent.com/111528360/213965708-c38dbe41-9de2-439c-9213-69c756dd42fc.png)
I had chosen E, The opposite of !(a != b) is just (a != b). When you apply De Morgan’s Law the logic operator and (&&) becomes an or (||) and vice versa. The opposite of (b > 7) is (b <= 7).
The correct answer B, De Morgan’s Law states that !(p && q) is equivalent to !p || !q. By applying De Morgan’s Law to this expression, we negate the first expression !(!(a !=b)) and the second expression !(b >7) to form !(!(a != b)) || !(b > 7). In the first expression the two consecutive not operators (!) cancel each other out giving us (a != b). In the second expression, the opposite of > is <= giving us (b <= 7). The equivalent expression is (a != b) || (b <= 7).
This time, there was a question that was refrenced in the review portion, I could use all of these tools to boost my learning and if 2 videos and eight other practice problem wont do the job then researching and finding more practice problems, watching youtube videos, and etc.
## 5).
![image](https://user-images.githubusercontent.com/111528360/213965736-05a00860-977b-4041-9395-dccaf7191277.png)
In this case, the method will return true since all is assigned the value "darkroomcartoonarticulate" which contains "art". This is the expected return value since “art” is in both "cartoon" and “articulate”.
In this case, the method should return false since the word “art” is not found in “rattrap”, “similar”, or “today”. When the method concatenates all three words together, all is assigned the value “rattrapsimilartoday”. The “ar” in “similar” gets concatenated with the “t” in “today”, resulting in the letter combinations for “art” to be in all, causing the method to incorrectly return true.
## 6).
![image](https://user-images.githubusercontent.com/111528360/213965856-c35d4e23-e27b-4c97-b13a-e144b97d997f.png)
This would result from incrementing counter when "a" is followed by "b", even if there is a space between them. This occurs two times.
 The expression str.substring(i, i + 1).equals("a") will evaluate to true if str contains the string "a" at position i. The expression !str.substring(i + 1, i + 2) will evaluate to true if str does not contain the string "b" at position i + 1. The variable counter is incremented when both of those expressions evaluate to true or, in other words, whenever "a" is not immediately followed by "b". This occurs five times in the given string: "a ", "ac", "at", "at", and "a ".
## 7).
![image](https://user-images.githubusercontent.com/111528360/213966055-c1e803ff-f347-4046-9bf6-e08306d90327.png)
The given code segment prints 1357, while this code segment prints 13579.
The given code segment starts when k is 1 and prints every other value as long as k is less than or equal to 7. This code segment starts when k is 1 and prints every other value as long as k is less than or equal to 8. Both code segments print 1357.
This time, there was a question that was refrenced in the review portion, I could use all of these tools to boost my learning and if 2 videos and eight other practice problem wont do the job then researching and finding more practice problems, watching youtube videos, and etc.
