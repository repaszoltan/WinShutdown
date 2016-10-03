# Shutdown for Windows

#
import os

#
def stop(minute):
    f1 = open('sd.bat','w')
    sec = int(minute) * 60
    f1.write('shutdown -s -t '+str(sec))
    f1.close()
    os.system("sd.bat")
def abort():
    f2 = open('abort.bat','w')
    f2.write('shutdown -a')
    f2.close()
    os.system("abort.bat")

#
minute = input("Hány perc múlva kapcsoljam ki a gépet?")
stop(minute)

#
ab = input("Megszakítsam a leállást? i / n:  ")
if ab == "i":
    print("Leállítás megszakítva!")
    abort()
