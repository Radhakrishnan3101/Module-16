Experiment 10(b): Balancing AVL Tree

Aim

To write a Python program to construct an AVL tree, balance it, and print the nodes of the tree before and after balancing using the appropriate packages and built-in functions.

Algorithm
```
Start the program.
Define getDictTree(self) to return the dictionary representation of the AVL tree.
Define Construct_AVL(L) to:
Create the AVL tree from the list L.
Print the tree before balancing.
Balance the tree using the BalanceTree() method.
Print the tree after balancing.
Create a list L of integers.
Call Construct_AVL(L) to build and balance the tree.
End the program.
```
Program
```
from TreeAVL.AVL import AVL



def getDictTree(self):
 return self.dict_tree

def Construct_AVL(L):
  tree = AVL(L)
  print("AVL Tree Before Balancing\n",getDictTree(tree))
  tree.BalanceTree()
  print("AVL Tree After Balancing\n",getDictTree(tree))


L=[11,8,18,5,13,17,4,7,2]
```
OUTPUT
![image](https://github.com/user-attachments/assets/b4cd4cfd-38b8-466e-a33c-f7f180d4be75)


RESULT
Thus the python program was initialised and executed successfully.
