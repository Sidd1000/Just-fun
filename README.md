
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
