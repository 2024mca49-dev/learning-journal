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

### Day 6 ✅ Feb 23 (Week 2 Day 1)
- [x] 30-Days Python Day 10 — Loops (for, while, break, continue, range, nested loops)
- [x] 30-Days Python Day 12 — Modules (import, creating modules, built-in modules)
- [x] Created custom module `string_utils.py` with reusable functions
- [x] Learned Loops: `for`, `while`, `range()`, `break`, `continue`, nested loops, accumulator pattern
- [x] Learned Modules: `import`, `from...import`, `os`, `sys`, `math`, `random`, `datetime`, `json`
- [x] Built: Triangle pattern, multiplication table, API response processor
- [x] Built: Random ID generator, RGB color generator, timestamp logger, JSON parser
- [x] **CRITICAL:** Processed API responses with loops + parsed JSON (real API workflow!)
- [x] **CRITICAL:** Created reusable module structure (how real projects are organized!)
- [x] Key insight: Modules = code reusability, every library you use is a module
- [x] Key insight: `json.loads()` converts API JSON string → Python dict
- [x] Key insight: `datetime.now()` for API call logging
- [x] Advanced: Used list comprehension with `join()` for ID generation
### Day 7 ✅ Feb 24 (Week 2 Day 2)
- [x] 30-Days Python Day 13 — List Comprehension (one-line list creation with conditions)
- [x] 30-Days Python Day 14 — Higher Order Functions (lambda, map, filter, reduce)
- [x] **FIRST REAL API CALL** — Called GitHub API with `requests` library
- [x] Learned List Comprehension: `[x*2 for x in nums if x > 0]`, nested comprehension for flattening
- [x] Learned Lambda: Anonymous functions `lambda x: x**2`
- [x] Learned map(): Transform all items `map(lambda x: x.upper(), names)`
- [x] Learned filter(): Keep only matching items `filter(lambda x: x > 0, nums)`
- [x] Learned reduce(): Combine all items into one `reduce(lambda a,b: a+b, nums)`
- [x] **CRITICAL:** Made HTTP GET request to real API
- [x] **CRITICAL:** Parsed JSON response with `response.json()`
- [x] **CRITICAL:** Checked status codes (200 = success)
- [x] **CRITICAL:** Used `.get()` for safe data extraction
- [x] Built: Chained map+filter+reduce for API data processing
- [x] Built: GitHub profile data fetcher and JSON file saver
- [x] Key insight: API calls = (1) send request (2) check status (3) parse JSON (4) extract data
- [x] Key insight: List comprehension is faster and cleaner than loops
- [x] Key insight: Functional programming (map/filter/reduce) is how you process API responses at scale
- [x] Advanced: Chained 3 operations in one line (filter → map → reduce)
---
