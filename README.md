from tkinter import *

window = Tk()

window.geometry("600x600")
window.configure(background = "black")

#Used Grid Method
l1 = Label(window, text = "Label 1", bg = "pink", fg = "magenta", width = 12, padx = 20, pady = 20)
l1.grid(row = 0, column = 0)



l2 = Label(window, text = "Label 2", bg = "lightgreen", fg = "magenta", width = 12, padx = 20, pady = 20)
l2.grid(row = 0, column = 1)



l3 = Label(window, text = "Label 3", bg = "red", fg = "magenta", width = 12, padx = 20, pady = 20)
l3.grid(row = 0, column = 2)



l4 = Label(window, text = "Label 4", bg = "darkblue", fg = "magenta", width = 24, padx = 20, pady = 20)
l4.grid(row = 1, column = 0, columnspan = 2, sticky = "EW")



l5 = Label(window, text = "Label 5", bg = "brown", fg = "magenta", width = 12, padx = 20, pady = 20)
l5.grid(row = 1, column = 2)


window.mainloop()
