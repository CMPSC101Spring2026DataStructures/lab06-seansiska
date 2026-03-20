# CS101 Spring 2026 — Practice Midterm Reflection

Name: Sean Siska  
Date: 3/18/26

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I actually felt very good doing this, throughout.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

question 6 was simple but it had me stumped a little, i didnt know if the len() function counted keys along with the values.

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

When a step is positive, it goes through a and b by that value, for example range(4,10, 2) would print 4 6 8. While if there was a negative step it would count backwards, for example range(10,4,-2) would print 10 8 6

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A list can be changed but a tuple cannot, so use a list for changing data and a tuple for fixed data. A dictionary stores key value pairs while a set stores only unique values with no duplicates.

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A default parameter is when a function already has a value set if no argument is given. For example, def greet(name="sean"): print(name) will print "sean" if no name is passed, because it uses the default value.

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [n * 2 for n in range(1,11)
    if n % 3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

It evaluates from right to left, so first do 2^3 = 8 then 2 ^8 = 256, so the answer is 256.

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

Classes are blueprints for creating programs that store data and functions together. They are necessary because they help organize code and make it easier to reuse and use larger programs.

---

(Did you remember to add your name and date at the top of this document?)
