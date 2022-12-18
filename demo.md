---
marp: true
theme: uncover
class: invert
math: mathjax
style: |
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }
---

# Testing Marp!
<span style="color:green">H</span>jodra :cat:

---

## List!

* Element 1
* Element 2

---

## Code!

```c++
#include <iostream>
using namespace std;

int main() {
    cout << "Hello world" << endl;
    return 0;
}
```

```python
print("Hello world")
```

---

## Math!

Single line expression

$\sum_{i=1}^n i = \frac{n(n+1)}{2}$

Or, multiple lines expression

$$
\begin{aligned}
\xi &= \frac{1}{2} \left( \frac{1}{\alpha} + \frac{1}{\beta} \right) 
\end{aligned}
$$

---

## Images!

![width:4in blur:2px](Profile.png) 

---

## Two columns!

![bg left width:4in](Profile.png)

* a
* b

---

<!--_color: red -->
<!--_backgroundColor: black-->
# <!--fit-->Huge

---

## Two Text columns!

<div class="columns">
<div>

* a
* b
* c

</div>
<div>

* d
* e
* f

</div>
</div>