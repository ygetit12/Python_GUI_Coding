from tkinter import*

r=Tk()
r.title('First GUI')
r.geometry('500x500+0+0')
l=Label(text='First Text')
l.pack()

r.mainloop()


# #============# #

from tkinter import*

r=Tk()
r.title('First GUI')
r.geometry('500x500+0+0')
l1=Label(text='First Text',fg='red').pack()
l2=Label(text='Second Text',bg='hot pink').pack()

r.mainloop()
