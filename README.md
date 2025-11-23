The application creates and handles a file called tasks.json in the same directory where the script was invoked. The tasks are stored in this JSON file, so the application can read the tasks the next time it runs.


Sample tasks.json data:


[
    {
        "id": 1,
        "description": "Draft the project README file",
        "done": true
    },
    {
        "id": 2,
        "description": "Refactor the main loop",
        "done": false
    }
]


📝 Project Structure


The complete application logic is in a single Python file:


Project.py: Contains all functions used to load, save, add, view, mark, and delete tasks, plus the main execution loop.


tasks.json: (Automatically created) List of tasks.


🤝 Contributing


Okay, if you want to contribute on this, please open an issue or submit a pull request!
