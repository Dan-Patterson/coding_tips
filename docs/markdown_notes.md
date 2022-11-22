# Markdown notes

**comments**

They begin 
<!-- have to be followed by an empty line! -->
  \<!-- A comment between the exclamation marks ! -->

----
**collapsible table of contents**
- The first one just contains one block.
- The second one contains two blocks.
- Click ``Raw`` to see the actual code.


<details>
<summary markdown="span">1. This link is closed. Click me to see more</summary>
This is where all the great stuff goes, all on one level.
</details>
<details>
<summary markdown="span">2. Another level in the level</summary>
</br>
A line break before more stuff.

- list
- second
- third


<details open>
<summary markdown="span">2.1 This one is open by default. Click me to collapse...</summary>
</br>

```python
def some_func:
   """There is </br> and a blank line before the ``def``"""
   return "hello"
```

So this one hides all the levels.
</details>
</details>

----
**Line breaks**

Especially after an image, use:

\<br clear="all"\>

This provides a clear break and removes the need to pad with extra lines.
