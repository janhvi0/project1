# project1
python program for student attendance portal
# STUDENT ATTENDANCE PORTAL------ 




print("~Studence Attendace Portal~")

while(True):
    print('Choose one of the following Operation:-\n'
          '1. Give Attendance\n'
          '2. Check Attendance')
    choise = input('=')
    
    if choise == '1':
        stud_name = input('Enter Your name:-')
        stud_rollno=input('Enter Your RollNo:-')
        print('Your Attendance Is registered Successfully!!')
        menu = input('Return to main menu(yes/no):-')
        if menu == 'no':
            print('ThankYou!!')
            break
            
        elif choise == '2':
        list=[['janhvi','111'],['kim','112'],['park','113'],['jeon','114'],['min','115'],['jung','116']]
        sname=input('Enter student name:-')
        if sname in list:
            print(sname,'is Present')
        else:
            print(sname,'is Absent')

        menu = input('Return to main menu(yes/no):-')
        if menu == 'no':
            print('ThankYou!!')
            break
