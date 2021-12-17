from tkinter import *
from tkinter import messagebox
import webbrowser
import os
import sys
pro = Tk ()
pro.geometry('800x300+280+50')
pro.resizable(False,False)
pro.title('ali ahmed')
title = Label (pro , text='ali ahmed',fg='gold',bg='black',font= ('tajawal',16,'bold'))
title.pack(fill=X)

F1 = Frame(pro , width=230 , height=420 , bg='red')
F1.place(x=590,y=28)
Title1 = Label (F1 , text='Ali Ahmed' , bg='red' , fg='white' , font=('tajwal',12,'bold')) 
Title1.place(x=42,y=10)
Title2 = Label(F1,text='A_tty', bg='red',fg='white' , font=('tajawal',12,'bold'))
Title2.place(x=52,y=50)
Title3 = Label(F1 , text='0772728372' ,bg='red',fg='white', font=('tajawal',12,'bold'))
Title3.place(x=50,y=90)
B1=Button(F1, text='insta',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B1.place(x=6,y=177)
B2=Button(F1, text='insta',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B2.place(x=6,y=190)
B3=Button(F1, text='insta',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B3.place(x=6,y=230)
B4=Button(F1, text='wotsob',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B4.place(x=6,y=260)
B5=Button(F1, text='feisbook',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B5.place(x=6,y=290)
B6=Button(F1, text='07723975616',width=26,fg='black',bg='red',font=('tajawal',11,'bold'))
B6.place(x=6,y=330)
