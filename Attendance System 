students = []
while True:
 print("1. attendance")
 print("2. view attendance")
 print("3. Exit")

 choice = input("Enter your choice: ")
 if choice == "1":
    name = input("Enter your name: ")
    status = input("Enter if present or absent: ")
    students.append({"name": name, "status":status})
  
    print("Attendance recorded ")
 elif choice =="2":
   print("Attendance record")
   if len(students) == 0:
     print("No attendance record ")
   else:
     for student in students:
      print(student["name"], "-", student["status"])
 elif choice =="3":
   print("thank you for using this system")
   break
 else:
   print("please choose a number 1, 2 or 3")
   break