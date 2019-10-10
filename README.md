from tkinter import *

mainloop = Tk()
mainloop.title("Численность популяций")
mainloop.geometry("550x530)

# 1

ngrost=Label(mainloop, text = "Неограниченный рост", bg = "green")
ngrost.place ( x = 100, y = 10)

A=Label(mainloop, text = 'A')
A.place (x = 10, y = 50)

zhertv=Entry(mainloop, width = 5)
zhertv.place(x = 30, y = 50)

bt_ngrost = Button (mainloop, text = "Неограниченный рост", bg = "gray")
bt_ngrost.place(x = 65, y = 45)

ent = Entry(mainloop, width = 20)
ent.place(x=210, y=50)

# 2 

ogrost=Label(mainloop, text = "Ограниченный рост", bg = "green")
ogrost.place(x=105, y=70)

B=Label(mainloop, text = 'B')
B.place (x=10, y=100)

zhertv2=Entry(mainloop, width = 5)
zhertv2.place(x = 25, y = 100)

bt_ogrost = Button (mainloop, text = "Ограниченный рост", bg = "gray")
bt_ogrost.place(x = 65, y = 95)

ent2 = Entry(mainloop, width = 7)
ent2.place(x=198, y=100)

# 3

ogtrapp=Label(mainloop, text = "Ограниченный рост с отловом", bg = "green")
ogtrapp.place(x=70, y=130)

С=Label(mainloop, text = 'С')
С.place (x=10, y=160)

zhertv3=Entry(mainloop, width = 5)
zhertv3.place(x = 25, y = 160)

bt_ogtrapp = Button (mainloop, text = "Ограниченный рост с отловом", bg = "gray")
bt_ogtrapp.place(x = 65, y = 155)

ent3 = Entry(mainloop, width = 7)
ent3.place(x=260, y=160)

# 4

predat=Label(mainloop, text = "Жертва-хищник",bg = "green")
predat.place(x=115, y=190)

D=Label(mainloop, text = 'D')
D.place (x=10, y=220)

zhertv4=Entry(mainloop, width = 5)
zhertv4.place(x = 25, y = 220)

F=Label(mainloop, text = 'F')
F.place (x=60, y=220)

zhertv5=Entry(mainloop, width = 5)
zhertv5.place(x = 75, y = 220)

G=Label(mainloop, text = "G")
G.place(x=110, y=220)

zhertv6=Entry(mainloop, width = 5)
zhertv6.place(x = 125, y = 220)

bt_predat = Button (mainloop, text = "Жертва-хищник", bg = "gray")
bt_predat.place(x = 170, y = 215)


victims=Label(mainloop, text="Жертвы")
victims.place(x=40, y=245)

victims1=Entry(mainloop, width = 5)
victims1.place(x=100, y = 245)


predators=Label(mainloop, text="Хищники")
predators.place(x=140, y=245)

predators1=Entry(mainloop, width=5)
predators1.place(x=200, y=245)

# 5

victimscan=Label(mainloop, text="Жертвы")
victimscan.place(x=10, y=285)

zhertv7=Entry(mainloop, width = 5)
zhertv7.place(x = 85, y = 285)

predatorscan=Label(mainloop, text="Хищники")
predatorscan.place(x=10, y=315)

zhertv8=Entry(mainloop, width = 5)
zhertv8.place(x = 85, y = 315)

cikl=Label(mainloop, text="Кол. циклов")
cikl.place(x=10, y=345)

klcikl=Entry(mainloop, width = 5)
klcikl.place(x = 85, y = 345)

bt_graf=Button(mainloop, text="График", bg="Gray")
bt_graf.place(x=40, y = 415)

canv=Canvas(mainloop, width=200, heigh=200, bg="white", )
canv.place(x=135, y=285)
