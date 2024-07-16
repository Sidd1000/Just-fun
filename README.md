
import tkinter as tk

# Create the main application window
root = tk.Tk()
root.title("Simple Frame Example")

# Create a frame widget
frame = tk.Frame(root, padx=20, pady=20)
frame.pack(padx=50, pady=50)

# Add some widgets (e.g., labels, buttons) inside the frame
label = tk.Label(frame, text="Hello, this is a frame!")
label.pack()

button = tk.Button(frame, text="Click Me!", command=lambda: print("Button clicked!"))
button.pack()

# Start the tkinter main loop
root.mainloop()





import tkinter as tk
from tkinter import messagebox

def login():
    username = entry_username.get()
    password = entry_password.get()

    # Yaha par aap authentication logic daal sakte hain
    # Jaise ki username aur password ka validation

    if username == "admin" and password == "password":
        messagebox.showinfo("Login Successful", "Welcome, Admin!")
    else:
        messagebox.showerror("Login Failed", "Invalid username or password")

# Create the main application window
root = tk.Tk()
root.title("Login Frame Example")

# Create a frame widget
frame = tk.Frame(root, padx=20, pady=20)
frame.pack(padx=50, pady=50)

# Username Label and Entry
label_username = tk.Label(frame, text="Username:")
label_username.grid(row=0, column=0, sticky="w", padx=5, pady=5)
entry_username = tk.Entry(frame)
entry_username.grid(row=0, column=1, padx=5, pady=5)

# Password Label and Entry
label_password = tk.Label(frame, text="Password:")
label_password.grid(row=1, column=0, sticky="w", padx=5, pady=5)
entry_password = tk.Entry(frame, show="*")  # show="*" will hide the password
entry_password.grid(row=1, column=1, padx=5, pady=5)

# Login Button
button_login = tk.Button(frame, text="Login", command=login)
button_login.grid(row=2, columnspan=2, pady=10)

# Start the tkinter main loop
root.mainloop()








# Just-fun
Something interesting and kidding 
a = 40
b = 5
num = print(a % b)

 


def is_divisible_by_7(49):
  """Checks if a number is divisible by 7.

  Args:
    number: The number to check.

  Returns:
    True if the number is divisible by 7, False otherwise.
  """

  if 49 % 7 == 0:
    return True
  else:
    return False

# Get input from the user
num = int(input("49: "))

# Check if the number is divisible by 7
if is_divisible_by_7(49):
  print(f"{49} is divisible by 7.")
else:
  print(f"{49} is not divisible by 7.")
