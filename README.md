# Demo1
Code Conversion
class  Student:
    def __init__(self,name,rollnum,marks):
        self.name=name
        self.rollnum=rollnum
        self.marks=marks
    
    def talk(self):
        print('I amrr:', self.name)
        print('my roll number is:', self.rollnum)
        print('my marks:',self.marks)
        
s1=Student('santhosh',101,90)
s2=Student('job',102,95)
s1.talk()
s2.talk()
        
