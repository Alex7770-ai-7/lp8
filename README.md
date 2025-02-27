import colorama
from colorama import Fore, Back, Style

colorama.init(autoreset=True)

print("Атрибуты colorama:", dir(colorama), "\n")

print(Fore.RED + "Червоний текст")
print(Fore.GREEN + "Зелений текст")
print(Back.YELLOW + "Жовтий фон" + Back.RESET)
print(Style.BRIGHT + "Яскравий текст")
print(Style.DIM + "Тьмяний текст")

colorama.deinit()
