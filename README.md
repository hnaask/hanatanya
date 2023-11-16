import pyatogui, time
time.sleep(5)
binatangs = open('binatang.txt', 'r')
for bianatang in binatangs:
| pyatogui.typewrite(binatang)
| pyatogui.press()
