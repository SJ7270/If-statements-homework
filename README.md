# If-statements-homework
integer = float(input('put integer here: '))
if integer % 2 == 1:
    print ('even')
else:
        print ('odd')

human_age = int(input('put human age here: '))
if human_age < 2: 
    first_dog_years = human_age * 10.5
    print (f'the total dog years is {first_dog_years}' )

else:
    remaining_years = human_age - 2
    dog_years = remaining_years * 4
    amount_of_first_years = human_age - remaining_years
    first_dog_years = amount_of_first_years * 10.5
    total_dog_years = first_dog_years + dog_years
    print (f'the total amount of dog years is {total_dog_years}' )

if human_age < 0:
    print ('error')

letter = input('put letter here: ')
if letter == 'a' or letter == 'i' or \
letter == 'e' or letter == 'o' or \
letter == 'u':
    print ('this is a vowel')
elif letter == 'y':
    print ('this is sometimes a vowel and a consonant')
else:
    print ('this is not a vowel')

sides = int(input('put number of sides here: '))
if sides == 3:
    print ('it is a triangle')
if sides == 4:
    print ('it is a square')
if sides == 5:
    print ('it is a pentagon')
if sides == 6:
    print ('it is a hexagon')
if sides == 7:
    print ('it is a heptagon')
if sides == 8:
    print ('it is a octagon')
if sides == 9:
    print ('it is a nonagon')
if sides == 10:
    print ('it is a decagon')
elif sides > 10:
    print ('error')
else:
    print ('error')

year = int(input('put year here: '))
new_year = year - 2000
if new_year % 12 == 0:
    print ('the animal associated with this year is dragon')
if new_year % 12 == 1:
    print ('the animal associated with this year is snake')
if new_year % 12 == 2:
    print ('the animal associated with this year is horse')
if new_year % 12 == 3:
    print ('the year associated with this year is sheep')
if new_year % 12 == 4:
    print ('the year associated with this year is monkey')
if new_year % 12 == 5:
    print ('the year associated with this year is rooster')
if new_year % 12 == 6:
    print ('the year associated with this year is dog')
if new_year % 12 == 7:
    print ('the year associated with this year is pig')
if new_year % 12 == 8:
    print ('the year associated with this year is rat')
if new_year % 12 == 9:
    print ('the year associated with this year is ox')
if new_year % 12 == 10:
    print ('the year associated with this year is tiger')
if new_year % 12 == 11:
    print ('the year associated with this year is hare')
