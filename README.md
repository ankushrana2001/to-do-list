📝 To-Do List CLI Application (Python)
A simple Command-Line Interface (CLI) To-Do List application written in Python that allows users to add tasks with deadlines, delete tasks, and view all tasks in a user-friendly format.
This project demonstrates basic Python concepts like functions, date validation, loops, and conditionals — ideal for beginners!

📖 Features
✅ Add new tasks with a deadline (in DD-MM-YYYY format)

✅ Delete tasks by selecting their task number

✅ Display all current tasks with formatted deadlines

✅ Exit the application gracefully

✅ Date format validation to prevent invalid inputs

📦 Requirements
Python 3.x
(No external libraries needed — uses Python's built-in datetime module)

📂 Project Structure
bash
Copy
Edit
ToDoList/
│
├── todo_list.py    # Main Python script
├── README.md       # Project documentation
🚀 How to Run
Clone the repository (or download the todo_list.py file)

bash
Copy
Edit
git clone https://github.com/yourusername/ToDoList.git
Navigate to the project directory

bash
Copy
Edit
cd ToDoList
Run the Python script

bash
Copy
Edit
python todo_list.py
📸 Application Preview
mathematica
Copy
Edit
Welcome to the To-Do List Application!

Choose one operation:
1. Add Task
2. Delete Task
3. Display Tasks
4. Exit
📚 Code Breakdown
add_task(): Adds a task after validating the deadline format.

delete_task(): Removes a task based on its task number.

display_tasks(): Lists all tasks with deadlines.

validate_date(): Validates if the deadline input is in the correct DD-MM-YYYY format.

userChoice(): Manages user menu selections and routes to the appropriate function.

🎯 Reference
This project idea was inspired by simple Python console applications and structured referencing CodeChef’s beginner-level problem-solving projects and practices.

🛠️ Author
Ankush Rana ✨
