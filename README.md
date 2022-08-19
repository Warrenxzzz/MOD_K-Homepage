# MOD_K-Homepage
from random import randint
print('UMDK PRISON RUN')
feeling_brave = True
score = 0
while feeling_brave:
    ghost_door = randint(1, 3)
    print('Three Doors Ahead...')
    print('A Guard Behind One, more traps behind others...')
    print('Which door will you pick huh?')
    door = input('1, 2, or 3?')
    door_num = int(door)
    if door_num == ghost_door:
        print('Darr....')
        feeling_brave = False
    else:
        print('You are a lucky one, proceed to the next...')
        print('You peek into the next door and it swings open')
        score = score + 1
print('Huff.Huff.Huff')
print('You have entered the Congalia Space Port. Get 50% of any lower mart store! Must have 500 or more social credit.')
