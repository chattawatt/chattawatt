from microbit import *
x=0
ei = Image("88888:"
"60006:"
"60006:"
"60006:"
"88888")
isi = Image("77777:"
"00007"
"00070"
"00700"
"77777")

while True:
    if button_a.is_pressed():
        display.show(ei)
        sleep(500)
        display.show(Image.HEART)
        sleep(500)
        display.show(Image.DIAMOND)
        sleep(500)
        display.show(Image.COW)
        sleep(600)
    if button_b.is_pressed():
        display.show(Image.SKULL)
        sleep(500)
        display.show(Image.GHOST)
        sleep(500)
        display.show(isi)
        sleep(600)
        display.show(Image.TARGET)
        sleep(500)
