# 3u-selection-quiz

Read the instructions carefully. **Do not include prompts in your input**.

```
word = input()
```

instead of

```
word = input("Enter a word: ")
```

---

Create a file called **selection.py** and upload it to this repository. In that file, write a program that asks the user for their pdsb email which will end in @pdsb.net. Your program will determine if the user is a teacher, grade 9 student, grade 10 student, grade 11 student or grade 12 student.

Their user id is everything before the @pdsb.net.

If their user id starts with p, then they are a teacher.

If their user id is 6 DIGITS long and starts with 5 - 9 then they are in grade 9.

If their user id is 6 DIGITS long and starts with 1 - 4 then they are in grade 10.

If their user id is 5 DIGITS long and starts with 5 - 9 then they are in grade 11.

If their user id is 5 DIGITS long and starts with 1 - 4 then they are in grade 12.

Otherwise they are not in pdsb.

**Sample Input 1**
```
999999@pdsb.net
```

**Sample Ouput 1**
```
grade 9
```

**Sample Input 2**
```
123456@pdsb.net
```

**Sample Ouput 2**
```
grade 12
```

**Sample Input 3**
```
p0123459@pdsb.net
```

**Sample Ouput 3**
```
teacher
```

**Sample Input 4**
```
12345b@pdsb.net
```

**Sample Ouput 4**
```
not in pdsb
```

**Sample Input 5**
```
012345@pdsb.net
```

**Sample Ouput 5**
```
not in pdsb
```
---
