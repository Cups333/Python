#Задание1
my_dict = {1: "0101101", 2: "101110", 3: "1A14C", 4: "1100100", 5: "101010"}
print(my_dict)
my_dict.pop(3)
print(my_dict)
my_dict[10] = "0100101"
print(my_dict)
#Задание2
sl = {"</>": 13, "script": 1, "___init___": 10, "seld": 5, "number_9": 6, "#comment": 100}
print(sl)
key = input("Введите ключ: ")
val = input("Введите значение: ")
sl[key] = val
print(sl)
#Задание3
dict1 = {}
while len(dict1) != 3:
    key = int(input("Введите ключ: "))
    val = input("Введите значение: ")
    dict1[key] = val
print(dict1)
#Задание4
all_d = {1: 15, 4: 80, 44: 0, 256: 15, 100: 70, 101: 70, 20: 444, 3: 9}
print(all_d)
key = (1, 101, 3)
for i in key:
    all_d.pop(i)
print(all_d)