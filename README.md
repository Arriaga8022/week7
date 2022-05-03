Part 1

[week 5_6 flow.pdf](https://github.com/Arriaga8022/week7/files/8612924/week.5_6.flow.pdf)

Part 2

while True:
    #taking user input for name
    name = input("employee name:")
    #taking user input for hours you worked
    name = input("employee name:")
    #taking user input for hourly rate..
    hourlyRate = float(input("Enter hourly rate(in $): "))
    #finding pay using given formula..
    pay = hoursWorked*hourlyRate
    #prinitng output..
    print("\n******Output******\n")
    print("Name: ",name,"\nHourly rate: ",hourlyRate,"\nHours worked:
    ",hoursWorked,"\nPay : $",pay)
    


Input: two float values
Output: three float values

1.	Insert rate
2.	Insert hrsworked
3.	Calculate pay:rate*hrsworked
4.	Print pay
5.	Ask user if they wish
To perform another calculation
Y, go back to step 1
N, exit the program
O, if user did not input y/n, we will ask the user, until we receive a y/n answer

Total pay
#input to stop script from closing: bad
name=('adam adam')
name=('adam bart')
name=('adam glenn')
name=('adam good')
name=('adam green')
name=('error')
name=('adam adam [11] is [40]')
name=('adam bart [12] is [35]')
name=('adam glenn [13] is [30]')
name=('adam good [14] is [25]')
name=('adam green [15] is [20]')
 
#Code

#create loop
#without loop list

user = input("input to stop script from closing: ")

a = ("adam","bart","glenn","good","green")
b=[10,]
c=["40","35","30","25","20",]
    
for i in a:
    print(i)
    if i == user:
      break
else:
    print("error")

    print("adam", b[0]+1, "is", c[0])
    print("bart", b[0]+2, "is", c[1])
    print("glenn", b[0]+3, "is", c[2])
    print("good", b[0]+4, "is", c[3])
    print("green", b[0]+5, "is", c[4])
