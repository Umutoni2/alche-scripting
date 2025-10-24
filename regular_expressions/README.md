# Regular Expressions (Regex)

**Regex** (regular expressions) are patterns used to **find, match, or change text**.

---

## Basics
- `.` → any character  
- `*` → 0 or more  
- `+` → 1 or more  
- `?` → 0 or 1  
- `[]` → any character in brackets  

---

## Example

```python
import re
text = "My cat is cute"
match = re.search(r"cat", text)
print(match.group())  # Output: cat
