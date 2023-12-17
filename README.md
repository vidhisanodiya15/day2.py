#INDEX= POSITION
# name="Tony Stark"
# print(name.find('Stark'))

# print(name.replace("Tony Stark","Ironman"))

# print("T" in name)

#OPERATORS = SUM,MULTIPLY,SUB

# print(20/4)
# print(5%2)
# result= 2+3/5
# print(result)

#COMPRASION OPERATOR
# print(3<2)
# print(3!=2)   (here ! indicates opposite operator)

#OR OPERATOR
# print(2>3 or 2>1)

#AND OPERATOR
# print(3>2 and 2>6)

#NOT OPERATOR
# print(not 3>2)

#CONDITION STATEMENTS(IF AND ELSE)
# age =19

# if age >=18:
#     print("you are an adult")
#     print("you can vote")
# elif age<18 and age>3:
#     print("you are in school")
# else:
#     print("you are a child")
    
# print("thank you")

#IN-BUILD FUN
#MODULE FUN
#USER DEFINED FUN

# import math
# print(dir(math))

#USER DEFINED FUN
# SYNTAX= def function_name(parameters):
def print_sum(first,second=4):
    print(first+second)
    
print_sum(1)
#collection of items called complex datatype

marks=[45,76,23]

# for score in marks:
#     print(score)
# print(marks[-1])
# print(marks[0:2]) 

#APPEND= TO ADD 
# marks.append(99)
# print(marks)

#INSERT
# marks.insert(0,54)
# print( 54 in marks)

# print(len(marks))

i=0
while i <len(marks):
    print(marks[i])
    i=i+1
    
marks.clear()
print(marks)

# i =1
# while i<=5:
#     print(i * "*")
#     i =i+1
    
# i =5
# while i>=0:
#     print(i * "*")
#     i =i-1

#FOR LOOP
# for item in range(5):
#     print(item+1)
#touple cant be modified 
marks=(94,76,34,94)
print(marks.count(94))
print(marks.index(94))
#IT IS UESD FOR UNIQUE ELEMENTS
# marks={93,66,43,88}
# person="ram","ramu","radha"
#print(person)
#[]=list,()=tuples,{}=sets
# for score in marks:
    
#     print(score)
#DICTIONARY
# marks={"english":89,"chemistry":67}
# information={"ram":"balkishan"}
# print(marks["chemistry"])
# marks["physics"]=97
# print(marks)
students=["ram","shyam","kisan","radha"]

for student in students:
    if student== "kisan":
        continue
    print(student)
