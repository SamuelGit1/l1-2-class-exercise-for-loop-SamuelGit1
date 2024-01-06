# 404B Lesson 1 Class Exercise - For Loop

## Instructions

### Split VS Code Window

You can drag `main.py` tab to the right side of the window to split the window into two panes. This will allow you to see the instructions and the code at the same time.

### Answering

You can answer the questions by writing your answers in the `main.py` file.

You can run the code by clicking the `Run` button on the top right corner of the editor.

The output will be shown in the `Terminal` tab at the bottom of the editor.

## For-Loop Examples

- Sample (1): `range(stop)`

    ```py
    for i in range(5):
        print(f'i becomes {i}')

    Outputs: 
    i becomes 0
    i becomes 1
    i becomes 2
    i becomes 3
    i becomes 4
    ```

- Sample (2): `range(start, stop)`

    ```py
    for i in range(5, 10):
        print(f'i becomes {i}')
        
    Outputs: 
    i becomes 5
    i becomes 6
    i becomes 7
    i becomes 8
    i becomes 9
    ```

- Sample (3): `range(start, stop, step)`

    ```py
    for i in range(50, 100, 10):
        print(f'i becomes {i}')
        
    Outputs: 
    i becomes 50
    i becomes 60
    i becomes 70
    i becomes 80
    i becomes 90
    ```

## Questions

1. Use a for loop to print the numbers range from zero ~ a million.
  
2. Use a for loop to find the sum from zero ~ a million.
  
3. Write a program with for-loop to produce the following sequences:
    > 2, 4, 6, 8, 10, 12, ...

4. Write a program with for-loop to produce the following sequences:
    > 97, 94, 91, 88, 85, 82, ...

5. Write a for-loop that produces the following output:

    > 1 4 9 16 25 36 49 64 81 100

    a) using `*` multiplcation operator

    b) without using `*` multication operator

6. Write a for-loop to produce the following outputs:

    ```py
    *****
    *****
    *****
    *****
    *****
    ```

    Hint: You may multiply a string with integer.

    ```py
    print('*' * 20)
    Output: ********************
    ```

7. Write a for-loop to produce the following outputs:

    ```py
    *
    **
    ***
    ****
    *****
    ```

8. Write a for-loop to produce the following outputs:

    ```py
    ******
    *****
    ****
    ***
    **
    *
    ```

9. Write a for-loop to produce the following outputs:

    ```py
    1
    22
    333
    4444
    55555
    ```
