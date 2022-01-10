#question1
number_1 = input('enter first number:')
number_2 = input('enter second number:')
number_3 = input('enter third number:')
average=(int(number_1)+int(number_2)+ int(number_3))/3
print('The average of three numbers is',average)

#question2
standard_deduction=10000
dependent_deduction=3000
gross_income=int(input('Please enter your gross income:'))
num_of_dependents=int(input('please enter the number of dependents:'))
taxable_income = gross_income - standard_deduction -(dependent_deduction*num_of_dependents)
tax = float(taxable_income)*0.2 #0.2 is used because tax rate is 20%
print('your income tax is:',tax) 

#question3
SID=int(input('Enter your SID :'))
Name=str(input('Enter your name:'))
Gender=str(input('Specify your gender:'))
Course_name=str(input('Enter your course name:'))
CGPA=float(input('Enter your cgpa:'))
STUDENT=[SID,Name,Gender,Course_name,CGPA]
print(STUDENT)

#question4
marks=[]
for i in range(5):
    marks.append(input("Enter marks of students:"))
marks.sort()
print(marks)

#question5
#part a
color=['Red','Green','White','Black','Pink','Yellow']
color.remove(color[3])
print('result for part A',color)
#part b
color=['Red','Green','White','Black','Pink','Yellow']
color[3:5]=['Purple']
print('result for part B',color)
