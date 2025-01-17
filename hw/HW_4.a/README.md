# CS-181/DA-210 Homework 4.a

The goal of this HW is to get set up with a local SQLite database and simple queries.

**Note that you may complete this homework with one partner.  You must type up all of the code yourself, but you can work together and look at each other's code.  You _must_ include the name of your partner, if any, in the cell at the end of single_table_proj.ipynb.**

---

## Step 1: SQLite Setup

Complete Parts A-C of [`getting_started.ipynb`](getting_started.ipynb) to get set up using a local SQLite database.

## Step 2: Column Projection

Complete Parts D-F of [`single_table_proj.ipynb`](single_table_proj.ipynb) to try out your first SQL queries, focusing on column projection within a single table.

## Step 3: Push your changes

Recall the general submission workflow, summarized here:

- Make your changes to complete the homework.

- Use the terminal command `git add <filepath>` for each file that you've changed and want to submit.  For this homework, you'll likely want the following (remember that `$` represents the prompt, so you don't type that part):

    ```
    $ git add hw/HW_4.a/getting_started.ipynb
    
    $ git add hw/HW_4.a/single_table_proj.ipynb
    ```

- You can use the command `git status` to verify that you've added the files you want to have in the commit.

- Use the terminal command `git commit -m "<commit message>"` to create a local commit.  For this homework, you could use:

    ```
    $ git commit -m "Completed HW 4.a."
    ```

- Use the terminal command `git push -u student main` to push your changes to your private Github repository; your instructor will pull from your repository in order to grade your homework:

    ```
    $ git push -u student main
    ```