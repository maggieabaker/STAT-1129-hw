#problem 1
n = 0
while n < 10:
    print(n)
    n = n+1
    if n == 5:
        break

#problem 2
n = 0
while n < 5:
    print(n)
    n= n+1
    if n ==5:
        print(n, 'is not less than 5')
        
#problem 3
fruit = ['pear', 'strawberry', 'melon', 'apple', 'blueberry', 'grape']
for i in fruit:
    if i == 'apple':
        print('Is apple really a fruit?')
        break
    print('I like',i)
    
    
#problem4
n = 0
s = 0
while n < 30:
    n = n+1
    s = s + n
print(s)


#problem5
score = [33, 78, 49, 63, 99, 65, 82]
for i in range (0, len(score)):
    if score[i] >= 90:
       grade = 'A'
    elif score[i] >= 80:
        grade = 'B'
    elif score[i] >= 70:
        grade = 'C'
    elif score [i] >=60:
        grade = 'D'
    else:
        grade = 'F'
    print('student', i+1, 'received a', grade)
    
#problem 6
marks = {'Andy':88, 'Amy':66, 'James':90, 'Jules':55, 'Arthur':77}
for i,j in marks.items():
    print(i,j)
    
n =0
list1=[]
for i in marks:
    list1.append(marks[i])
    n = n + marks[i]
mean = n/len(marks)

print('the mean grade was',mean)
print('the minimum grade was',min(list1),'and the maximum grade was', max(list1))

for i in marks.keys():
    if 'J' in i:
        break
    print(i)
    
for i in marks.keys():
    if 'J' in i:
        continue
    print(i)
