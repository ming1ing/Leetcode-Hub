# 177. [中等] 第N高的薪水

**题目链接：**[https://leetcode-cn.com/problems/nth-highest-salary](https://leetcode-cn.com/problems/nth-highest-salary)

---

<div class="content__1Y2H">
 <div class="notranslate">
  <p>编写一个 SQL 查询，获取 <code>Employee</code> 表中第&nbsp;<em>n&nbsp;</em>高的薪水（Salary）。</p> 
  <pre class="language-text">+----+--------+
| Id | Salary |
+----+--------+
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |
+----+--------+
</pre> 
  <p>例如上述&nbsp;<code>Employee</code>&nbsp;表，<em>n = 2&nbsp;</em>时，应返回第二高的薪水&nbsp;<code>200</code>。如果不存在第&nbsp;<em>n&nbsp;</em>高的薪水，那么查询应返回&nbsp;<code>null</code>。</p> 
  <pre class="language-text">+------------------------+
| getNthHighestSalary(2) |
+------------------------+
| 200                    |
+------------------------+
</pre> 
 </div>
</div>

---

```sql
CREATE FUNCTION getNthHighestSalary(N INT) RETURNS INT
BEGIN
  RETURN (
      # Write your MySQL query statement below.
      
  );
END
```