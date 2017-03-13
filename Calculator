from tkinter import *
from math import *
import sys

root = Tk()
large_font = ('Verdana',20)
root.columnconfigure(0, weight=1)
root.columnconfigure(1, weight=1)
root.columnconfigure(2, weight=1)
root.columnconfigure(3, weight=1)
root.columnconfigure(4, weight=1)
root.rowconfigure(0, weight=1)
root.rowconfigure(1, weight=1)
root.rowconfigure(2, weight=1)
root.rowconfigure(3, weight=1)
root.rowconfigure(4, weight=1)
root.rowconfigure(5, weight=1)
root.rowconfigure(6, weight=1)

liste = []

def write1():
    liste.append("1")
    inbox.insert(len(liste), "1")

def write2():
    liste.append("1")
    inbox.insert(len(liste), "2")

def write3():
    liste.append("1")
    inbox.insert(len(liste), "3")

def write4():
    liste.append("1")
    inbox.insert(len(liste), "4")

def write5():
    liste.append("1")
    inbox.insert(len(liste), "5")

def write6():
    liste.append("1")
    inbox.insert(len(liste), "6")

def write7():
    liste.append("1")
    inbox.insert(len(liste), "7")

def write8():
    liste.append("1")
    inbox.insert(len(liste), "8")

def write9():
    liste.append("1")
    inbox.insert(len(liste), "9")

def write0():
    liste.append("1")
    inbox.insert(len(liste), "0")

def writeplus():
    liste.append("1")
    inbox.insert(len(liste), "+")

def writeminus():
    liste.append("1")
    inbox.insert(len(liste), "-")

def writediv():
    liste.append("1")
    inbox.insert(len(liste), "/")

def writemul():
    liste.append("1")
    inbox.insert(len(liste), "*")

def off():
    sys.exit()

def c():
    inbox.delete(0, END)

def Del():
    inbox.delete(len(inbox.get()) -1)


def evaluate():

    res = str(eval(inbox.get()+ ".0"))
    inbox.delete(0, END)
    inbox.insert(0, res)


root.geometry("200x220")

root.title("Rechner")

inboxVar = StringVar(value='')
inbox = Entry(root, width=750, textvariable=inboxVar, font=large_font)
inbox.grid(row=0, columnspan=5000)
inbox.bind("<Return>", evaluate)

button1 = Button(root, text="1", bg="black", fg="white", command = write1)
button1.config(font=("Arial", 20))
button1.grid(row=3, column=0, sticky=N+S+E+W)


button2 = Button(root, text="2", bg="black", fg="white", command = write2)
button2.config(font=("Arial", 20))
button2.grid(row=3, column=1, sticky=N+S+E+W)

button3 = Button(root, text="3", bg="black", fg="white", command = write3)
button3.config(font=("Arial", 20))
button3.grid(row=3, column=2, sticky=N+S+E+W)

button4 = Button(root, text="4", bg="black", fg="white", command = write4)
button4.config(font=("Arial", 20))
button4.grid(row=4, column=0, sticky=N+S+E+W)

button5 = Button(root, text="5", bg="black", fg="white", command = write5)
button5.config(font=("Arial", 20))
button5.grid(row=4, column=1, sticky=N+S+E+W)

button6 = Button(root, text="6", bg="black", fg="white", command = write6)
button6.config(font=("Arial", 20))
button6.grid(row=4, column=2, sticky=N+S+E+W)

button7 = Button(root, text="7", bg="black", fg="white", command = write7)
button7.config(font=("Arial", 20))
button7.grid(row=5, column=0, sticky=N+S+E+W)

button8 = Button(root, text="8", bg="black", fg="white", command = write8)
button8.config(font=("Arial", 20))
button8.grid(row=5, column=1, sticky=N+S+E+W)

button9 = Button(root, text="9", bg="black", fg="white", command = write9)
button9.config(font=("Arial", 20))
button9.grid(row=5, column=2, sticky=N+S+E+W)

button0 = Button(root, text="0", bg="black", fg="white", command = write0)
button0.config(font=("Arial", 20))
button0.grid(row=6, column=0, sticky=N+S+E+W)

buttonenter = Button(root, text="  =  ", bg="orange", fg="black", command=evaluate)
buttonenter.config(font=("Arial", 20))
buttonenter.grid(row=6, column=1, columnspan=2, sticky=N+S+E+W)

buttonplus = Button(root, text="+", bg="grey", fg="white", command = writeplus)
buttonplus.config(font=("Arial", 20))
buttonplus.grid(row=3, column=3, sticky=N+S+E+W)


buttonminus = Button(root, text="_", bg="grey", fg="white", command = writeminus)
buttonminus.config(font=("Arial", 20))
buttonminus.grid(row=4, column=3, sticky=N+S+E+W)

buttondiv = Button(root, text=" :", bg="grey", fg="white", command = writediv)
buttondiv.config(font=("Arial", 20))
buttondiv.grid(row=5, column=3, sticky=N+S+E+W)

buttonmul = Button(root, text="x", bg="grey", fg="white", command = writemul)
buttonmul.config(font=("Arial", 20))
buttonmul.grid(row=6, column=3, sticky=N+S+E+W)

buttonoff = Button(root, text="Off", bg="white", fg="black", command = off)
buttonoff.config(font=("Arial", 10))
buttonoff.grid(row=2, column=0, sticky=N+S+E+W)

buttonc = Button(root, text="Clr", bg="white", fg="black", command = c)
buttonc.config(font=("Arial", 10))
buttonc.grid(row=2, column=1, sticky=N+S+E+W)

buttondel = Button(root, text="     Del     ", bg="black", fg="white", command = Del)
buttondel.config(font=("Arial", 10))
buttondel.grid(row=2, column=2, columnspan=2, sticky=N+S+E+W)




root.mainloop()
