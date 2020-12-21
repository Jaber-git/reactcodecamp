
 <span align ="left" > span left </span>
    
 <span align="right" > span right</span>
    


<p align="center">

<a href="http://unlicense.org/">
<img src="https://img.shields.io/badge/license-Unlicense-blue.svg" alt="License: Unlicense">
</a>

<a href="https://github.com/markdown-templates/markdown-snippets/issues">
<img src="https://img.shields.io/github/issues/markdown-templates/markdown-snippets.svg" alt="Issues">
</a>

<a href="https://github.com/markdown-templates/markdown-snippets/fork">
<img src="https://img.shields.io/github/forks/markdown-templates/markdown-snippets.svg" alt="Forks">
</a>

<a href="https://github.com/markdown-templates/markdown-snippets/stargazers">
<img src="https://img.shields.io/github/stars/markdown-templates/markdown-snippets.svg" alt="Stars">
</a>

</p>

 
  <p align ="left" style="float:left ;"> paragraph </p>
    
  <p align="right" style="float:right ;"> paragraph </p>
    
    
<div width="40%" style=" background-color:blue;">
    
 <p align ="left" style="float:left ;"> paragraph </p>
    
 <p align="right" style="float:right ;"> paragraph </p>
    
<a href="http://unlicense.org/">
<img src="https://img.shields.io/badge/license-Unlicense-blue.svg" alt="License: Unlicense">
</a>

<a href="https://github.com/markdown-templates/markdown-snippets/issues">
<img src="https://img.shields.io/github/issues/markdown-templates/markdown-snippets.svg" alt="Issues">
</a>

</div>

<div width="40%" style="color:red;">
    
<a href="https://github.com/markdown-templates/markdown-snippets/fork">
<img src="https://img.shields.io/github/forks/markdown-templates/markdown-snippets.svg" alt="Forks">
</a>

<a href="https://github.com/markdown-templates/markdown-snippets/stargazers">
<img src="https://img.shields.io/github/stars/markdown-templates/markdown-snippets.svg" alt="Stars">
</a>

</div>



# Rule 1
Description for rule 1.


    <p align="left" >
        <h2>Good</h2>
        int foo (void) {
    int i;
}

    </p>
    <p align="right">
        <h2>Bad</h2>
      int foo (void) {
    int i;
}

    </p>

``` 
<table>
<tr>
<th> Good </th>
<th> Bad </th>
</tr>
<tr>
<td
    
  ```
                        c++
                        int foo() {
                            int result = 4;
                            return result;
                        }
 ```
</td>
<td>
 
```

                                                                c++
                                                                int foo() { 
                                                                    int x = 4;
                                                                    return x;
                                                                }

```
</td>
</tr>
</table>
```

turn into -
<table>
<tr>
<th> Good </th>
<th> Bad </th>
</tr>
<tr>
<td
    
  ```
                        c++
                        int foo() {
                            int result = 4;
                            return result;
                        }
 ```
</td>
<td>
 
```

                                                                c++
                                                                int foo() { 
                                                                    int x = 4;
                                                                    return x;
                                                                }

```
</td>
</tr>
</table>
# two column
# Rule 1
Description for rule 1.

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div style="display: inline-block;">
        <h2>Good</h2>
        <pre><code class="language-c">int foo (void) 
{
    int i;
}
</code></pre>
    </div>
    <div style="display: inline-block;">
        <h2>Bad</h2>
        <pre><code class="language-c">int foo (void) {
    int i;
}
</code></pre>
    </div>
</div>

Blockquotes can contain other Markdown elements, including headers, lists, and code blocks:

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

<br>
To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab. For example, given this input:

This is a normal paragraph:

    This is a code block.

Markdown will generate:

```
<p>This is a normal paragraph:</p>

<pre><code>This is a code block.
</code></pre>
```
<br>

<p>This is a normal paragraph:</p>

<pre><code>This is a code block.
</code></pre>
<br>
One level of indentation — 4 spaces or 1 tab — is removed from each line of the code block. For example, this:

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

will turn into:
```
<p>Here is an example of AppleScript:</p>

<pre><code>tell application "Foo"
    beep
end tell
</code></pre>
```

<p>Here is an example of AppleScript:</p>

<pre><code>tell application "Foo"
    beep
end tell
</code></pre>

```
<table>     <tr>         <td># Massgeschneiderte<br>Lösungen für Firmen<br>und Privatpersonen</td>         <td>![](illu.png)</td>     </tr> </table>
```
turn into
<table>     <tr>         <td># Massgeschneiderte<br>Lösungen für Firmen<br>und Privatpersonen</td>         <td>![](illu.png)</td>     </tr> </table>
