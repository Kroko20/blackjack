import random

def main():
    number = random.randint(1,21)
    enemy = random.randint(1,21)
    winlose = True
    print("У вас " + str(number) + " очка(ов).")

    while True:
        choice = input("Будете брать карту?\nВыберите Y или N")
        if choice == "y":
            number += random.randint(1,11)
            print("У вас " + str(number) + " очка(ов).")
        if choice == "n":
            print("Вы не взяли карту")
            break
        if number >= 22:
            print("Вы проиграли! У вас: " + str(number))
            winlose = False
            break

    if winlose == False:
        pass
    else:
        if enemy >= number:
            print("Вы проиграли! У вашего соперника: " + str(enemy) + "\nУ вас: " + str(number))
        elif enemy == number:
            print("Ничья! У вашего соперника: " + str(enemy) + "\nУ вас: " + str(number))
        else:
            print("Вы выиграли! У вашего соперника: " + str(enemy) + "\nУ вас: " + str(number))
    

main()
while True:
    flag = input('Ещё раз? [y/n]: ')

    if flag == 'y':
        main()
    else:
        break
