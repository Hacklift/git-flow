# git-flow
A simple assignment to help learners level up on git commands and work flows.



After each step, add your changes, commit and then push to github.

Steps:

1. Create a new direcotry named `git-flow` for your project.
   Open the directory with Your editor (e.g Visual Studio Code)
   Initial git in this directory (ie `git init`)
   

2. In the directory `git-flow`, create a new file called `age-calculator.py`.
   In the file type `print("I will be 100 years old in the year 2080")`
   Save your changes. You can run `python age-calculator.py` to see the result of your code


3. Checkout a new branch called `add-name`
   Update your code to look like the following
   ```
   name = input("What is your name: ")
   print(name + " will be 100 years old in the year 2080")
   ```
   Save your changes. You can run `python age-calculator.py` to see the result of your code
   On your github, make a Pull Request (PR) to the master branch.
   Merge the PR.


4. Checkout the master branch (ie on your local machine, switch back to master branch)
   Pull the origin master.
   Checkout a new branch called `add-age`
   Update your code to..
   ```
   name = input("What is your name: ")
   age = int(input("How old are you: "))
   print(name + " will be " + age + " years old in the year 2080")
   ```
   Save your changes. You can run `python age-calculator.py` to see the result of your code
   On your github, make a Pull Request (PR) to the master branch.
   Merge the PR.

5. Checkout the master branch (ie on your local machine, switch back to master branch)
   Pull the origin master.
   Checkout a new branch called `add-year`
   Update your code to look like the following
   ```
   name = input("What is your name: ")
   age = int(input("How old are you: "))
   year = str((2018 - age)+100)
   print(name + " will be 100 years old in the year " + year)
   ```
   Save your changes. You can run `python age-calculator.py` to see the result of your code
   On your github, make a Pull Request (PR) to the master branch.
   Merge the PR.
