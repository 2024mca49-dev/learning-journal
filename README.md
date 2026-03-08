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

### Day 8 ✅ Feb 26 (Week 2 Day 3)
- [x] 30-Days Python Day 17 — Exception Handling (try/except/finally, error types)
- [x] **Made first AI API call with Gemini API** — Called gemini-2.5-flash model
- [x] Learned Exception Handling: `try/except/finally`, catching specific errors, `Exception as e`
- [x] Built: Exception handlers for ValueError, ZeroDivisionError, KeyError, ConnectionError, FileNotFoundError
- [x] Built: Gemini API caller with environment variable management (.env file)
- [x] **CRITICAL:** try/except is MANDATORY for all API calls in production
- [x] **CRITICAL:** Understood API call pattern: (1) load API key (2) create client (3) send request (4) handle response
- [x] **CRITICAL:** Used `python-dotenv` to securely load API keys from environment
- [x] Key insight: Graceful error handling prevents app crashes
- [x] Key insight: Never hardcode API keys — use environment variables
- [x] Key insight: Gemini API = same pattern as any AI API (Claude, OpenAI, etc.)

### Day 9 ✅ Feb 27 (Week 2 Day 4)
- [x] 30-Days Python Day 21 — Classes and Objects (OOP, `__init__`, methods, self)
- [x] **Built CLI AI Assistant using OOP** — Interactive Gemini chatbot in terminal
- [x] **PYTHON THEORY COMPLETE!** — All essential concepts mastered
- [x] Learned Classes: `class`, `__init__`, `self`, instance variables, methods
- [x] Built: Book class with description method
- [x] Built: API Client class with call tracking and success rate calculation
- [x] Built: Student grade tracker with average and best subject finder
- [x] Built: **GeminiAssistant class** — encapsulated API client in reusable class
- [x] **CRITICAL:** Classes organize related data and functions together (encapsulation)
- [x] **CRITICAL:** Interactive loop with user input → API call → response display
- [x] **CRITICAL:** Each object has its own data (self.client stores API connection)
- [x] Key insight: Classes make code reusable — create once, use many times
- [x] Key insight: OOP pattern used in ALL production AI applications
- [x] Advanced: Built interactive CLI with while loop and exit conditions
- [x] Advanced: Wrapped external API in custom class interface

### Day 10 ✅ Feb 28 (Week 2 Day 5)
- [x] Completed Claude 101 course on Anthropic Academy (13 lessons, 1 hour)
- [x] Read FastAPI documentation — Introduction + First Steps
- [x] Reviewed Week 1-2 progress and updated learning journal
- [x] Learned FastAPI Basics: `FastAPI()`, `@app.get()`, path operations, automatic docs
- [x] **CRITICAL:** Understood FastAPI = Python functions → API endpoints
- [x] **CRITICAL:** Automatic interactive documentation at `/docs` and `/redoc`
- [x] **CRITICAL:** Path parameters `{item_id}` and query parameters `?q=value`
- [x] Key insight: Decorators `@app.get()` turn functions into API routes
- [x] Key insight: Return dictionaries → automatic JSON conversion
- [x] Key insight: Type hints (`item_id: int`) → automatic validation
- [x] Key insight: OpenAPI schema generated automatically for all endpoints
- [x] Understood: GET (fetch), POST (create), PUT (update), DELETE (delete)
- [x] Ready to build first FastAPI application on Saturday
### Day 11 ✅ Mar 1 (Week 2 - Saturday)
- [x] Built Gemini Summarizer project — AI-powered topic summarizer CLI tool
- [x] **Project Features:**
  - Takes user input (any topic)
  - Calls Gemini API for 3-point summary
  - Saves summaries to timestamped text files
  - Interactive loop with exit command
  - Full error handling (missing API key, network errors, invalid input)
- [x] **Code Organization:**
  - `GeminiSummarizer` class with 4 methods
  - Clean separation: init → get_summary → save_summary → run
  - Professional project structure with README
- [x] **Security Best Practices:**
  - API key in `.env` file (not hardcoded)
  - `.gitignore` to protect secrets
  - `python-dotenv` for environment management
- [x] **CRITICAL:** Built complete project from scratch with proper structure
- [x] **CRITICAL:** Used OOP to encapsulate functionality
- [x] **CRITICAL:** Implemented production-level error handling
- [x] Key insight: Real projects need README, .gitignore, requirements.txt
- [x] Key insight: Classes make code professional and maintainable
- [x] Key insight: Always protect API keys with environment variables
- [x] Pushed to GitHub with full documentation

### Days 12-14 ✅ Mar 2-4 (Week 3 Days 1-3)
- [x] FastAPI Tutorial — First Steps, Path Parameters, Query Parameters
- [x] FastAPI Tutorial — Request Body with Pydantic models
- [x] FastAPI Tutorial — Error Handling with HTTPException
- [x] Built 3 complete FastAPI applications (one per day)
- [x] **Monday:** Basic routes with path/query parameters
- [x] **Tuesday:** POST endpoint with JSON validation using Pydantic
- [x] **Wednesday:** Notes API with CRUD operations and 404 handling
- [x] **CRITICAL:** Understood FastAPI core: routes → Pydantic → validation → response
- [x] **CRITICAL:** Automatic interactive docs at `/docs` for testing
- [x] **CRITICAL:** Type hints = automatic validation (no manual checks!)
- [x] Key insight: Pydantic models validate data automatically
- [x] Key insight: HTTPException returns proper HTTP status codes
- [x] Key insight: FastAPI does all validation/conversion/docs for you
- [x] All apps tested successfully with interactive Swagger UI

### Days 15-16 ✅ Mar 4-5 (Week 3 Days 4-5)
- [x] Dependencies pattern in FastAPI
- [x] Set up Supabase project and PostgreSQL database
- [x] Created `notes` table with proper schema
- [x] Built complete CRUD API connected to Supabase
- [x] **5 Operations:** POST, GET (all), GET (one), PUT, DELETE
- [x] **CRITICAL:** Full backend API with real database (production-ready!)
- [x] **CRITICAL:** Learned Row Level Security (RLS) in Supabase
- [x] **CRITICAL:** Environment variables for API keys (.env)
- [x] Key insight: CRUD = foundation of all backend APIs
- [x] Key insight: Supabase = PostgreSQL + instant API
- [x] Key insight: Every app needs Create, Read, Update, Delete
- [x] All endpoints tested successfully with `/docs`
### Day 17 ✅ Mar 6 (Week 3 Day 6)
- [x] JWT Authentication implementation
- [x] POST `/register` - Create user with hashed password
- [x] POST `/login` - Returns JWT token
- [x] Protected all `/notes` endpoints with token verification
- [x] Created `users` table in Supabase
- [x] Linked notes to users (`user_email` column)
- [x] **CRITICAL:** JWT = token-based authentication (no sessions!)
- [x] **CRITICAL:** Bearer token in Authorization header
- [x] **CRITICAL:** Each user sees only their own notes
- [x] Key insight: `Depends(verify_token)` = protect any endpoint
- [x] Key insight: Password hashing prevents storing plain passwords
- [x] Key insight: Tokens expire (30 min) for security
- [x] Tested complete auth flow: register → login → get token → use protected endpoints
---

