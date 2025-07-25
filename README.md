
## 📝 Task Tracker


This is a simple python program that can help you to track your tasks. 

#### Usage with Examples:
- To add a task, use: `add [task-description]`

```bash
task-cli > add "Buy groceries"
# Output: Task added successfully (ID: 1)
```
- To update a task, use: `update [task-id] [new-description]`
```bash
task-cli > update 1 "Buy groceries and cook dinner"
# Output: Task updated successfully (ID: 1)
```
- To delete a task, use: `delete [task-id]`
```bash
task-cli > delete 1
# Output: Task deleted successfully (ID: 1)
```
- To mark tasks as in-progress or done, use: `mark-in-progress [task-id]` & `mark-done [task-id]`
```bash
task-cli > mark-in-progress 1 
# Output: Task marked successfully (ID: 1)
task-cli > mark-done 1 
# Output: Task marked successfully (ID: 1)
```
- To list down task, use: `list`
```bash
task-cli > list 

# Output:
----------------------------------------
1. Buy milk - Done
2. Eat soda - In-progress
3. Fix keyboard - Done
4. Go outside - In-progress
----------------------------------------
```
- You can also specify the status like: `list done` for completed tasks and `list todo` or `list in-progress` for in progress tasks.

```bash
task-cli > list done

# Output:
----------------------------------------
1. Buy milk - Done
3. Fix keyboard - Done
----------------------------------------
```
```bash
task-cli > list todo 

# Output:
----------------------------------------
2. Eat soda - In-progress
4. Go outside - In-progress
----------------------------------------
```
---
Idea taken from [Task Tracker](https://roadmap.sh/projects/task-tracker) and built as a personalized CLI tool.
