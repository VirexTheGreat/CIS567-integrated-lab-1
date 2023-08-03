# CIS567-integrated-lab-1
Week 5



first_number = int(input())
second_number = int(input())
if second_number < first_number:
    print("Second integer can't be less than the first.")
else:
    # Loop from the first number to the second number, incrementing by 5 each time
    for num in range(first_number, second_number+1, 5):
        print(num, end=' ')
    print()
