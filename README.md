# 📌 CLI Task Manager

A simple command-line task manager built with Python and SQLite. Manage your to-do list easily from the terminal!

## 🚀 Features
- ✅ Add tasks
- 📋 List tasks
- 🎉 Mark tasks as completed
- 🗑️ Remove tasks
- 💾 Persistent storage using SQLite

## 🛠️ Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Nouran-11/cli-task-manager.git
   cd cli-task-manager
   ```
2. **Ensure you have Python installed** (>= 3.x)
3. **Run the script**:
   ```sh
   python task_manager.py --help
   ```

## 📖 Usage
### Add a new task
```sh
python task_manager.py --add "Finish MLH application"
```
### List all tasks
```sh
python task_manager.py --list
```
### Mark a task as completed
```sh
python task_manager.py --complete 1
```
### Remove a task
```sh
python task_manager.py --remove 1
```

## 📂 File Structure
```
cli-task-manager/
│── task_manager.py  # Main script
│── tasks.db         # SQLite database (auto-generated)
│── README.md        # Project documentation
```

## 🏆 Contributing
Contributions are welcome! Feel free to submit an issue or pull request.

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
 
