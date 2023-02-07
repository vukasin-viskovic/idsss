---
# try also 'default' to start simple
theme: default
background: https://www.holland.com/upload_mm/4/8/f/68913_fullimage_vincent_van_gogh.jpg
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Introduction to Data Science for Social Scientists - March 2023
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Introduction to Data Science for Social Scientists

### Lesson 1 - Introduction to Python

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# What is Python?


- Python is a widely-used general-purpose, high-level programming language. It was initially designed by Guido van Rossum in 1991 and developed by Python Software Foundation. It was mainly developed for emphasis on code readability, and its syntax allows programmers to express concepts in fewer lines of code.
<br>
[*Source*](https://www.geeksforgeeks.org/history-of-python/)
<br>
<br>
- What started as a hobby project, soon became a general purpose programming language: nowadays, you can use Python to build practically any piece of software. But how did this happen?

<!--
Here is another comment.
-->


---

# Why is Python so popular?

- Well, first of all, Python is open source. It's free to use.

- Second, it's very easy to build packages in Python, which is code that you can share with other people to solve specific problems. Throughout time, more and more of these packages specifically built for data science have been developed. Suppose you want to make some fancy visualizations of your company's sales. There's a package for that. Or what about connecting to a database to analyze sensor measurements? There's also a package for that. People often refer to Python as the swiss army knife of programming languages as you can do almost anything with it.

---
layout: image-right
image: https://artsdot.com/ADC/Art-ImgScreen-1.nsf/O/A-5ZKGCX/$FILE/Vincent-van-gogh-flowering-garden.Jpg
---

# Arithmetic Operators 1

```python
## Multiplication
1 + 2 
```
```python
>>> 3
```

- In Python, we use the hash sign (`#`) to write comments.

- Everything written after a hash sign isn’t evaluated - it’s ignored.

- This method only works for one-line comments, though.

- We can also write multi-line comments.

🏠 Can you find out how to write multi-line comments in Python?

<style>
code {
    font-size: 18px;
}
</style>

---

# Arithmetic Operators 2


```python
## Subtraction
5 - 4 ## This is how we can subtract two numbers with Python
```
```python
>>> 1
```
<br>
```python
## Multiplication
2 * 5
```
```python
>>> 10
```
<br>
```python
## Division
10 / 2
```
```python
>>> 5
```

<style>
code {
    font-size: 18px;
}
</style>

---

# Arithmetic Operators 3

```python
## Be careful when attempting to divide by zero!
10 / 0
```
<br>
```python
## "Modulo" operator

10 % 2 ## This operation gives us the remainder of a division

## What is the result of the operation "9 % 2"? 
```
```python
>>> 0
```
<br>
```python
## Exponents

print(9 ** 2) ## Introducing the "print()" function
print(9 ** 3)
```
```python
>>> 81
>>> 729
```
<br>

<style>
code {
    font-size: 18px;
}
slidev-code-wrapper {
    background: "black"
}
</style>

---
layout: center
class: text-center
---

# Learn More

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
