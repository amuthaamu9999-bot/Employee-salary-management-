salary = []
n = int(input("Enter number of employees: "))
# Insertion
for i in range(n):
    s = int(input("Enter salary: "))
    salary.append(s)
# Traversal
print("Employee Salaries:")
for i in salary:
    print(i)
# Update operation
pos = int(input("Enter position to update salary: "))
new_salary = int(input("Enter new salary: "))
salary[pos] = new_salary
print("Updated Salaries:", salary)# Employee-salary-management-
Practical programs
