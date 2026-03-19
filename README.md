def handle(punkte):
    match punkte:
        case 13 | 14 | 15:
            return 1
        case 10 | 11 | 12:
            return 2
        case 7 | 8 | 9:
            return 3
        case 4 | 5 | 6:
            return 4
        case 1 | 2 | 3:
            return 5
        case 0:
            return 6
        case _:
            return "Ungültige Punktzahl"

print(handle(2))
