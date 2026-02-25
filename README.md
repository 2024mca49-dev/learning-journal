# Learning Journal

**Name:** Supraja R  
**Goal:** Build AI-powered apps and land a developer job by April 2026  
**Started:** Feb 17, 2025  

---

## Week 1 — Python Fundamentals + Setup

### Day 1 ✅ Feb 17
- [x] GitHub repo created and first commit pushed
- [x] GitHub Copilot + Copilot Chat installed in VS Code
- [x] 30-Days Python Day 1 — Python basics, math operations, data types
- [x] Learned: `print()`, `type()`, basic arithmetic, int, float, str, bool, list
- [x] Key insight: Python starts counting from 0

### Day 2 ✅ Feb 18
- [x] 30-Days Python Day 2 — Variables, built-in functions, casting
- [x] 30-Days Python Day 3 — Operators, Booleans, comparisons, logical operators
- [x] Read Claude API docs — Intro + Quickstart
- [x] Learned: variables, `len()`, `input()`, `int()`, `float()`, `str()`, `==`, `!=`, `and`, `or`, `not`, `in`
- [x] Key insight: `input()` always returns string → use `int(input())` for numbers
- [x] Key insight: Comparison operators return `True/False` — foundation for API logic
- [x] Understood: API key, messages structure, models (Opus/Sonnet/Haiku)

### Day 3 ✅ Feb 19
- [x] 30-Days Python Day 4 — Strings (concatenation, slicing, f-strings, methods)
- [x] 30-Days Python Day 5 — Lists (indexing, slicing, append, extend, remove, pop)
- [x] Used Copilot Chat to understand my MCA scanner.py file
- [x] Learned Strings: `.strip()`, `.split()`, `.replace()`, `.join()`, f-strings, string indexing `[0]`, slicing `[0:3]`, `[::-1]`
- [x] Learned Lists: `.append()`, `.extend()`, `.remove()`, `.pop()`, `.sort()`, `.reverse()`, `.count()`, `.index()`, list slicing, `in` operator
- [x] Key insight: f-strings are THE way to format — `f"Hello {name}"` — will use for API responses
- [x] Key insight: `.strip()` cleans whitespace — critical for user input and API data
- [x] Key insight: `.split()` converts strings to lists — essential for parsing API responses
- [x] Key insight: Lists are mutable (can change), strings are immutable (cannot change)

### Day 4 ✅ Feb 20
- [x] 30-Days Python Day 6 — Tuples (immutable sequences, unpacking)
- [x] 30-Days Python Day 7 — Sets (unique items, union, intersection, difference)
- [x] 30-Days Python Day 8 — Dictionaries (key-value pairs, nested dicts, JSON structure)
- [x] Read MDN Web Docs — "How the Web Works" + "What is an API?"
- [x] Learned Tuples: immutable, `.count()`, `.index()`, unpacking, when to use (coordinates, config)
- [x] Learned Sets: `add()`, `update()`, `remove()`, `discard()`, `union()`, `intersection()`, `difference()`, `symmetric_difference()`
- [x] Learned Dictionaries: `[]` vs `.get()`, `.keys()`, `.values()`, `.items()`, nested access, safe key checking with `in`
- [x] **CRITICAL:** Understood that API responses are dictionaries — `response["content"][0]["text"]`
- [x] **CRITICAL:** Understood client/server model and HTTP request/response cycle
- [x] **CRITICAL:** Understood JSON = Python dictionary
- [x] Key insight: Use `.get()` for safe API response parsing
- [x] Key insight: Sets remove duplicates automatically — `set(list_with_dupes)`
- [x] Key insight: Tuples protect data from accidental changes (API config, credentials)
- [x] Advanced: Chained set operations for complex data filtering (production-level logic)
- [x] Advanced: Nested dictionary navigation — ready for real API responses

### Day 5 ✅ Feb 21
- [x] 30-Days Python Day 11 — Functions (definition, parameters, return values)
- [x] Built 5 functions from scratch WITHOUT Copilot
- [x] Learned: `def`, parameters, `return`, default parameters, keyword arguments
- [x] Functions created: circle area calculator, acronym maker, email validator, duplicate remover, API text extractor
- [x] Key insight: Functions make code reusable — write once, use everywhere
- [x] Key insight: `return` gives you data to use, `print()` just displays
- [x] Key insight: `.get()` works one level at a time for nested dictionaries
- [x] **CRITICAL:** Can now write functions that process API responses
- [x] **CRITICAL:** Built muscle memory by coding without AI assistance

### Day 6 ✅ Feb 24 (Week 2 Day 1)
- [x] 30-Days Python Day 10 — Loops (for, while, break, continue, range)
- [x] Completed 7 loop challenges including nested loops and API response processing
- [x] Learned: `for` loop through lists/dicts/strings, `while` loop, `range()`, `break`, `continue`
- [x] Built: Triangle pattern generator, multiplication table, even number filter, sum accumulator
- [x] **CRITICAL:** API response processing loop — filtered valid responses, calculated total tokens, found max
- [x] Key insight: Loops are how you process multiple API responses
- [x] Key insight: Accumulator pattern (sum += value) is fundamental
- [x] Key insight: Nested loops for 2D data structures
- [x] Advanced: Used `end=""` in print for same-line output
---
