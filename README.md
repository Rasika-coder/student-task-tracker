code
import json

FILE_NAME = "tasks.json"

# Load tasks from file
def load_tasks():
    try:
        with open(FILE_NAME, "r") as file:
            return json.load(file)
    except:
        return []

# Save tasks to file
def save_tasks(tasks):
    with open(FILE_NAME, "w") as file:
        json.dump(tasks, file)

# Add task
def add_task(tasks):
    task = input("Enter task: ")
    tasks.append(task)
    save_tasks(tasks)
    print("Task added successfully")

# View tasks
def view_tasks(tasks):
    if len(tasks) == 0:
        print("No tasks available")
    else:
        print("\nYour Tasks:")
        for i, t in enumerate(tasks):
            print(f"{i+1}. {t}")

# Delete task
def delete_task(tasks):
    view_tasks(tasks)
    try:
        num = int(input("Enter task number to delete: ")) - 1
        if 0 <= num < len(tasks):
            removed = tasks.pop(num)
            save_tasks(tasks)
            print(f"Task '{removed}' deleted successfully")
        else:
            print("Invalid task number")
    except:
        print("Please enter a valid number")

# Main program
def main():
    tasks = load_tasks()

    while True:
        print("\n===== Student Task Tracker =====")
        print("1. Add Task")
        print("2. View Tasks")
        print("3. Delete Task")
        print("4. Exit")

        choice = input("Enter choice: ")

        if choice == "1":
            add_task(tasks)

        elif choice == "2":
            view_tasks(tasks)

        elif choice == "3":
            delete_task(tasks)

        elif choice == "4":
            print("Exiting program...")
            break

        else:
            print("Invalid choice. Try again.")

if __name__ == "__main__":
    main()
