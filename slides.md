---
marp: true
theme: default
style: |
  .ccolumns {
    display: grid;
    grid-template-columns: 50% auto;
    gap: 1rem;
  }
---

![bg fit](assets/ucl-banner.png)

<br/><br/><br/><!-- aesthetic vspace so the title isn't too close to the UCL banner -->

<!-- if html tags appear then: https://github.com/marp-team/marpit/issues/178#issuecomment-511106762 -->


# Erik Burman FEM Error Estimates.
## Project Debrief Talk.

Sam Cunliffe, Matt Graham, Matthew Scroggs

ARC Collaborations' Hour. 2025-08-19.

---

<!--
paginate: true
footer: F. Author, 202Y-MM-DD.
-->

# A basic slide with bullets

- First point.
- Second point.

---

# Slide with bullets that appear

<!-- prettier-ignore-start -->

* I appear...
* Then I appear...
* Then **I** appear 🎉!

<!-- prettier-ignore-end -->

---

# Centered on a slide

<center>

Example of something centred.

</center> 

---

# Split bullet slide

<br/>
<div class="ccolumns">
<div>

- Bullet to the left

</div>
<div>

- Bullet to the right

</div>

---

# Code

```py

def i_prefer_python() -> None
    print("Obviously, I use type hints")
    return

```

```c++

int butWillWriteCppIfNeeded()
{
  return 1337;
}

```

---

<!--
_footer: the footer is different on this slide only
-->

# Emoji are cool

- ❤️🎉✅

---

# Maths

- An example of inline maths $e^{i\pi} = -1$
- An example of display format maths:

$$
\widehat{f}(\xi) = \int_{-\infty}^{\infty} f(x)\ e^{-i 2\pi \xi x}\,dx.
$$


---

# Conclusions

- One or two clear take-home points.
- Don't overload your audience.

---

# Appendix

---

# Add appendix slides if needed

- Delete all of this if you don't need it.
- (Obviously)
