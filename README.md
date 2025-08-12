# Python Strings

A well-structured Jupyter Notebook exploring Python’s string type in depth — from the fundamentals to advanced manipulation techniques.  
Includes hands-on code examples, method demonstrations, and real-world use cases.

---

## Features
- **Foundations** – creation, indexing, slicing, immutability
- **Methods Reference** – most-used string functions with examples
- **Formatting Techniques** – f-strings, `.format()`, `%` formatting
- **Advanced Use Cases** – regex, text parsing, validation
- **Encoding** – working with UTF-8, ASCII

---

## Example
```python
name = "Srinivas"
greeting = f"Hello, {name.upper()}!"
print(greeting)  
# Output: Hello, SRINIVAS!
```
## String Methods Reference

| Method          | Description                                   | Example                           |
| --------------- | --------------------------------------------- | --------------------------------- |
| `upper()`       | Converts to uppercase                         | `"abc".upper()` → `"ABC"`         |
| `lower()`       | Converts to lowercase                         | `"ABC".lower()` → `"abc"`         |
| `strip()`       | Removes whitespace from both ends             | `"  hi  ".strip()` → `"hi"`       |
| `replace(a, b)` | Replaces `a` with `b` in the string           | `"hi".replace("i", "o")` → `"ho"` |
| `split()`       | Splits into list by spaces or given separator | `"a,b".split(",")` → `['a', 'b']` |
| `join()`        | Joins iterable into string with separator     | `"-".join(['a','b'])` → `"a-b"`   |
| `find()`        | Finds index of substring (-1 if not found)    | `"hello".find("e")` → `1`         |
| `startswith()`  | Checks if string starts with given substring  | `"hi".startswith("h")` → `True`   |
| `endswith()`    | Checks if string ends with given substring    | `"hi".endswith("i")` → `True`     |
