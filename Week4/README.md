1. Tree Data Structure
实际中的一些应用比如：决策树 decision tree, 表达式树 expression tree, 文件系统 file system, 

	Root is most important – Heap
	Organized by character frequency – Huffman Tree or Compression Tree
	Organized by node ordering – Search Trees
	Etc...

2. Binary Search Tree (BST) V.S. Trie (Prefix Tree)

3. Preorder, Inorder, Postorder, level-order tree traversal. 前序，中序，后序, 层序 树遍历。
Order we visit matters and we'll make choices based on out needs. 可以再去看看刷过的题中的不同实现。


4. Tree Definition (树的定义)

	• Single root
	• Each node can have only one parent. Any parent can have any child nodes.
	• No cycles in a tree

5. 二叉搜索树BST又叫做 sorted binary tree. It allows fast lookup, addition and removal of items. BST keep their keys in sorted order. 二叉搜索树具有下列性质：1）若它的left child不空，则left sub tree上所有节点的值均小于它的根节点的值；若right child不空，则right sub tree所有节点的值均大于它的根节点的值。且它的左右子树也分别为二叉搜索树BST (recursive definition)；2）中序遍历Inorder traversal是升序序列。

6. 注意BST search的实现方式。 其中有一点：Don't change root pointer.

7. 