```markdown
# Task Management Commands

## Overview

This document outlines the commands for managing your tasks using a Go-based application.

## Commands

### View Tasks

To view your current tasks, run:
```

go run ./ -list

```

### Add Task
To add a new task, use the following command:
```

go run ./ -add "2: Go for a walk"

```

### Add Task
To Edit a task, use the following command:
```

go run ./ -edit "2: Go for a walk"

```


### Change Task to Completed
To mark a task as completed or toggle its status, run:
```

go run ./ -toggle 2

```

### Delete Task
To delete a specific task, use this command:
```

go run ./ -del 2

```

## Notes
- Replace `2` with the task number you want to edit or delete.
- Ensure that your Go environment is set up to run these commands successfully.
```

You can copy and paste this directly into your Markdown file!
