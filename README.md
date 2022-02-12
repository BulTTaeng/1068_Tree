# 1068_Tree

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1068_Tree/blob/main/1068_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , Recursive

## What was the key point and the hard part?

I think it is much easier to solve it with dfs...

I solve it this way because of a competitive mind.

If we get the input, if some node is parent of some node, it means it is not leaf node. So, I chekc it is_p[i] = true;

After that with recursive function, if parent of some node is erasing node number , make it false, and make that nodes children false too.

In here , we have one problem.

If deleting node is only child node of parent, the parent node becomes leaf node , but this algorithm does not countt this situation.

So before doing recursive function, I check if deleting node is only child of parent, and if it does , I check parent node as leaf node.

DFS will be much easier I think... Use DFS ;)

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
