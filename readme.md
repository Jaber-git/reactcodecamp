# Rule 1
Description for rule 1.

<div style="float:left ;width:50%;">
    <div style="display: inline-block;">
        <h2>Good</h2>
        <pre><code class="language-c">int foo (void) 
{
    int i;
}
</code></pre>
    </div>
    <div style="display: inline-block; float:right; width:45%;">
        <h2>Bad</h2>
        <pre><code class="language-c">int foo (void) {
    int i;
}
</code></pre>
    </div>
</div>

<table>
<tr>
<th> Good </th>
<th> Bad </th>
</tr>
<tr>
<td>

```c++
int foo() {
    int result = 4;
    return result;
}
```

</td>
<td>

```c++
int foo() { 
    int x = 4;
    return x;
}
```

</td>
</tr>
</table>
