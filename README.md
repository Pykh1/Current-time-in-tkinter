# Display Current-time-in-tkinter
import tkinter as tk
import time as tm
my_window=tk.Tk()
my_window.title("current_time")
current_time=tm.strftime("%H:%M:%S")
clock_label=tk.Label(my_window,font="arial 80",bg="green",fg="black",text=current_time)
clock_label.grid(row=0,column=0)
my_window.mainloop()

