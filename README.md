# DSA-PROJECT
##Project name:Splay Tree

##Group Members: Almas (18B-088-SE-B),Zainab(18B-42-SE-B)

There are two classes in this project Node and Splay Tree.

The main function in this project is Insert and Delete a node.The sub-functions are rotate_left,rotate_right,splay,maximum,search,inorder.

When you want to insert a Node in Tree you have to make object of class Node and then pass the object of Node class into Insert Function of Splaytree class so it is obivious that you have to make object of splaytree class first.

Repeat step 6 when you want to delete Node from tree.Now you call delete function instead of insert function.

Now, to print the data you have to call inorder function of splaytree class.This function takes 1 argument which is root of tree .Root of tree is a attribute of splaytree class so you can access it by using object of splaytree class.

For example:

ob=SplayTree()

a=Node(15)

b=Node(10)

c=Node(30)

ob.insert(a)

ob.insert(b)

ob.insert(c)

ob.delete(a)

ob.inorder(ob.root)
