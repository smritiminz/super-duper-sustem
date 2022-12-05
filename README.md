# super-duper-sustem
print("Welcome to the tip calculator. ")
bill=eval(input("What was the total bill?"))
tip=int(input("What percentage tip would you like to give? 10,20 or 30?"))
split=int(input("How many people to split the bill?"))
total_bill=bill+tip
splited_bill=total_bill/split
print(f"Each person will pay {splited_bill} rupees.")
