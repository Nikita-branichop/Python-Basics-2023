# Задача 1 - Hello SoftUni

Напишете конзолна Python програма, която отпечатва текста "Hello SoftUni".

```python
print ('Hello SoftUni')
```

---
# Задача 2 - Nums 1...10

Напишете Python конзолна програма, която отпечатва числата от 1 до 10 на отделни редове на конзолата.

```python
print (1)
print (2)
print (3)
print (4)
print (5)
print (6)
print (7)
print (8)
print (9)  
print (10)
```

---
# Задача 3 - Rectangle Area

Да се напише конзолна програма, която въвежда две цели числа (страните на правоъгълника a и b) и пресмята лицето на правоъгълник с тези страни.

```python
a = int(input())
b = int(input())
print (a * b)
```

---
# Задача 4 - Inches to Centimeters

Да се напише програма, която чете от конзолата реално число и го преобразува от инчове в сантиметри. За целта умножете инчовете по 2.54 (1 инч = 2.54 сантиметра).

```python
a = float(input())
print(a * 2.54)
```

---
# Задача 5 - Greeting by Name

Да се напише програма, която чете от конзолата текст (име на човек) и отпечатва "Hello, &lt;name&gt;!", където name е въведеното име от конзолата.

```python
name = input()
print('Hello,' + name + '!')
```

---
# Задача 6 - Concatenate Data

Напишете програма, която прочита от конзолата име, фамилия, възраст и град и печата следното съобщение: "You are &lt;firstName&gt; &lt;lastName&gt;, a &lt;age&gt;-years old person from &lt;town&gt;."

```python
first_name = input()
last_name = input()
age = input()
town = input()
print(f'You are {first_name} {last_name}, a {age}-years old person from {town}.')
```

---
# Задача 7 - Projects Creation

Напишете програма, която изчислява колко часа ще са необходими на един архитект, за да изготви проектите на няколко строителни обекта. Изготвянето на един проект отнема три часа.

```python
architect = input()
projects = int(input())
print(f'The architect {architect} will need {projects * 3} hours to complete {projects} project/s.')
```

---
# Задача 8 - Pet Shop

Напишете програма, която пресмята нужните разходи за закупуването на храна за кучета и котки.  Храната се пазарува от зоомагазин, като една опаковка храна за кучета е на цена 2.50 лв, а опаковка храна за котки струва 4 лв.

```python
food_dog = int(input())
food_cat = int(input())
print(f'{food_dog * 2.50 + food_cat * 4} lv.')
```

---
# Задача 9 - Yard Greening

Божидара разполага с няколко къщи на Черноморието и желае да озелени дворовете на някои от тях, като по този начин създаде уютна обстановка и комфорт на гостите си. За целта е наела фирма.<br>
Напишете програма, която изчислява необходиматa сума, които Божидара ще трябва да заплати на фирмата изпълнител на проекта. Цената на един кв. м. е 7.61 лв със ДДС. Понеже нейният двор е доста голям, фирмата изпълнител предлага 18% отстъпка от крайната цена.


```python
size = float(input())
print(f'The final price is: {size * 7.61 - size * 7.61 * 0.18} lv.')
print(f'The discount is: {size * 7.61 * 0.18} lv.')
```
