Name = "Mohammad Rizwan"
ID = "5674"
Centre = "Gulshan Campus" 
Slot = "Sunday 9 to 12"

Phy = 78
Maths = 88
Eng = 79
Comp = 82
Chem = 72

total_marks = int (Phy+Maths+Eng+Comp+Chem)
percentage = int ((total_marks/500)*100)


if percentage>= 80:
    grade = "A-1"
if percentage>= 70 and percentage < 80:
    grade = "A"
if percentage>= 60 and percentage < 70:
    grade = "B"
if percentage>= 50 and percentage < 70:
    grade = "C"
if percentage< 50:
    grade = "F"
    
print ("Name:" + Name)
print ("ID:" + ID)
print ("Centre:" + Centre)
print ("Slot:" + Slot)
print ("Marks Obtained:" , total_marks)
print ("Percentage:" , percentage)
print ("Grade:" + grade)
