numbers = ("one", "two", "three", "four", "five", "six", "seven", "eight", "nine", "ten",
           "eleven", "twelve", "thirteen", "fourteen", "fifteen", "sixteen", "seventeen",
           "eighteen", "nineteen", "twenty")
           
ask = int(input("Type a number between [1] and [20]: "))

item = numbers[ask - 1]

print(f"You typed the number [{item}]")
---------------------------------------------------------------------------------------------------------------------------------------------------
    
teams = ("Bragantino", 'Flamengo', 'Botafogo', 'Athletico', 'Gremio', 'Internacional', 'Atletico MG', 'Fortaleza', 'Bahia', 'Fluminense', 'Palmeiras', 'Cruzeiro', 'Juventude', 'São Paulo', 'Vasco da gama', 'Criciuma', 'Vitória', 'Corithians', 'Atletico GO', 'Cuiaba')

print(f'The 5 first teams in the table are', teams[0:5])
print('-='*10)
print('The 5 last teams in the tabele are', teams[14:-1])
print('-='*10)
print('Teams in the alphabetical order ',sorted(teams))
print('-='*10)
juventude = 'Juventude'
position = teams.index(juventude)
print(f'the juventude team is the {position}° position')

---------------------------------------------------------------------------------------------------------------------------------------------------
#074

from random import randint 

numbers = (randint(1,10), randint(1,10), randint(1,10), randint(1,10), randint(1,10))

print (f'The sorted numbers were : {numbers}')
print (f'The biggest number was {max(numbers)} and  the smallest number was {min(numbers)}')
