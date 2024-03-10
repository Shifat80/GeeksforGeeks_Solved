<h2><a href="https://www.geeksforgeeks.org/problems/delete-without-head-pointer/1">Delete without head pointer</a></h2><h3>Difficulty Level : Easy</h3><hr><div class="problems_problem_content__Xm_eO"><p><span style="font-size: 18px;">You have a singly linked list of size <strong>n&nbsp;</strong> and given a target value. You have to <strong>remove </strong>the <strong>first occurence </strong>of the node with value equal to the target from the linked list.</span><span style="color: #273239; font-family: Nunito, sans-serif;"><span style="font-size: 18px; letter-spacing: 0.162px;"><br></span></span><span style="font-size: 18px;"><strong>Note:</strong> No head reference is given to you. It is&nbsp;guaranteed&nbsp;that the node to be deleted is<strong>&nbsp;not a tail node&nbsp;</strong>in the linked list.</span></p>
<p><span style="font-size: 18px;"><strong>Example 1:</strong></span></p>
<pre><span style="font-size: 18px;"><strong>Input:
</strong>n = 2
value[] = {1,2}
target = 1
<strong>Output: </strong>2<strong>
Explanation: </strong>After deleting 1 from the
linked list, we have remaining nodes
as 2.</span>
</pre>
<p><span style="font-size: 18px;"><strong>Example 2:</strong></span></p>
<pre><span style="font-size: 18px;"><strong>Input:
</strong>n = 4
value[] = {10,20,4,30}
target = 20
<strong>Output: </strong>10 4 30<strong>
Explanation: </strong>After deleting 20 from
the linked list, we have remaining
nodes as 10, 4, 30.</span></pre>
<p><span style="font-size: 18px;"><strong>Your Task:</strong><br>You only need to complete the function<strong> deleteNode() </strong>that takes <strong>reference </strong>to the node that needs to be <strong>deleted</strong>. The function should take only <strong>one argument</strong>, which is a <strong>pointer to the first occurence </strong>of a node with value equal to the <strong>target </strong>which is to be deleted. The <strong>printing </strong>is done <strong>automatically </strong>by the<strong> driver code</strong>.</span></p>
<p><span style="font-size: 18px;"><strong>Expected Time Complexity</strong> : O(1).<br><strong>Expected Auxilliary Space</strong> : O(1).</span></p>
<p><span style="font-size: 18px;"><strong>Constraints:</strong><br>2 &lt;= n &lt;= 10<sup>3&nbsp;</sup>&nbsp;<br>1 &lt;= value[i] &lt;= 10<sup>9</sup> <br>1 &lt;= target &lt;= 10<sup>9<br></sup>It is guaranteed that there exists a node with value equal to the target and it will not be the last node of the linked list.</span></p></div><p><span style=font-size:18px><strong>Company Tags : </strong><br><code>Amazon</code>&nbsp;<code>Microsoft</code>&nbsp;<code>Samsung</code>&nbsp;<code>Visa</code>&nbsp;<code>Goldman Sachs</code>&nbsp;<code>Kritikal Solutions</code>&nbsp;<br><p><span style=font-size:18px><strong>Topic Tags : </strong><br><code>Linked List</code>&nbsp;<code>Data Structures</code>&nbsp;