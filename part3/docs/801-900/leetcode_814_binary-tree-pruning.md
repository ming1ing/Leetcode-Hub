# 814. [中等] 二叉树剪枝

**题目链接：**[https://leetcode-cn.com/problems/binary-tree-pruning](https://leetcode-cn.com/problems/binary-tree-pruning)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>给定二叉树根结点&nbsp;<code>root</code>&nbsp;，此外树的每个结点的值要么是 0，要么是 1。</p> 
  <p>返回移除了所有不包含 1 的子树的原二叉树。</p> 
  <p>( 节点 X 的子树为 X 本身，以及所有 X 的后代。)</p> 
  <pre class="language-text"><strong>示例1:</strong>
<strong>输入:</strong> [1,null,0,0,1]
<strong>输出: </strong>[1,null,0,null,1]
 
<strong>解释:</strong> 
只有红色节点满足条件“所有不包含 1 的子树”。
右图为返回的答案。

<img style="width:450px" src="/uploads/2018/04/06/1028_2.png" alt="">
</pre> 
  <pre class="language-text"><strong>示例2:</strong>
<strong>输入:</strong> [1,0,1,0,0,0,1]
<strong>输出: </strong>[1,null,1,null,1]


<img style="width:450px" src="/uploads/2018/04/06/1028_1.png" alt="">
</pre> 
  <pre class="language-text"><strong>示例3:</strong>
<strong>输入:</strong> [1,1,0,1,1,0,1,0]
<strong>输出: </strong>[1,1,0,1,1,null,1]


<img style="width:450px" src="/uploads/2018/04/05/1028.png" alt="">
</pre> 
  <p><strong>说明: </strong></p> 
  <ul> 
   <li>给定的二叉树最多有&nbsp;<code>100</code>&nbsp;个节点。</li> 
   <li>每个节点的值只会为&nbsp;<code>0</code> 或&nbsp;<code>1</code>&nbsp;。</li> 
  </ul> 
 </div>
</div>

---

```java
/**
 * Definition for a binary tree node.
 * public class TreeNode {
 *     int val;
 *     TreeNode left;
 *     TreeNode right;
 *     TreeNode(int x) { val = x; }
 * }
 */
class Solution {
    public TreeNode pruneTree(TreeNode root) {
        
    }
}
```