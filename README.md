ticket = int(input('Введите количество билетов '))
age = [int(input('Введите возраст всех участников ')) for i in range(ticket)]
sum = 0
for i in range(len(age)):
    if age [i] <= 18:
        sum += 0
    elif 18 <= age [i] <= 25:
        sum += 990
    else:
        sum += 1390
if ticket>=3:sum=sum*0.9
print (sum)
