<h2>unknown-problem</h2><h3>Medium</h3><hr><div><p>Given two <a href="https://en.wikipedia.org/wiki/Sparse_matrix" target="_blank">sparse matrices</a> <b>A</b> and <b>B</b>, return the result of <b>AB</b>.</p>

<p>You may assume that <b>A</b>'s column number is equal to <b>B</b>'s row number.</p>

<p><b>Example:</b></p>

<pre><b>Input:

</b><strong>A</strong> = [
  [ 1, 0, 0],
  [-1, 0, 3]
]

<strong>B</strong> = [
  [ 7, 0, 0 ],
  [ 0, 0, 0 ],
  [ 0, 0, 1 ]
]

<strong>Output:</strong>

     |  1 0 0 |   | 7 0 0 |   |  7 0 0 |
<b>AB</b> = | -1 0 3 | x | 0 0 0 | = | -7 0 3 |
                  | 0 0 1 |
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= A.length, B.length &lt;= 100</code></li>
	<li><code>1 &lt;= A[i].length, B[i].length &lt;= 100</code></li>
	<li><code>-100 &lt;= A[i][j], B[i][j]&nbsp;&lt;= 100</code></li>
</ul>
</div>