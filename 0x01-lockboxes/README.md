# :book: 0x01. Lockboxes
## Topics Covered
1. Python.
2. Lockboxes.

# :computer: Tasks.
## [0. Lockboxes](0-lockboxes.py)
### Task requirements.
You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and each box may contain keys to the other boxes.

Write a method that determines if all the boxes can be opened.

  *  Prototype: def canUnlockAll(boxes)
  *  boxes is a list of lists
  *  You can assume all keys will be positive integers
      *  There can be keys that do not have boxes
  *  The first box boxes[0] is unlocked
  *  Return True if all boxes can be opened, else return False
### :wrench: Task setup.
```bash
# Create task file and set write permission.
touch ./0-lockboxes.py
chmod +x ./0-lockboxes.py
./0-lockboxes.py

# Lint the code.
pycodestyle ./0-lockboxes.py
pep8 ./0-lockboxes.py

# Create test file
touch ./0-main.py
chmod +x ./0-main.py
./0-main.py
```

### :heavy_check_mark: Solution.
> [:point_right:  Open 0-lockboxes.py](0-lockboxes.py)

# :books: References
1. [Python Lists](https://www.w3schools.com/python/python_lists.asp)
1. [Python sum() Function](https://www.w3schools.com/python/ref_func_sum.asp)

:thumbsup: A lot of thanks to [ALX-Africa Software Engineering](https://www.alxafrica.com/) program for the project requirements.
