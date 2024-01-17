# Reselect Two

### Intro

Often frustrated by the impossibility of juggling between the last Selection and
the one which precedes it.  I missed the possibility of being able to invoke the
previous Selection regularly enough to end up creating this base.  This work in
progress is **dirty, buggy, and open to contributions**.

### Description

In addition to the well known **gv** which reselect the *last VISUAL Selection*, you
can press **gV** to reselect the *previous VISUAL Selection*, the one which is
overwritten by **gv** when a new selection is done.

In the example I create two selection, then I alternate from one to the other
using **gv** and **gV**.

![Vim Reselect Two](./doc/vim-reselect-two.gif)

### Get Started

* Install with *vim-plug* or any other plugin manager:

  `Plug 'clemedon/vim-reselect-two'`

* Press **v**, **V**, **<C-V>** or **<C-Q>** to create a 1st VISUAL Selection.
* Quit VISUAL mode with **<Esc>**.
* ress **v**, **V**, **<C-V>** or **<C-Q>** to create a 2nd VISUAL Selection.
* Quit VISUAL mode with **<Esc>**.
* Switch between the 1st and the 2nd Selection with **gv** and **gV**.
