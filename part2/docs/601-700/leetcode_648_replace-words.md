# 648. [中等] 单词替换

**题目链接：**[https://leetcode-cn.com/problems/replace-words](https://leetcode-cn.com/problems/replace-words)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>在英语中，我们有一个叫做&nbsp;<code>词根</code>(root)的概念，它可以跟着其他一些词组成另一个较长的单词——我们称这个词为&nbsp;<code>继承词</code>(successor)。例如，词根<code>an</code>，跟随着单词&nbsp;<code>other</code>(其他)，可以形成新的单词&nbsp;<code>another</code>(另一个)。</p> 
  <p>现在，给定一个由许多词根组成的词典和一个句子。你需要将句子中的所有<code>继承词</code>用<code>词根</code>替换掉。如果<code>继承词</code>有许多可以形成它的<code>词根</code>，则用最短的词根替换它。</p> 
  <p>你需要输出替换之后的句子。</p> 
  <p><strong>示例 1:</strong></p> 
  <pre class="language-text"><strong>输入:</strong> dict(词典) = ["cat", "bat", "rat"]
sentence(句子) = "the cattle was rattled by the battery"
<strong>输出:</strong> "the cat was rat by the bat"
</pre> 
  <p><strong>注:</strong></p> 
  <ol> 
   <li>输入只包含小写字母。</li> 
   <li>1 &lt;= 字典单词数 &lt;=1000</li> 
   <li>1 &lt;=&nbsp; 句中词语数&nbsp;&lt;= 1000</li> 
   <li>1 &lt;= 词根长度 &lt;= 100</li> 
   <li>1 &lt;= 句中词语长度&nbsp;&lt;= 1000</li> 
  </ol> 
 </div>
</div>

---

```java
class Solution {
    public String replaceWords(List<String> dict, String sentence) {
        
    }
}
```