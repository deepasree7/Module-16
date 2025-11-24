# Ex. No: 16A - Constructing and Printing an AVL Tree in Python

## AIM:
To write a Python program to construct an **AVL tree** and print the nodes of it using the appropriate packages and built-in function.

---

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Define a function `getDictTree(tree)` to return the **dict_tree** of an AVL tree.

**Step 3**: Define a function `Construct_AVL(L)` to:
- Create an **AVL tree** from the list `L`.
- Get and print the **dict_tree** using `getDictTree(tree)`.

**Step 4**: Define a list `L` with integer values.

**Step 5**: Call `Construct_AVL(L)` to build the tree and print the result.

**Step 6**: End the program.

---

## PYTHON PROGRAM
```
from TreeAVL.AVL import AVL

def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print(getDictTree(tree))

L=[10,20,30,40,50,25]```

```

## OUTPUT

<img width="835" height="89" alt="443772767-32dfadb9-1f63-44fd-ae10-6e3693baa752" src="https://github.com/user-attachments/assets/d57a9cd9-f8ca-4887-8da1-b9f871a28132" />

## RESULT
Thus, the python program to construct an AVL tree and print the nodes of it using the appropriate packages and built-in function has been executed and verified successfully.
