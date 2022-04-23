# spam.py
import pyautogui
import time

message =  input("masukan pesan : ")
n = input("nominal : ")
print("Proses")

count = 5
while(count != 0) :
    time.sleep(1)
    count -= 1

print("Kelar")
for i in range (0, int(n)):
    pyautogui.typewrite(message + '\n')
