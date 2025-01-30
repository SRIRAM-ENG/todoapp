**Input:**  
The ToDo list app follows the Input-Process-Output (IPO) model to manage user interactions. Users enter task descriptions in an input field and click the "Add Task" button to submit them. The app processes this input by adding the new task to the list. Users can also remove tasks by clicking the "Delete" button next to each item.  

**Process:**  
The app operates in two steps. First, when a user clicks "Add Task," the app captures the input text, checks if it is not empty, and then updates the task list using the usestate hook. Second, when a user clicks "Delete" on a task, the handleDeleteTodo function identifies and removes the selected task from the list.  

**Output:**  
The app updates the ToDo list in real-time. Using the map function, it dynamically generates and displays tasks on the screen, each with a "Delete" button for easy removal. This implementation ensures a seamless user experience by efficiently collecting input, processing tasks, and instantly updating the display.