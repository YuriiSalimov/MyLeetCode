<a href="https://leetcode.com/problems/daily-temperatures/" target="_blank">
    <img src="https://assets.leetcode.com/static_assets/public/webpack_bundles/images/logo-dark.e99485d9b.svg"
        style="width:150px" alt="LeetCode"/>
</a>

### 108. Convert Sorted Array to Binary Search Tree

<span style="color:orange">Medium</span>

Given an array of integers `temperatures` represents the daily temperatures,
return _an array_ `answer` such that `answer[i]` _is the number of days you have
to wait after the <code>i<sup>th</sup></code> day to get a warmer temperature_.
If there is no future day for which this is possible,
keep `answer[i] == 0 instead`.

__Example 1:__
<pre>
<b>Input:</b> temperatures = [73,74,75,71,69,72,76,73]
<b>Output:</b> [1,1,4,2,1,1,0,0]
</pre>

__Example 2:__
<pre>
<b>Input:</b> temperatures = [30,40,50,60]
<b>Output:</b> [1,1,1,0]
</pre>

__Example 3:__
<pre>
<b>Input:</b> temperatures = [30,60,90]
<b>Output:</b> [1,1,0]
</pre>

__Constraints:__

* <code>1 <= temperatures.length <= 10<sup>5</sup></code>
* `30 <= temperatures[i] <= 100`
