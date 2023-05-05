Download Link: https://assignmentchef.com/product/solved-cse100-algorithm-design-and-analysis-lab-04
<br>
<strong>Max Subarray</strong>

In this lab assignment, your job is to implement the <em>O</em>(<em>n</em>log<em>n</em>) time divide-and-conquer algorithm for the Max Subarray Problem; for the pseudo-code, see page 72 in the textbook. Recall that in the problem, we are given as input an array <em>A</em>[1···<em>n</em>] of <em>n </em>integers, and would like to find <em>i</em><sup>∗ </sup>and <em>j</em><sup>∗ </sup>(1 ≤ <em>i</em><sup>∗ </sup>≤ <em>j</em><sup>∗ </sup>≤ <em>n</em>) such that <em>A</em>[<em>i</em><sup>∗</sup>] + <em>A</em>[<em>i</em><sup>∗ </sup>+ 1] + ··· + <em>A</em>[<em>j</em><sup>∗</sup>] is maximized.

<strong>Input structure </strong>The input starts with an integer number <em>n</em>, which indicates the array size. Then, the integers, <em>A</em>[1]<em>,A</em>[2]<em>,</em>···<em>,A</em>[<em>n</em>]<em>, </em>follow, one per line.

<strong>Output structure </strong>Output the sum of integers in the max subarray, i.e., <em>A</em>[<em>i</em><sup>∗</sup>] + <em>A</em>[<em>i</em><sup>∗ </sup>+ 1] + ··· + <em>A</em>[<em>j</em><sup>∗</sup>].