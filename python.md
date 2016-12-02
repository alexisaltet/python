`python`

## 1. Basics
### 1.1 The format method  

The `format` method substitutes each argument value into the place of the specification.

    name = 'John'
    age = 20

    print('{0} is {1}'.format(name, age)) # The numbers are optional

 **Output:**

    John is 20



We can achieve the same using string concatenation:

    name = 'John'
    age = 20

    print name + ' is ' + str(age)

 **Output:**

    John is 20


<br>
<br>

## 2. Conditionals & Control Flow

### 2.1 Boolean operators

#### `and`
The boolean operator `and` returns `True` when
the expressions on both sides of `and` are true.


**Example:**  
`1 < 2 and 2 < 3`  is `True`  
`1 < 2 and 2 > 3`  is `False`

---

#### `or`
The boolean operator `or` returns `True` when
at least one expression on either side of `or` is true.

**Example:**  
`1 < 2 or 2 > 3` is `True`  
`1 > 2 or 2 > 3` is `False`

---

#### `not`
The boolean operator `not` returns `True` for
false statements and `False` for true statements.

**Example**  
`not False` will evaluate to `True`  
`not 41 > 40` will return `False`

---

##### Control flow  
Boolean operators aren't just evaluated from left to right.  
Just like with arithmetic operators, there's an order of operations
for boolean operators.  
1. `not` is evaluated first  
2. `and` is evaluated next  
3. `or` is evaluated last

>Parentheses `()` ensure your expressions are evaluated in the order you want.  
Anything in parentheses is evaluated as its own unit.



### 2.2 Conditional statements
