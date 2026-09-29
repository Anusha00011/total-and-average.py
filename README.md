n = int(input("Enter the number of values: "))

total = 0

for i in range(n):
    value = float(input(f"Enter value {i + 1}: "))
    total += value

average = total / n

print("\nTotal =", total)
print("Average =", average)# total-and-average.py
total and average
