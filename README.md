# SCHOOL-ADMINISTRATION-
Developed by: SUBASRI R

# School Administration Programe

student_info = input('Enter student information for student n{} in the following format[Name Age Contact_Number E-mail_Id]: ')

student_info_list = student_info.split()

print("\n The Entered information is -\nName: {}\nAge: {}\nContact_Number: {}\nE-mail_Id: {}".format (student_info_list[0], student_info_list[1], student_info_list[2], student_info_list[3]))

choice_check = input("Is the Entered information is correct? (yes/no):")

if choice_check =="yes":
			condition_check = input("Enter (yes/no) if you want to enter information for another student: ")
			
			if condition_check == "yes":
				condition = True
			
			elif condition_check =="no":
				condition = False
				
elif chice_check == "no":
			print("\Please re-enter the values!")
			
