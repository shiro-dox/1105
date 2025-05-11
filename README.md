# 1105
import pyautogui # в начале файла для подключения pyautogui

print(pyautogui.size()) # Узнать размеры окна
print(pyautogui.position()) # Узнать позицию мыши
pyautogui.moveTo(25, 1055) #Передвинули мышку в левый нижний угол экрана
pyautogui.click() # Сэмулировали нажатие левой кнопки мыши
pyautogui.click(button = ‘right’) # Клик правой клавишей
pyautogui.doubleClick() #Двойной клик 
pyautogui.dragTo(100, 200, button='left') #Передвинули мышку с нажатой левой клавишей
pyautogui.mouseDown() # нажать левую клавишу мыши и держать
pyautogui.mouseUp() # отпустить левую клавишу мыши

pyautogui.write('Hello world!')  # Напечатать на клавиатуре «Hello world»
pyautogui.write('Hello world!', interval=0.25) # То же, но с интервалом между  нажатиями клавиш
keyboard.write(“Привет”) # Напечатать на клавиатуре «Привет», нужно для русских
# букв
pyautogui.press('enter')  # Нажать enter. Вместо него могут быть ‘f1’,’left’,’shift’,’ctrl’,
# а также ‘a’,’b’,’1’,’2’,’*’, ‘win’ и т.д.
pyautogui.hotkey('ctrl', 'shift', 'esc', ‘a’) # Нажать несколько клавиш одновременно
pyautogui.hotkey('ctrl', 'c') # ctrl+c
pyautogui.keyDown('ctrl') # Нажать и не отпускать клавишу
pyautogui.keyUp('esc') # Отпустить нажатую клавишу

pyautogui.alert(text=”это текст”, title=”Заголовок”, button='OK') # Показать всплывающее сообщение

time.sleep(1) # ждать 1 секунду (требует import time)

