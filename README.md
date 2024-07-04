# python-tutorials
A collection of beginner-friendly Python tutorials and exercises
class ToDoList:
    def __init__(self):
        self.tasks = []

    def add_task(self, task):
        self.tasks.append(task)

    def show_tasks(self):
        for task in self.tasks:
            print(task)

my_list = ToDoList()
my_list.add_task("Learn Python")
my_list.add_task("Build a project")
my_list.show_tasks()
