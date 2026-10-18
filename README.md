# Class-project
weights = []

for i in range(4):
    weight = float(input())
    weights.append(weight)

print(weights)

average = sum(weights) / len(weights)
print(f'{average:.2f}')

max_weight = max(weights)
print(f'{max_weight:.2f}')

index = int(input())

pounds = weights[index]
kilograms = pounds / 2.2

print(f'{pounds:.2f} pounds')
print(f'{kilograms:.2f} kilograms')
