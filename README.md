#Python only (recommended software for code is IDLE)
print('Welcome to QUIZ TEMPLATE ')
answer=input('Are you ready to play the Quiz ? (yes/no) :')
score=0
total_questions=3
 
if answer.lower()=='yes':
    answer=input('Question 1: Who is better your choice or your choice ?')
    if answer.lower()=='your choice':
        score += 1
        print('correct')
    else:
        print('your choice of dialouge :(')
        
answer=input('Question 2:do i prefer your choice of your choice ?')
if answer.lower()=='your choice':
        score += 1
        print('correct')
else:
        print('your choice of dialouge  :(')

print("your choice of dialouge")
 
