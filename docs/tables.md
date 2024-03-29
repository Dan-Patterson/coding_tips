# Tables in docstrings

Here is a sample header for some function that demonstrates two options for including a table.

```
    def some_func(_n, _p, _c, _seen, _outside, _inside):
        """Some function which uses a table to describe options for two variables `poly` and `clp`.

        Parameters
        ----------
        parameter meanings::

            ====== ====== ===== ===== ======  ========== ========
              x     _n     _p    _c   _seen   _outside   _inside
            ------ ------ ----- ----- ------  ---------- --------
            poly   pl_n   p_p   p_c   p_seen  p_outside  p_inside
            clip   cl_n   c_p   c_c   c_seen  c_outside  c_inside
            ====== ====== ===== ===== ======  ========== ========


        +------+-------+-----+-----+--------+-----------+----------+
        |      |  _n   | _p  | _c  | _seen  | _outside  | _inside  |
        +======+=======+=====+=====+========+===========+==========+
        | poly |  pl_n | p_p | p_c | p_seen | p_outside | p_inside |
        +------+-------+-----+-----+--------+-----------+----------+
        |clip  | cl_n  | c_p | c_c | c_seen | c_outside | c_inside |
        +------+-------+-----+-----+--------+-----------+----------+

        """
```
What it looks like when the function is called.

The image ...

<a href="url"><img src="docstring_table.png" align="left" height="auto" width="400"></a>

The double colon at the end of `parameter meaning` enables the box format of the simple table.  That table uses spacing and dashes of both formats to provide the table structure.

The second table format uses dashes, + and the | (pipe) to provide the structure.  One should note that the top left corner can be empty in this table variant and not in the first (which required an `x` to maintain the structure).


