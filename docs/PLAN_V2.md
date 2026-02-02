# 90-Day Senior Frontend Interview Preparation Plan V2.0

**Version:** 2.0 (Enhanced Edition)  
**Target:** Sr/Lead Frontend roles at Unicorn & Top Product Companies  
**Daily Commitment:** 4.5 hours (9 Pomodoros)  
**Start Date:** ___________  
**Interview Ready Date:** Day 91

---

## Executive Summary

This plan is designed for candidates targeting **senior/lead frontend positions** at unicorn companies (Stripe, Airbnb, Vercel, etc.) and top tech firms. It addresses:

- Deep JavaScript mastery with TypeScript integration
- React ecosystem including Next.js App Router
- Data Structures & Algorithms tailored for frontend
- Frontend System Design at scale
- Modern tooling (CI/CD, Monorepos, Design Systems)
- AI-augmented development skills
- Comprehensive testing strategies
- Behavioral preparation with STAR stories

---

## Progress Tracker

| Phase | Days | Status | Score | Notes |
|-------|------|--------|-------|-------|
| Phase 1: JavaScript + TypeScript | 1-30 | [ ] Not Started | /100 | |
| Phase 2: React & Ecosystem | 31-54 | [ ] Not Started | /100 | |
| Phase 3: Testing Mastery | 55-58 | [ ] Not Started | /100 | |
| Phase 4: DSA for Frontend | 59-74 | [ ] Not Started | /100 | |
| Phase 5: System Design | 75-86 | [ ] Not Started | /100 | |
| Phase 6: Mock & Polish | 87-90 | [ ] Not Started | /100 | |

**Overall Readiness:** [ ] Not Ready | [ ] Partially Ready | [ ] Interview Ready

---

## Daily Structure (Pomodoro-Aligned)

Each day = **4.5 hours** = **9 Pomodoros** (25 min work + 5 min break)

```
Session 1-2 (50 min): Morning Study - Concepts & Theory
  [5 min break]
Session 3-4 (50 min): Deep Study - Advanced Topics
  [15 min LONG BREAK]
Session 5-6 (50 min): Afternoon Practice - Coding/Implementation
  [5 min break]
Session 7-8 (50 min): Hands-on Practice - Problem Solving
  [15 min LONG BREAK]
Session 9 (25 min): Evening Review - Notes & Reflection
```

**Tomato Tracking:** Mark completed sessions daily: [ ][ ][ ][ ] | [ ][ ][ ][ ] | [ ]

---

## AI-Augmented Learning Protocol

Throughout this plan, integrate AI tools to **enhance** (not replace) learning:

### Tools to Use
- **Claude/ChatGPT:** Explain concepts, generate practice problems, review code
- **GitHub Copilot:** Practice with AI pair programming during coding exercises
- **Cursor/Windsurf:** AI-assisted debugging and refactoring practice

### AI Integration Rules
1. **First attempt manually** - Always solve problems yourself first
2. **Use AI for explanation** - After solving, ask AI to explain alternative approaches
3. **Generate variations** - Use AI to create similar problems for extra practice
4. **Code review** - Have AI review your implementations
5. **Mock interviews** - Use AI for rapid-fire Q&A practice

### Weekly AI Skill-Building
- Week 1-4: Learn effective prompting for code generation
- Week 5-8: Practice AI-assisted debugging workflows
- Week 9-12: Integrate AI into system design discussions

---

# PHASE 1: JavaScript + TypeScript Foundations (Days 1-30)

## Week 1: Execution Model & Core Concepts (Days 1-7)

### Day 1: Event Loop & Execution Context
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Study**
- How JavaScript executes code (call stack)
- Execution context (global, function, eval)
- Variable Environment vs Lexical Environment
- Event loop phases: Call Stack -> Microtask Queue -> Macrotask Queue

**Sessions 3-4: Deep Dive**
- `setTimeout` vs `Promise` timing differences
- Microtasks: Promise.then, queueMicrotask, MutationObserver
- Macrotasks: setTimeout, setInterval, setImmediate, I/O
- requestAnimationFrame positioning

**Resources:**
- Jake Archibald's "In The Loop" talk (YouTube) - MUST WATCH
- JavaScript.info: Event Loop chapter
- Lydia Hallie's JavaScript Visualized series

**Sessions 5-6: Practice**
- 15 output prediction problems (event loop)
- Create mental model diagram of event loop
- AI Practice: Ask Claude to generate 5 tricky event loop questions

**Sessions 7-8: Implementation**
- Implement simple task scheduler
- Debug 5 async timing bugs
- Predict output of 10 mixed Promise/setTimeout code blocks

**Session 9: Review**
- Write 5 key insights in notes
- Note confusing parts for tomorrow
- Update progress tracker

**Deliverable:** Can predict output of mixed async code with 90%+ accuracy

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 2: Event Loop Deep Dive + TypeScript Setup
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Advanced Concepts**
- `process.nextTick` vs `setImmediate` (Node.js)
- `queueMicrotask` API and use cases
- Starvation scenarios (microtask flooding)
- Render blocking and long tasks

**Sessions 3-4: TypeScript Introduction**
- Why TypeScript matters for senior roles
- Setting up TypeScript environment
- Basic types: string, number, boolean, array, tuple
- Type inference and type annotations
- Union types and literal types

**Resources:**
- TypeScript Handbook (official docs)
- Matt Pocock's TypeScript tutorials

**Sessions 5-6: Coding**
- Implement custom `queueMicrotask` polyfill
- Build a simple Promise.resolve
- Convert 5 JS functions to TypeScript

**Sessions 7-8: Practice**
- Solve 15 output prediction problems
- Add types to event loop examples
- Practice explaining event loop aloud (record yourself)

**Session 9: TEST CHECKPOINT**
- Self-test: 10 rapid-fire event loop questions
- Target: 8/10 minimum
- If <8/10, schedule Day 2.5 for review

**Blocker:** Score <8/10 requires review day

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 3: Scope, Hoisting, TDZ
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Study**
- Lexical scope vs dynamic scope
- Scope chain resolution algorithm
- How JavaScript resolves variable names
- Closure creation during scope chain

**Sessions 3-4: Hoisting Deep Dive**
- Hoisting mechanism (var, let, const, function, class)
- Temporal Dead Zone (TDZ) - why it exists
- Block scope vs function scope
- `var` in loops (the classic bug)

**Sessions 5-6: Practice**
- 25 output prediction problems (scope/hoisting)
- Fix 10 scope-related bugs
- Explain hoisting to yourself aloud

**Sessions 7-8: TypeScript Integration**
- TypeScript's block-scoped behavior
- `const` assertions
- Type narrowing in different scopes
- Add strict types to scope examples

**Session 9: Create Cheat Sheet**
- var vs let vs const (complete comparison table)
- Hoisting rules with code examples
- TDZ visualization diagram

**Deliverable:** Scope/hoisting cheat sheet created

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 4: Closures (Part 1)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Study**
- What is a closure? (formal definition)
- How closures are created (lexical environment reference)
- Closure memory model visualization
- When closures are NOT created

**Sessions 3-4: Use Cases**
- Data privacy and encapsulation
- Function factories
- Partial application basics
- Module pattern (IIFE)
- Classic loop + setTimeout bug (3 solutions)

**Resources:**
- MDN: Closures (complete guide)
- "You Don't Know JS: Scope & Closures" (Chapter 5)

**Sessions 5-6: Coding**
- Fix var/setTimeout bug (3 different ways: let, IIFE, bind)
- Create private counter with increment/decrement/reset
- Implement `once()` function
- Build ID generator using closures

**Sessions 7-8: TypeScript + Closures**
- Type function factories
- Generic closures
- Type the private counter
- Understand closure type inference

**Session 9: Explain**
- Record yourself explaining closures (2 min max)
- Listen back - check for clarity
- Note areas to improve

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 5: Closures (Part 2) + Testing
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Advanced Patterns**
- Partial application (detailed)
- Currying with closures
- Memoization fundamentals
- Closure-based state machines

**Sessions 3-4: Memory & Performance**
- Closure memory implications
- Memory leaks from closures
- When to avoid closures
- Garbage collection with closures

**Sessions 5-6: Implementations**
- Implement `memoize` function (single argument)
- Build cache with TTL using closures
- Implement `partial` function
- Create rate limiter with closure

**Sessions 7-8: Problem Solving**
- Solve 5 LeetCode-style closure problems
- Implement `createCounter` variations
- Build event emitter with closures

**Session 9: TEST CHECKPOINT**
- Closure implementation test
- Must demonstrate: once, memoize, counter, partial
- Explain memory implications

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 6: `this` Binding (Critical Topic)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: The 4 Rules**
- Default binding (strict vs non-strict mode)
- Implicit binding (method calls, dot notation)
- Explicit binding (call, apply, bind)
- `new` binding (constructor calls)

**Sessions 3-4: Special Cases**
- Arrow functions (lexical `this`)
- Precedence rules (which binding wins?)
- Lost binding scenarios
- `this` in callbacks

**Resources:**
- "You Don't Know JS: this & Object Prototypes" (Chapters 1-2)
- Tyler McGinnis: "JavaScript this Keyword" article

**Sessions 5-6: Practice**
- 30 "what is `this`?" prediction problems
- Fix 10 context-loss bugs
- Convert between regular and arrow functions
- Implement scenarios for each binding type

**Sessions 7-8: TypeScript & `this`**
- `this` parameter in TypeScript
- `ThisType<T>` utility type
- Typing methods correctly
- `this` in class methods

**Session 9: Create Reference**
- `this` determination flowchart
- All binding rules with TypeScript examples
- Common pitfalls checklist

**CRITICAL:** This is typically a weak area - invest extra focus

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 7: `this` Deep Dive + Implementation
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Polyfill Implementations**
- Implement `Function.prototype.bind` from scratch
- Handle edge cases (new with bound function)
- Implement `Function.prototype.call`
- Implement `Function.prototype.apply`

**Sessions 3-4: `new` Operator Deep Dive**
- How `new` operator works step-by-step
- Implement `new` operator behavior
- Constructor return values
- `new.target` meta-property

**Sessions 5-6: Real-World Scenarios**
- Fix callback context bugs in React patterns
- Event handler `this` binding
- Timer callback context
- Class method binding patterns

**Sessions 7-8: TypeScript Typing**
- Type the bind/call/apply implementations
- Generic `this` typing
- Type-safe method extraction
- Typing event handlers

**Session 9: TEST CHECKPOINT**
- Implementation test: bind, call, apply, new
- Prediction test: 10 `this` scenarios
- Target: 9/10 - this is critical

**Blocker:** Score <9/10 requires extra day

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 2: Prototypes & OOP (Days 8-14)

### Day 8: Prototypes (Part 1)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Core Concepts**
- `__proto__` vs `prototype` (the critical difference)
- Prototype chain traversal
- Property lookup algorithm
- `[[Prototype]]` internal slot

**Sessions 3-4: Object Creation**
- Constructor functions
- `Object.create()` - direct prototype setting
- `Object.getPrototypeOf()` and `Object.setPrototypeOf()`
- Prototype chain length and performance

**Resources:**
- MDN: Inheritance and the prototype chain
- JavaScript.info: Prototypes (complete section)

**Sessions 5-6: Practice**
- Trace prototype chains in 15 examples
- Create objects with `Object.create()`
- Build inheritance without classes
- Draw prototype chain diagrams

**Sessions 7-8: TypeScript**
- Interface inheritance vs prototype
- `extends` in TypeScript
- Typing prototype methods
- Constructor types

**Session 9: Documentation**
- Create prototype chain visualization tool
- Document all prototype methods

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 9: Prototypes (Part 2)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Advanced Concepts**
- Adding methods to prototypes (pros/cons)
- Prototype pollution attacks (security)
- `hasOwnProperty` vs `in` operator
- `instanceof` operator internals

**Sessions 3-4: Native Prototypes**
- Extending native prototypes (why not to)
- Polyfilling safely
- Symbol.toStringTag
- Object.prototype methods

**Sessions 5-6: Implementations**
- Implement `Object.create()` polyfill
- Implement `instanceof` from scratch
- Implement `new` operator behavior
- Create deep inheritance chain (3+ levels)

**Sessions 7-8: Complex Scenarios**
- Prototype chain with mixins
- Multiple inheritance patterns
- Diamond problem in JS
- Composition over inheritance

**Session 9: Diagrams**
- Draw complex prototype chains
- Document inheritance patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 10: ES6 Classes & Inheritance
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Class Syntax**
- Class as syntactic sugar (what it compiles to)
- Constructor method
- Instance methods vs prototype methods
- Static methods and properties

**Sessions 3-4: Advanced Class Features**
- `extends` keyword and `super`
- Private fields (`#field`) - true privacy
- Public class fields
- Getters and setters
- Static initialization blocks

**Sessions 5-6: Practice**
- Convert 5 constructor functions to classes
- Implement inheritance with extends
- Use private fields
- Build real-world class hierarchy (e.g., Shape -> Rectangle -> Square)

**Sessions 7-8: TypeScript Classes**
- Access modifiers (public, private, protected)
- Abstract classes
- Implementing interfaces
- Readonly properties
- Parameter properties

**Session 9: Comparison**
- Class vs constructor function (complete comparison)
- When to use each
- TypeScript class best practices

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 11: Object Mastery
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Property Descriptors**
- Property attributes: writable, enumerable, configurable
- `Object.defineProperty()` deep dive
- `Object.defineProperties()`
- Getting descriptors

**Sessions 3-4: Object Operations**
- `Object.freeze()` - shallow freeze
- `Object.seal()` - prevent add/delete
- `Object.preventExtensions()`
- Deep freeze implementation
- Computed property names

**Sessions 5-6: Coding**
- Implement deep clone (handle circular references)
- Implement deep freeze
- Build reactive object with getters/setters
- Object validation with descriptors

**Sessions 7-8: TypeScript Object Types**
- Index signatures
- Record type
- Mapped types basics
- Readonly and Partial utilities
- Object destructuring with types

**Session 9: Patterns**
- Immutability patterns comparison
- When to use freeze vs seal
- Performance implications

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 12: TypeScript Advanced Types (Day 1)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Union & Intersection**
- Union types (`|`) - either/or
- Intersection types (`&`) - combine
- Type narrowing techniques
- Discriminated unions (tagged unions)

**Sessions 3-4: Generics Foundations**
- Why generics matter
- Generic functions
- Generic constraints (`extends`)
- Multiple type parameters
- Default type parameters

**Sessions 5-6: Practice**
- Implement generic `identity` function
- Create type-safe `pick` function
- Build generic data structures (Stack, Queue)
- Type event emitter with generics

**Sessions 7-8: Utility Types**
- `Partial<T>`, `Required<T>`
- `Pick<T, K>`, `Omit<T, K>`
- `Record<K, T>`
- `ReturnType<T>`, `Parameters<T>`

**Session 9: Reference**
- Create utility types cheat sheet
- Document common generic patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 13: TypeScript Advanced Types (Day 2)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Conditional Types**
- Basic conditional types (`T extends U ? X : Y`)
- `infer` keyword
- Distributive conditional types
- Utility type implementations

**Sessions 3-4: Template Literal Types**
- Basic template literals
- String manipulation types
- Pattern matching with templates
- Real-world use cases

**Sessions 5-6: Practice**
- Implement `MyPick<T, K>` from scratch
- Implement `MyOmit<T, K>`
- Implement `DeepReadonly<T>`
- Build type-safe API response handler

**Sessions 7-8: Advanced Patterns**
- Function overloads
- Type guards (custom)
- Assertion functions
- `as const` assertions

**Session 9: OOP Testing**
- Self-test on prototypes, classes, TypeScript
- Review weak areas
- Update progress tracker

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 14: Week 2 Review + Consolidation
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Review**
- Redo difficult problems from Days 8-13
- Fill conceptual gaps
- Create consolidated notes
- Practice explaining concepts

**Sessions 5-6: Coding Challenge**
- Build complete OOP system with:
  - Inheritance hierarchy
  - TypeScript strict typing
  - Private/protected members
  - Factory pattern

**Sessions 7-8: Implementation Test**
- Implement Object.create, instanceof, new
- Type complex object hierarchies
- Solve 5 prototype chain problems

**Session 9: PHASE CHECKPOINT TEST**
- Prototype + TypeScript comprehensive test
- Target: 85%+
- Document areas for future review

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 3: Async Patterns & Performance (Days 15-21)

### Day 15: Callbacks & Promises Fundamentals
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Callbacks**
- Callback pattern
- Callback hell / pyramid of doom
- Error-first callback convention (Node.js)
- Inversion of control problem

**Sessions 3-4: Promise Fundamentals**
- Promise states: pending, fulfilled, rejected
- Promise resolution and rejection
- `then()`, `catch()`, `finally()` - complete behavior
- Promise chaining mechanics

**Resources:**
- JavaScript.info: Promises (complete section)
- "Exploring JS: Promises" chapter

**Sessions 5-6: Practice**
- Convert 10 callback functions to promises
- Chain promises correctly
- Handle errors in promise chains
- Understand `fetch` behavior (404 is not rejection)

**Sessions 7-8: TypeScript Promises**
- `Promise<T>` typing
- Async function return types
- Error typing in promises
- Generic promise utilities

**Session 9: Patterns**
- Callback vs Promise comparison
- When promises are overkill
- Anti-patterns to avoid

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 16: Promise APIs & Implementation
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Static Methods**
- `Promise.all()` - parallel, fail-fast
- `Promise.race()` - first settled wins
- `Promise.allSettled()` - all results regardless
- `Promise.any()` - first fulfilled wins

**Sessions 3-4: Edge Cases**
- Empty array behavior for each method
- Error handling differences
- Performance characteristics
- Real-world selection criteria

**Sessions 5-6: Implementations**
- Implement `Promise.all()` from scratch
- Implement `Promise.race()` from scratch
- Implement `Promise.allSettled()` from scratch
- Handle edge cases properly

**Sessions 7-8: Advanced**
- Add timeout wrapper for promises
- Implement retry with configurable attempts
- Build promise queue with concurrency limit
- Type all implementations in TypeScript

**Session 9: Documentation**
- When to use each Promise API (decision tree)
- Implementation notes

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 17: Async/Await Mastery
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Fundamentals**
- async/await as syntactic sugar
- How async functions work internally
- Return values of async functions
- Error handling with try-catch-finally

**Sessions 3-4: Patterns**
- Sequential execution with await
- Parallel execution (Promise.all + await)
- Mixed patterns
- Top-level await (ES2022)
- Async iteration (for-await-of)

**Sessions 5-6: Practice**
- Convert promise chains to async/await
- Implement proper error handling
- Sequential API calls
- Parallel API calls with error handling
- Process array items sequentially

**Sessions 7-8: Common Pitfalls**
- Await in loops (sequential vs parallel)
- Missing await bugs
- Error swallowing
- Unhandled rejections
- TypeScript async patterns

**Session 9: Best Practices**
- When to use .then() vs async/await
- Error handling patterns
- Readability guidelines

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 18: Advanced Async Patterns
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Concurrency Control**
- Sequential promise execution (why and how)
- Parallel with concurrency limit (critical pattern)
- Request queue management
- Priority queues

**Sessions 3-4: Resilience Patterns**
- Retry with exponential backoff
- Circuit breaker pattern
- Timeout patterns
- Fallback strategies

**Sessions 5-6: Implementations**
- Build API client with retry logic
- Implement rate-limited API caller
- Create async task scheduler
- Build concurrent request pool

**Sessions 7-8: Race Conditions**
- Identify race conditions in async code
- Prevent race conditions (abort, cancel, ignore)
- AbortController usage
- Request deduplication

**Session 9: Review**
- Common async bugs checklist
- Prevention strategies

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 19: Debounce & Throttle (Critical)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Concepts**
- Debouncing: wait for silence (last call wins)
- Throttling: limit execution rate (first call wins)
- Visual timeline comparison
- Use cases for each

**Sessions 3-4: Implementation Details**
- Leading vs trailing edge
- Immediate execution option
- Cancel and flush methods
- Max wait time

**CRITICAL:** This topic requires deep understanding - common interview question

**Sessions 5-6: Implementations**
- Implement debounce (basic)
- Add leading/trailing options
- Add cancel method
- Implement throttle (basic)
- Add leading/trailing options
- Add cancel method

**Sessions 7-8: Real-World Usage**
- Debounce search input
- Throttle scroll handler
- Throttle resize handler
- Debounce form validation
- TypeScript implementations

**Session 9: Comparison**
- Debounce vs throttle decision tree
- Performance testing
- Edge cases documentation

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 20: Memoization & Caching
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Memoization Concepts**
- What is memoization?
- When it helps vs hurts
- Cache key generation
- Cache invalidation

**Sessions 3-4: LRU Cache**
- LRU (Least Recently Used) algorithm
- Implementation approaches
- Time complexity requirements
- Space complexity trade-offs

**Sessions 5-6: Implementations**
- Simple memoize (single argument)
- Memoize with multiple arguments (key serialization)
- Implement LRU Cache (O(1) get/put)
- Memoize with TTL (time-to-live)
- Memoize async functions

**Sessions 7-8: Practice**
- Fibonacci with memoization
- API response caching
- Computed value caching
- TypeScript generic memoize

**Session 9: Trade-offs**
- Memory vs computation trade-off
- When NOT to memoize
- Cache size strategies

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 21: Memory Management
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Garbage Collection**
- JavaScript memory model
- Mark-and-sweep algorithm
- Reference counting (historical)
- Generational garbage collection

**Sessions 3-4: Memory Leaks**
- Closure-based leaks
- Timer leaks (setInterval)
- DOM reference leaks
- Event listener leaks
- Circular references

**Sessions 5-6: WeakMap & WeakSet**
- Why weak references matter
- WeakMap use cases (private data, caching)
- WeakSet use cases (object marking)
- Differences from Map/Set
- Cannot iterate (and why)

**Sessions 7-8: Practice**
- Identify memory leaks in 10 code samples
- Fix closure-based leaks
- Implement cache with WeakMap
- Proper cleanup patterns

**Session 9: Checklist**
- Memory leak prevention checklist
- Debugging tools overview (Chrome DevTools Memory tab)

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 4: Functional Programming (Days 22-28)

### Day 22: FP Foundations
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Core Principles**
- Pure functions (deterministic, no side effects)
- Immutability (why it matters)
- First-class functions
- Higher-order functions

**Sessions 3-4: Practical FP**
- Function composition
- Point-free style
- Declarative vs imperative
- Referential transparency

**Resources:**
- "Functional-Light JavaScript" by Kyle Simpson (free online)
- "Professor Frisby's Mostly Adequate Guide" (free online)

**Sessions 5-6: Practice**
- Convert 10 imperative functions to pure
- Identify side effects in code
- Compose functions manually
- Write declarative array transformations

**Sessions 7-8: TypeScript FP**
- Typing higher-order functions
- Generic function composition
- Readonly types for immutability
- Tuple types

**Session 9: Patterns**
- FP benefits for testing
- FP in React (why it matters)

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 23: Array Methods Deep Dive
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Transformation Methods**
- `map` - transform each element
- `filter` - select elements
- `reduce` - accumulate to single value
- Method chaining patterns

**Sessions 3-4: Search & Check Methods**
- `find`, `findIndex`, `findLast`, `findLastIndex`
- `some`, `every`
- `includes`, `indexOf`, `lastIndexOf`
- `flat`, `flatMap`

**Sessions 5-6: Implementations**
- Implement `Array.prototype.map`
- Implement `Array.prototype.filter`
- Implement `Array.prototype.reduce`
- Implement `Array.prototype.flat` (recursive, any depth)
- Implement `Array.prototype.flatMap`

**Sessions 7-8: Performance**
- Mutation vs non-mutation methods
- Method chaining performance
- When to use `reduce` vs separate methods
- TypeScript array method typing

**Session 9: Patterns**
- Common reduce patterns (groupBy, countBy, keyBy)
- Chaining best practices

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 24: Currying & Composition
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Currying**
- What is currying?
- Currying vs partial application (difference)
- Arity and currying
- Auto-currying

**Sessions 3-4: Composition**
- Function composition (`compose`)
- Pipe (left-to-right composition)
- Composition laws
- Point-free programming

**Sessions 5-6: Implementations**
- Implement `curry` (basic)
- Add placeholder support to curry
- Implement `compose` (variadic)
- Implement `pipe` (variadic)
- Implement `partial` (left and right)

**Sessions 7-8: Practice**
- Curry existing utility functions
- Build data transformation pipelines
- Point-free refactoring
- TypeScript curry/compose typing (advanced)

**Session 9: Real-World**
- Currying in Redux (action creators)
- Composition in React (HOCs)
- When currying helps readability

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 25: ES6+ Features (Part 1)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Destructuring**
- Array destructuring (all patterns)
- Object destructuring (all patterns)
- Nested destructuring
- Default values
- Renaming in destructuring

**Sessions 3-4: Spread & Rest**
- Spread operator (arrays)
- Spread operator (objects) - shallow copy
- Rest parameters (functions)
- Rest in destructuring
- Order matters in spread

**Sessions 5-6: Practice**
- 20 destructuring problems
- Deep copy with spread (limitations)
- Function signatures with rest
- Merge objects with spread

**Sessions 7-8: Other ES6+**
- Default parameters (evaluation)
- Template literals (including tagged templates)
- Symbols (use cases: privacy, well-known symbols)
- for...of vs for...in

**Session 9: Cheat Sheet**
- ES6+ syntax quick reference
- Common patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 26: ES6+ Features (Part 2) - Iterators & Generators
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Iterators**
- Iterator protocol
- Iterable protocol
- `Symbol.iterator`
- Custom iterators
- Built-in iterables

**Sessions 3-4: Generators**
- Generator function syntax (`function*`)
- `yield` keyword
- Generator as iterator
- Two-way communication (yield/next with values)
- Generator delegation (`yield*`)

**Sessions 5-6: Implementations**
- Create custom iterator for linked list
- Implement range iterator
- Build Fibonacci generator
- Async generators (for-await-of)

**Sessions 7-8: Practical Applications**
- Generators for pagination
- Lazy evaluation with generators
- Async generators for streaming
- TypeScript generator types

**Session 9: Patterns**
- When to use generators
- Generator vs async/await

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 27: Proxy & Reflect
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Proxy Fundamentals**
- Proxy object creation
- Handler and traps
- Common traps: get, set, has, deleteProperty
- Revocable proxies

**Sessions 3-4: Reflect API**
- Why Reflect exists
- Reflect methods (mirror of Proxy traps)
- Reflect vs direct operations
- Using Reflect in Proxy handlers

**Sessions 5-6: Implementations**
- Validation proxy (type checking)
- Observable pattern with Proxy
- Property access logging
- Negative array indices
- Auto-vivification

**Sessions 7-8: Real-World**
- Vue 3 reactivity (based on Proxy)
- Proxy vs Object.defineProperty
- Performance considerations
- TypeScript and Proxy

**Session 9: Use Cases**
- When to use Proxy
- Proxy limitations

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 28: Map, Set, WeakMap, WeakSet + Error Handling
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Map & Set**
- Map vs Object (key differences)
- Set vs Array
- Map methods and iteration
- Set operations (union, intersection, difference)

**Sessions 3-4: WeakMap & WeakSet**
- Weak reference concept
- WeakMap limitations and use cases
- WeakSet limitations and use cases
- Memory management benefits

**Sessions 5-6: Error Handling**
- try-catch-finally semantics
- Error types (built-in)
- Custom error classes
- Error.cause (ES2022)
- Stack traces

**Sessions 7-8: Practice**
- Convert Object to Map scenarios
- Set operations implementation
- WeakMap for private data
- Custom error hierarchy
- Error handling in async code

**Session 9: Week 4 Review**
- Review FP concepts
- Practice weak areas
- Update progress tracker

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 5: JavaScript Advanced + Modules (Days 29-30)

### Day 29: Module Systems
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Module History**
- IIFE modules (classic)
- CommonJS (Node.js)
- AMD (RequireJS)
- UMD (Universal)

**Sessions 3-4: ES Modules**
- Named exports and imports
- Default exports and imports
- Mixed exports
- Re-exports
- Import aliases

**Sessions 5-6: Advanced Modules**
- Dynamic imports (`import()`)
- Top-level await
- Circular dependencies (handling)
- Tree shaking requirements

**Sessions 7-8: Practice**
- Convert CommonJS to ESM
- Create module with mixed exports
- Implement dynamic imports for code splitting
- Resolve circular dependency

**Session 9: Module Patterns**
- Module organization best practices
- Barrel files (index.js re-exports)

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 30: Phase 1 Final Test + Review
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Comprehensive Review**
- Review all JavaScript topics
- Redo failed test questions
- Practice implementations
- Consolidate notes

**Sessions 5-6: Coding Challenge**
- Build utility library with:
  - debounce, throttle, memoize
  - curry, compose, pipe
  - deep clone, deep freeze
  - Promise utilities
  - All in TypeScript with strict types

**Sessions 7-8: PHASE 1 FINAL TEST**
- Comprehensive JavaScript + TypeScript test
- Implementation questions
- Output prediction
- Concept explanation
- Target: 85%+

**Session 9: Gap Analysis**
- Identify remaining weak areas
- Plan remediation if needed
- Update progress tracker

**Blocker:** Score <85% requires 2-3 extra days before Phase 2

**Phase 1 Checkpoint:** [ ] Completed | Score: /100

---

# PHASE 2: React & Ecosystem (Days 31-54)

## Week 6: React Foundations (Days 31-37)

### Day 31: React Fundamentals + JSX
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: React Philosophy**
- Declarative UI paradigm
- Component-based architecture
- One-way data flow
- Virtual DOM concept

**Sessions 3-4: JSX Deep Dive**
- JSX is not HTML (it's syntax sugar)
- JSX transforms (what Babel produces)
- Expressions in JSX
- Conditional rendering patterns
- List rendering basics

**Resources:**
- Official React docs (react.dev) - READ THE NEW DOCS
- "React - The Complete Guide" (Udemy - first 4 hours)

**Sessions 5-6: Components**
- Functional components
- Class components (legacy, but know them)
- When to use each (modern: always functional)
- Component naming conventions

**Sessions 7-8: Props**
- Passing props
- Children prop
- Spread props
- Default props
- TypeScript: typing props

**Session 9: Practice**
- Build 5 basic components with TypeScript
- Compose components

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 32: State & Events
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: useState Hook**
- State concept in React
- `useState` syntax and behavior
- Lazy initialization
- State vs props

**Sessions 3-4: State Updates**
- State updates are async
- Batching in React 18
- Functional updates (prev => newState)
- Multiple state variables vs object state

**Sessions 5-6: Events**
- Event handling in React
- Synthetic events (SyntheticEvent)
- Event pooling (historical)
- Passing arguments to handlers
- TypeScript event types

**Sessions 7-8: Practice**
- Counter component (all variations)
- Form with multiple inputs
- Toggle component
- State lifting exercise

**Session 9: Patterns**
- State update patterns
- When to lift state

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 33: useEffect & Lifecycle
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Component Lifecycle**
- Mount, update, unmount phases
- Class lifecycle methods (for context)
- How useEffect maps to lifecycle

**Sessions 3-4: useEffect Deep Dive**
- Effect execution timing
- Dependency array (the rules)
- Cleanup functions (critical)
- Common pitfalls

**Sessions 5-6: Practice**
- Fetch data on mount
- Subscribe to events (with cleanup!)
- Timer with cleanup
- Window resize listener

**Sessions 7-8: Debugging Effects**
- Infinite loop causes and fixes
- Missing dependency issues
- ESLint exhaustive-deps rule
- Effect vs event handler

**Session 9: Mental Model**
- "Synchronization" mental model (not lifecycle)
- When NOT to use effects

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 34: useRef & DOM
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: useRef Hook**
- Ref vs state (when to use each)
- Accessing DOM elements
- Storing mutable values (no re-render)
- Ref current property

**Sessions 3-4: Advanced Ref Patterns**
- `forwardRef` - passing refs to children
- `useImperativeHandle` - customizing ref value
- Callback refs
- Ref cleanup (React 19)

**Sessions 5-6: Practice**
- Focus input on mount
- Measure DOM element dimensions
- Store previous value
- Scroll to element
- Video player controls

**Sessions 7-8: TypeScript Refs**
- `RefObject<T>` vs `MutableRefObject<T>`
- Typing forwardRef components
- Typing callback refs

**Session 9: Decision Tree**
- Ref vs State decision flowchart

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 35: Lists, Keys & Reconciliation
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Rendering Lists**
- map() for rendering
- Key prop (why React needs it)
- Good keys vs bad keys
- Index as key (when it's okay, when it's not)

**Sessions 3-4: Reconciliation Algorithm**
- Virtual DOM diffing
- How keys help React
- React Fiber overview
- Reconciliation heuristics

**Sessions 5-6: Practice**
- Todo list with add/remove/reorder
- Sortable list
- Filtered list (key stability)
- Pagination with lists

**Sessions 7-8: Performance**
- Avoiding re-renders in lists
- Stable keys strategies
- Large list considerations
- When to virtualize (preview)

**Session 9: Debugging**
- Key-related bugs identification
- Fix reconciliation issues

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 36: Forms & Controlled Components
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Controlled Components**
- Controlled vs uncontrolled
- Input, textarea, select
- Checkbox and radio buttons
- File inputs (uncontrolled only)

**Sessions 3-4: Form State Management**
- Single handler for multiple inputs
- Dynamic form fields
- Form validation approaches
- Error message display

**Sessions 5-6: Practice**
- Multi-field form
- Dynamic field addition/removal
- Real-time validation
- Form submission handling

**Sessions 7-8: Form Libraries (Concepts)**
- React Hook Form approach
- Formik approach
- Why form libraries exist
- TypeScript form typing

**Session 9: Patterns**
- Controlled vs uncontrolled decision
- Validation timing patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 37: React Fundamentals Test
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Review & Reinforce**
- Review Days 31-36
- Redo challenging problems
- Create summary notes

**Sessions 5-6: Build Project**
- Complete Todo App:
  - Add/edit/delete todos
  - Mark complete
  - Filter (all/active/completed)
  - Local storage persistence
  - Form validation
  - TypeScript throughout

**Sessions 7-8: CHECKPOINT TEST**
- React fundamentals test
- Explain rendering behavior
- Debug component issues
- Build feature from requirements

**Session 9: Gap Analysis**
- Identify weak areas
- Plan review if needed

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 7: Advanced React (Days 38-44)

### Day 38: Context API
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Context Fundamentals**
- Prop drilling problem
- createContext, Provider, Consumer
- useContext hook
- Default values

**Sessions 3-4: Context Patterns**
- Multiple contexts
- Context composition
- Context with reducer
- Context performance gotchas

**Sessions 5-6: Practice**
- Theme context (light/dark)
- Auth context (user state)
- Settings context
- Combine with custom hooks

**Sessions 7-8: Performance**
- Why context causes re-renders
- Context splitting strategies
- Memoization with context
- When NOT to use context

**Session 9: Patterns**
- Context design best practices
- Context vs props vs state management

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 39: Custom Hooks
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Hook Rules & Patterns**
- Rules of hooks (why they exist)
- Custom hook conventions
- Extracting logic to hooks
- Hook composition

**Sessions 3-4: Common Custom Hooks**
- `useLocalStorage`
- `useFetch` (with loading, error, data)
- `useDebounce`
- `useThrottle`

**Sessions 5-6: More Implementations**
- `useToggle`
- `usePrevious`
- `useOnClickOutside`
- `useEventListener`
- `useMediaQuery`
- `useOnScreen` (Intersection Observer)

**Sessions 7-8: TypeScript Hooks**
- Generic custom hooks
- Typing hook returns
- Overloaded hooks
- Testing custom hooks

**Session 9: Hook Library**
- Organize personal hook library
- Document each hook

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 40: Performance Optimization
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: React.memo**
- What React.memo does
- When to use it
- Custom comparison function
- Common mistakes

**Sessions 3-4: useMemo & useCallback**
- useMemo - memoize computed values
- useCallback - memoize functions
- Difference and relationship
- Dependency management

**Sessions 5-6: Practice**
- Optimize expensive list rendering
- Prevent unnecessary child re-renders
- Memoize event handlers
- Profile with React DevTools

**Sessions 7-8: Code Splitting**
- React.lazy
- Suspense for loading states
- Route-based splitting
- Component-based splitting

**Session 9: Performance Checklist**
- Optimization decision tree
- Common anti-patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 41: Advanced Patterns
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Higher-Order Components (HOC)**
- HOC pattern
- Creating HOCs
- HOC vs hooks (comparison)
- When HOCs are still useful

**Sessions 3-4: Other Patterns**
- Render props pattern
- Compound components
- Controlled vs uncontrolled pattern
- Provider pattern

**Sessions 5-6: Implementations**
- withAuth HOC
- Render prop component
- Compound Tabs component
- Controlled component with API

**Sessions 7-8: State Patterns**
- State reducer pattern
- State machine patterns
- Lifted content pattern
- Children as function

**Session 9: Pattern Selection**
- Pattern comparison and decision guide

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 42: Error Boundaries & Portals
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Error Boundaries**
- Error boundary concept
- getDerivedStateFromError
- componentDidCatch
- What errors ARE caught
- What errors are NOT caught

**Sessions 3-4: Error Handling Strategies**
- Error boundary placement
- Recovery strategies
- Error reporting
- Fallback UIs

**Sessions 5-6: Portals**
- ReactDOM.createPortal
- Portal use cases (modals, tooltips, dropdowns)
- Event bubbling through portals
- Accessibility considerations

**Sessions 7-8: Practice**
- Create reusable error boundary
- Modal with portal
- Tooltip with portal
- Toast notification system

**Session 9: Patterns**
- Error boundary strategy
- Portal patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 43: React 18+ Features
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Concurrent React**
- Concurrent rendering concept
- Automatic batching (React 18)
- Transitions concept
- What problems it solves

**Sessions 3-4: New Hooks**
- useTransition - mark updates as non-urgent
- useDeferredValue - defer expensive computations
- useId - generate unique IDs
- useSyncExternalStore (for libraries)

**Sessions 5-6: Practice**
- Search with useTransition
- Expensive filter with useDeferredValue
- isPending UI patterns
- Compare with throttle/debounce

**Sessions 7-8: Suspense**
- Suspense for code splitting (current)
- Suspense for data fetching (emerging)
- Suspense boundaries
- Loading patterns

**Session 9: React 19 Preview**
- Upcoming features overview
- Migration considerations

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 44: Advanced React Test
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Review**
- Review Days 38-43
- Practice weak areas

**Sessions 5-6: Build Project**
- E-commerce Product Filter:
  - Search with debounce
  - Category/price filters
  - Infinite scroll
  - Cart with Context
  - Performance optimizations
  - Error boundaries

**Sessions 7-8: CHECKPOINT TEST**
- Advanced React test
- Re-rendering behavior
- Performance debugging
- Pattern implementation

**Session 9: Gap Analysis**
- Document weak areas

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 8: Next.js (Days 45-51)

### Day 45: Next.js Fundamentals
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Next.js Overview**
- Why Next.js (React framework benefits)
- Pages Router vs App Router
- File-based routing
- Project structure

**Sessions 3-4: Routing Deep Dive**
- Static routes
- Dynamic routes ([id])
- Catch-all routes ([...slug])
- Route groups (App Router)
- Parallel routes

**Resources:**
- Official Next.js docs (nextjs.org/docs)
- Next.js 14 crash course

**Sessions 5-6: Practice**
- Create Next.js project (App Router)
- Build multi-page app
- Dynamic routes
- Nested layouts

**Sessions 7-8: Components**
- Link component (client navigation)
- Image component (optimization)
- next/font (font optimization)
- Metadata API

**Session 9: Configuration**
- next.config.js basics

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 46: Data Fetching (Pages Router)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Rendering Strategies**
- Static Site Generation (SSG)
- Server-Side Rendering (SSR)
- Incremental Static Regeneration (ISR)
- Client-Side Rendering (CSR)

**Sessions 3-4: Data Fetching Methods**
- getStaticProps (build time)
- getStaticPaths (dynamic SSG)
- getServerSideProps (request time)
- Fallback modes (blocking, true, false)

**Sessions 5-6: Practice**
- SSG page with getStaticProps
- Dynamic SSG with getStaticPaths
- SSR page with getServerSideProps
- ISR with revalidate

**Sessions 7-8: Client-Side**
- SWR library basics
- React Query basics
- When to fetch client-side
- Hybrid approaches

**Session 9: Decision Matrix**
- SSG vs SSR vs ISR vs CSR decision guide

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 47: App Router & Server Components
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Server Components**
- Server vs Client Components
- Default is Server Component
- 'use client' directive
- Benefits of Server Components

**Sessions 3-4: App Router Data Fetching**
- Async Server Components
- fetch() in Server Components
- Caching and revalidation
- Dynamic rendering

**Sessions 5-6: Practice**
- Fetch data in Server Component
- Mix Server and Client Components
- Streaming with loading.js
- Error handling with error.js

**Sessions 7-8: Advanced**
- Server Actions basics
- 'use server' directive
- Form handling with Server Actions
- Route Handlers (API routes)

**Session 9: Mental Model**
- Server vs Client boundary
- When to use each

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 48: API Routes & Middleware
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: API Routes**
- Pages Router: /pages/api
- App Router: Route Handlers
- Request/Response handling
- HTTP methods

**Sessions 3-4: Middleware**
- middleware.ts location and execution
- Matching paths
- Request modification
- Response modification
- Authentication patterns

**Sessions 5-6: Practice**
- RESTful API endpoints
- Auth middleware
- Redirects and rewrites
- Rate limiting concept

**Sessions 7-8: Edge Runtime**
- Edge vs Node runtime
- When to use Edge
- Limitations of Edge
- Edge middleware

**Session 9: Security**
- API security best practices
- CORS handling

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 49: Styling & Optimization
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Styling Options**
- CSS Modules
- Tailwind CSS integration
- CSS-in-JS (styled-components, emotion)
- Global styles

**Sessions 3-4: Built-in Optimization**
- next/image (automatic optimization)
- next/font (font optimization)
- next/script (script loading)
- Automatic code splitting

**Sessions 5-6: Practice**
- Style app with CSS Modules
- Add Tailwind CSS
- Optimize images
- Configure fonts

**Sessions 7-8: Performance**
- Bundle analyzer
- Lazy loading
- Prefetching
- Performance monitoring

**Session 9: Production**
- Build optimization
- Environment variables

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 50: Full Next.js Project
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Full Day Project: Blog Application**

**Sessions 1-2: Setup & Structure**
- Project setup (App Router)
- Layout structure
- TypeScript configuration

**Sessions 3-4: Core Pages**
- Home page (list posts - SSG)
- Post page (dynamic route - SSG)
- Category pages

**Sessions 5-6: Features**
- Search (client-side)
- Contact form (Server Action)
- Newsletter signup

**Sessions 7-8: Polish**
- SEO (metadata)
- Responsive design
- Image optimization
- Error boundaries

**Session 9: Review**
- Code review
- Performance check

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 51: State Management Overview
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Redux (Concepts)**
- Redux philosophy
- Actions, reducers, store
- Redux Toolkit (modern Redux)
- When Redux makes sense

**Sessions 3-4: Lighter Alternatives**
- Zustand (simple, hooks-based)
- Jotai (atomic state)
- Recoil (Facebook)
- Comparison and selection

**Sessions 5-6: Server State**
- TanStack Query (React Query)
- SWR
- Server state vs client state
- Caching strategies

**Sessions 7-8: Practice**
- Simple Zustand store
- TanStack Query for data fetching
- Combine approaches

**Session 9: Decision Guide**
- State management selection criteria

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 9: React Ecosystem + AI Integration (Days 52-54)

### Day 52: TypeScript + React Best Practices
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Component Typing**
- FC vs function components
- Props with children
- Event handler types
- Ref types

**Sessions 3-4: Advanced Typing**
- Generic components
- Discriminated union props
- Component prop polymorphism
- as prop pattern

**Sessions 5-6: Hook Typing**
- useState with types
- useReducer with discriminated unions
- Custom hook return types
- Context typing

**Sessions 7-8: Patterns**
- Type-safe event handlers
- Form handling types
- API response types
- Error boundary types

**Session 9: Checklist**
- TypeScript + React best practices summary

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 53: AI-Augmented React Development
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: AI in Frontend**
- AI assistants for React development
- Effective prompting for React code
- Code generation best practices
- Review and validation workflow

**Sessions 3-4: Practical AI Workflows**
- Component scaffolding with AI
- Test generation with AI
- Documentation with AI
- Debugging with AI assistance

**Sessions 5-6: AI-Powered Features**
- Streaming responses in UI
- Chat interfaces
- AI-generated content display
- Loading states for AI responses

**Sessions 7-8: Practice**
- Build component with AI assistance
- Generate tests with AI
- Implement streaming UI
- Code review with AI

**Session 9: Workflow Integration**
- Personal AI development workflow

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 54: Phase 2 Final Test
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Comprehensive Review**
- Review all React and Next.js
- Practice weak areas
- Consolidate notes

**Sessions 5-6: Coding Challenge**
- Build feature from requirements (timed)
- Include TypeScript, hooks, optimization
- Error handling
- Testing considerations

**Sessions 7-8: PHASE 2 FINAL TEST**
- React/Next.js comprehensive test
- Build features live
- Explain rendering, SSR/SSG
- Optimize performance
- Target: 85%+

**Session 9: Gap Analysis**
- Document areas for review
- Update progress tracker

**Phase 2 Checkpoint:** [ ] Completed | Score: /100

---

# PHASE 3: Testing Mastery (Days 55-58)

### Day 55: Testing Fundamentals
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Testing Philosophy**
- Testing pyramid (unit, integration, e2e)
- Test-driven development (TDD)
- Behavior-driven development (BDD)
- What to test, what not to test

**Sessions 3-4: Jest Fundamentals**
- Test structure (describe, it, test)
- Assertions (expect, matchers)
- Setup and teardown (beforeEach, afterEach)
- Mocking basics

**Resources:**
- Jest documentation
- Testing JavaScript with Kent C. Dodds

**Sessions 5-6: Practice**
- Test pure functions
- Test async functions
- Mock modules
- Snapshot testing (when appropriate)

**Sessions 7-8: TypeScript Testing**
- Type-safe mocks
- Testing type guards
- Generic function testing

**Session 9: Test Strategy**
- Unit test guidelines

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 56: React Testing Library
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: RTL Philosophy**
- "The more your tests resemble the way your software is used..."
- Testing behavior, not implementation
- Accessible queries priority
- User-event vs fireEvent

**Sessions 3-4: Queries**
- getBy, queryBy, findBy (differences)
- ByRole, ByLabelText, ByText priorities
- Within queries
- Debug and screen utilities

**Sessions 5-6: Practice**
- Test component rendering
- Test user interactions
- Test form submissions
- Test async behavior (waitFor, findBy)

**Sessions 7-8: Advanced**
- Testing custom hooks
- Testing context providers
- Testing error boundaries
- MSW for API mocking

**Session 9: Patterns**
- Component testing patterns

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 57: Integration & E2E Testing
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Integration Testing**
- Testing component interactions
- Testing with real providers
- API mocking with MSW
- Database mocking

**Sessions 3-4: E2E Concepts**
- Cypress overview
- Playwright overview
- When to write E2E tests
- E2E vs integration trade-offs

**Sessions 5-6: Practice**
- Integration test for form flow
- MSW handlers
- Test authentication flow
- Test error scenarios

**Sessions 7-8: E2E Practice**
- Simple Playwright/Cypress setup
- Test user journey
- Visual regression basics

**Session 9: Test Strategy**
- Complete testing strategy document

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 58: Testing Best Practices + Review
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Best Practices**
- Test organization
- Naming conventions
- DRY vs readability in tests
- Flaky test prevention

**Sessions 3-4: Coverage & CI**
- Code coverage (what it means)
- Coverage thresholds
- CI/CD integration
- Pre-commit hooks

**Sessions 5-6: Practice**
- Add tests to previous projects
- Achieve meaningful coverage
- Set up test script

**Sessions 7-8: TESTING CHECKPOINT TEST**
- Write tests for given components
- Explain testing decisions
- Debug failing tests

**Session 9: Documentation**
- Testing guidelines document

**Phase 3 Checkpoint:** [ ] Completed | Score: /100

---

# PHASE 4: DSA for Frontend (Days 59-74)

## Week 10: DSA Foundations (Days 59-65)

### Day 59: Big O & Problem-Solving Approach
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Big O Notation**
- Time complexity
- Space complexity
- Common complexities: O(1), O(log n), O(n), O(n log n), O(n²)
- Best, average, worst case

**Sessions 3-4: Problem-Solving Framework**
- Understand the problem
- Work through examples
- Break down approach
- Code solution
- Test and optimize

**Resources:**
- "Grokking Algorithms" (Chapter 1)
- NeetCode roadmap

**Sessions 5-6: Practice**
- Analyze 20 code snippets for complexity
- Optimize given solutions
- Explain trade-offs

**Sessions 7-8: TypeScript DSA Setup**
- DSA in TypeScript
- Generic data structures
- Test setup for problems

**Session 9: Reference**
- Big O cheat sheet creation

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 60: Arrays - Easy Problems
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Array Fundamentals**
- Array operations complexity
- Two-pointer technique intro
- Sliding window intro

**Sessions 3-8: LeetCode Practice (10 problems)**
- [ ] Two Sum
- [ ] Best Time to Buy and Sell Stock
- [ ] Contains Duplicate
- [ ] Valid Anagram
- [ ] Valid Palindrome
- [ ] Reverse String
- [ ] Merge Sorted Array
- [ ] Remove Duplicates from Sorted Array
- [ ] Plus One
- [ ] Move Zeroes

**Target:** <15 mins each, explain approach before coding

**Session 9: Review**
- Note patterns
- Identify weak areas

**Checkpoint:** [ ] Completed | Problems: /10

---

### Day 61: Arrays - Medium Problems
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Advanced Patterns**
- Sliding window (fixed and variable size)
- Two pointers (same and opposite direction)
- Prefix sum
- Kadane's algorithm

**Sessions 3-8: LeetCode Practice (8 problems)**
- [ ] Longest Substring Without Repeating Characters
- [ ] 3Sum
- [ ] Container With Most Water
- [ ] Product of Array Except Self
- [ ] Maximum Subarray (Kadane's)
- [ ] Group Anagrams
- [ ] Longest Palindromic Substring
- [ ] Rotate Array

**Target:** <25 mins each

**Session 9: Pattern Summary**
- Document patterns learned

**Checkpoint:** [ ] Completed | Problems: /8

---

### Day 62: Hash Tables & Sets
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Hash Table Concepts**
- Hash function basics
- Collision handling
- Map vs Object in JavaScript
- Set operations

**Sessions 3-8: LeetCode Practice (8 problems)**
- [ ] Two Sum (optimal)
- [ ] Intersection of Two Arrays
- [ ] Happy Number
- [ ] Isomorphic Strings
- [ ] Word Pattern
- [ ] Contains Duplicate II
- [ ] First Unique Character
- [ ] Design HashMap

**Session 9: Patterns**
- Hash table problem patterns

**Checkpoint:** [ ] Completed | Problems: /8

---

### Day 63: Stacks & Queues
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Concepts**
- Stack (LIFO) - implementation
- Queue (FIFO) - implementation
- Monotonic stack pattern
- Use cases

**Sessions 3-8: LeetCode Practice (8 problems)**
- [ ] Valid Parentheses
- [ ] Implement Queue using Stacks
- [ ] Min Stack
- [ ] Backspace String Compare
- [ ] Daily Temperatures
- [ ] Next Greater Element I
- [ ] Evaluate Reverse Polish Notation
- [ ] Decode String

**Session 9: Pattern Summary**
- Stack/queue decision guide

**Checkpoint:** [ ] Completed | Problems: /8

---

### Day 64: Linked Lists
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Concepts**
- Singly linked list
- Doubly linked list
- Fast & slow pointers
- Reverse pattern

**Sessions 3-8: LeetCode Practice (8 problems)**
- [ ] Reverse Linked List
- [ ] Merge Two Sorted Lists
- [ ] Linked List Cycle
- [ ] Remove Nth Node From End
- [ ] Middle of Linked List
- [ ] Palindrome Linked List
- [ ] Intersection of Two Linked Lists
- [ ] Add Two Numbers

**Session 9: Patterns**
- Linked list problem patterns

**Checkpoint:** [ ] Completed | Problems: /8

---

### Day 65: Trees - Part 1
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Tree Concepts**
- Binary tree terminology
- Traversals: inorder, preorder, postorder
- DFS vs BFS
- Level-order traversal

**Sessions 3-8: LeetCode Practice (8 problems)**
- [ ] Maximum Depth of Binary Tree
- [ ] Same Tree
- [ ] Invert Binary Tree
- [ ] Symmetric Tree
- [ ] Path Sum
- [ ] Binary Tree Level Order Traversal
- [ ] Binary Tree Inorder Traversal
- [ ] Subtree of Another Tree

**Session 9: Traversal Practice**
- Implement all traversals from memory

**Checkpoint:** [ ] Completed | Problems: /8

---

## Week 11: DSA Intermediate (Days 66-71)

### Day 66: Trees - Part 2 (BST)
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: BST Concepts**
- BST properties
- BST operations
- LCA (Lowest Common Ancestor)
- Tree construction

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Validate Binary Search Tree
- [ ] Kth Smallest Element in BST
- [ ] Lowest Common Ancestor of BST
- [ ] Binary Tree Right Side View
- [ ] Construct BST from Preorder
- [ ] Diameter of Binary Tree

**Session 9: BST Patterns**
- BST problem patterns

**Checkpoint:** [ ] Completed | Problems: /6

---

### Day 67: Recursion & Backtracking
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Recursion Patterns**
- Base case + recursive case
- Recursion tree visualization
- Backtracking template
- When to backtrack

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Subsets
- [ ] Permutations
- [ ] Combination Sum
- [ ] Generate Parentheses
- [ ] Letter Combinations of Phone Number
- [ ] Word Search

**Session 9: Templates**
- Backtracking template document

**Checkpoint:** [ ] Completed | Problems: /6

---

### Day 68: Dynamic Programming
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: DP Concepts**
- Optimal substructure
- Overlapping subproblems
- Memoization (top-down)
- Tabulation (bottom-up)

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Climbing Stairs
- [ ] House Robber
- [ ] Maximum Subarray (DP)
- [ ] Coin Change
- [ ] Longest Increasing Subsequence
- [ ] Unique Paths

**Session 9: DP Patterns**
- DP problem identification

**Checkpoint:** [ ] Completed | Problems: /6

---

### Day 69: Graphs
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Graph Concepts**
- Representations (adjacency list/matrix)
- DFS in graphs
- BFS in graphs
- Connected components

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Number of Islands
- [ ] Clone Graph
- [ ] Course Schedule
- [ ] Pacific Atlantic Water Flow
- [ ] Graph Valid Tree
- [ ] Number of Connected Components

**Session 9: Graph Patterns**
- Graph problem patterns

**Checkpoint:** [ ] Completed | Problems: /6

---

### Day 70: Binary Search
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Binary Search Patterns**
- Classic binary search
- Search space reduction
- Binary search on answer
- Rotated array patterns

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Binary Search
- [ ] First Bad Version
- [ ] Search Insert Position
- [ ] Find Peak Element
- [ ] Search in Rotated Sorted Array
- [ ] Koko Eating Bananas

**Session 9: Templates**
- Binary search template variations

**Checkpoint:** [ ] Completed | Problems: /6

---

### Day 71: Heaps & Priority Queues
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Heap Concepts**
- Min heap vs max heap
- Heap operations
- Priority queue use cases
- Top K pattern

**Sessions 3-8: LeetCode Practice (6 problems)**
- [ ] Kth Largest Element
- [ ] Top K Frequent Elements
- [ ] Merge K Sorted Lists
- [ ] Last Stone Weight
- [ ] K Closest Points to Origin
- [ ] Task Scheduler

**Session 9: Heap Patterns**
- Heap problem patterns

**Checkpoint:** [ ] Completed | Problems: /6

---

## Week 12: DSA Review & Practice (Days 72-74)

### Day 72: Mixed Practice Day 1
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Full Day: Timed Practice**

Solve 8 random medium problems (30 mins each):
- [ ] Problem 1: ___________
- [ ] Problem 2: ___________
- [ ] Problem 3: ___________
- [ ] Problem 4: ___________
- [ ] Problem 5: ___________
- [ ] Problem 6: ___________
- [ ] Problem 7: ___________
- [ ] Problem 8: ___________

**Session 9: Review**
- Analyze mistakes
- Note patterns

**Checkpoint:** [ ] Completed | Problems: /8

---

### Day 73: Mixed Practice Day 2
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Full Day: Interview Simulation**

- 2 Easy (15 mins each)
- 4 Medium (30 mins each)
- 1 Hard (45 mins)

**Session 9: Gap Analysis**
- Identify weak data structures
- Plan review

**Checkpoint:** [ ] Completed

---

### Day 74: DSA Phase Final Test
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Review**
- Review all patterns
- Redo difficult problems
- Create pattern cheat sheet

**Sessions 5-6: Timed Practice**
- Solve 4 problems under time pressure

**Sessions 7-8: PHASE 4 FINAL TEST**
- Solve 3 problems (easy, medium, medium)
- Explain approach before coding
- Analyze complexity
- Handle follow-ups

**Session 9: Documentation**
- DSA pattern reference complete

**Phase 4 Checkpoint:** [ ] Completed | Score: /100

---

# PHASE 5: Frontend System Design (Days 75-86)

## Week 13: System Design Foundations (Days 75-80)

### Day 75: System Design Introduction
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Frontend System Design**
- What is frontend system design?
- Differences from backend system design
- Interview format and expectations
- Evaluation criteria

**Sessions 3-4: Framework**
- Requirements gathering (functional, non-functional)
- Clarifying questions template
- Component architecture basics
- API design basics

**Resources:**
- GreatFrontEnd System Design Guidebook
- Frontend Masters: Enterprise Architecture

**Sessions 5-6: Practice**
- Watch 2 system design interviews
- Create requirements template
- Practice clarifying questions

**Sessions 7-8: Case Study**
- Analyze existing system (Twitter/X feed)
- Identify components, state, data flow

**Session 9: Template**
- Create personal system design template

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 76: Component Architecture & State
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Component Design**
- Component hierarchy principles
- Container vs presentational
- Atomic design concepts
- Component composition

**Sessions 3-4: State Management**
- When to use what (local, context, global)
- Client state vs server state
- State normalization
- Derived state

**Sessions 5-6: Practice Design**
- E-commerce product page
- Social media feed
- Admin dashboard

**Sessions 7-8: Deep Dive**
- Component tree diagrams
- State flow diagrams
- Prop drilling analysis

**Session 9: Patterns**
- Component architecture patterns document

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 77: Data Fetching & Caching
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Fetching Strategies**
- Fetch on mount
- Prefetching
- Lazy loading data
- Background refresh

**Sessions 3-4: Caching Strategies**
- In-memory cache
- LocalStorage/IndexedDB
- Cache invalidation
- Stale-while-revalidate

**Sessions 5-6: Real-Time**
- Polling
- WebSockets
- Server-Sent Events
- When to use each

**Sessions 7-8: Practice Design**
- News feed with infinite scroll
- Real-time chat data layer
- Dashboard with live data

**Session 9: Decision Guide**
- Data fetching decision tree

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 78: Performance & Optimization
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Performance Metrics**
- Core Web Vitals (FCP, LCP, CLS, FID/INP)
- Time to Interactive (TTI)
- Total Blocking Time (TBT)
- Measurement tools

**Sessions 3-4: Optimization Techniques**
- Code splitting
- Lazy loading (routes, components, images)
- Virtualization (windowing)
- Bundle optimization

**Sessions 5-6: Critical Path**
- Critical rendering path
- Resource prioritization
- Preload, prefetch, preconnect
- Above-the-fold optimization

**Sessions 7-8: Practice**
- Optimize previous designs
- Identify bottlenecks
- Propose improvements

**Session 9: Checklist**
- Performance optimization checklist

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 79: Accessibility & Responsive Design
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Accessibility**
- WCAG guidelines (A, AA, AAA)
- Semantic HTML
- ARIA roles and attributes
- Keyboard navigation

**Sessions 3-4: Screen Readers**
- Screen reader behavior
- Focus management
- Live regions
- Form accessibility

**Sessions 5-6: Responsive Design**
- Mobile-first approach
- Breakpoint strategies
- Touch vs mouse
- Responsive images

**Sessions 7-8: Practice**
- Add accessibility to designs
- Plan responsive layouts
- Document a11y requirements

**Session 9: A11y Checklist**
- Accessibility checklist

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 80: Security & Error Handling
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Frontend Security**
- XSS prevention
- CSRF protection
- Content Security Policy
- Secure cookies

**Sessions 3-4: Authentication**
- JWT tokens
- OAuth flow
- Session management
- Authorization patterns

**Sessions 5-6: Error Handling**
- Error boundaries
- API error handling
- Retry logic
- Fallback strategies
- Graceful degradation

**Sessions 7-8: Practice**
- Design auth flow
- Plan error handling
- Security checklist

**Session 9: Security Checklist**
- Security best practices document

**Checkpoint:** [ ] Completed | Score: /10

---

## Week 14: Real-World System Design (Days 81-86)

### Day 81: Design - News Feed & Autocomplete
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: News Feed Design**
- Requirements gathering
- Component architecture
- Infinite scroll data fetching
- Virtualization
- Real-time updates
- Performance optimization

**Sessions 5-8: Autocomplete/Typeahead**
- Requirements
- Debouncing strategy
- Caching results
- Keyboard navigation
- Accessibility
- API design

**Session 9: Document**
- Both designs documented

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 82: Design - Image Gallery & Chat
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Image Gallery/Carousel**
- Requirements
- Lazy loading images
- Swipe gestures
- Keyboard controls
- Responsive design
- Performance

**Sessions 5-8: Chat Application**
- Requirements
- Real-time messaging (WebSocket)
- Message history
- Typing indicators
- Optimistic updates
- Offline support

**Session 9: Document**
- Both designs documented

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 83: Design - E-commerce & Video Player
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: E-commerce Product Listing**
- Requirements
- Filters and sorting
- URL state management
- Pagination strategies
- SEO considerations
- Performance

**Sessions 5-8: Video Player**
- Requirements
- Controls design
- Quality selection
- Subtitles/captions
- Keyboard shortcuts
- Buffering/performance

**Session 9: Document**
- Both designs documented

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 84: Design - Dashboard & Notifications
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Dashboard with Widgets**
- Requirements
- Widget library design
- Drag and drop
- Data refresh strategies
- Customization/persistence

**Sessions 5-8: Notification System**
- Requirements
- Real-time notifications
- Notification types
- Browser notifications
- Persistence
- Read/unread state

**Session 9: Document**
- Both designs documented

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 85: Modern Tooling & Architecture
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: Monorepos**
- Why monorepos
- Nx basics
- Turborepo basics
- Trade-offs

**Sessions 3-4: Design Systems**
- Design system architecture
- Component libraries
- Theming
- Documentation

**Sessions 5-6: CI/CD**
- Frontend CI pipelines
- Build optimization
- Preview deployments
- Feature flags

**Sessions 7-8: Advanced**
- Micro-frontends (concepts)
- Module federation
- When to use micro-frontends

**Session 9: Modern Architecture**
- Modern frontend architecture document

**Checkpoint:** [ ] Completed | Score: /10

---

### Day 86: System Design Final Test
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Review**
- Review all designs
- Create design template
- Pattern consolidation

**Sessions 5-6: Timed Practice**
- Design 1 system (45 mins)
- Self-evaluate

**Sessions 7-8: PHASE 5 FINAL TEST**
- Design complete system (1 hour)
- Cover: requirements, architecture, state, performance, accessibility
- Handle follow-up questions

**Session 9: Final Documentation**
- System design reference complete

**Phase 5 Checkpoint:** [ ] Completed | Score: /100

---

# PHASE 6: Mock Interviews & Polish (Days 87-90)

### Day 87: Behavioral Preparation
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: STAR Stories**
Prepare 10 stories using STAR method:
1. [ ] Leadership/ownership
2. [ ] Conflict resolution
3. [ ] Technical decision
4. [ ] Failure and learning
5. [ ] Challenging project
6. [ ] Performance optimization
7. [ ] Team collaboration
8. [ ] Tight deadline
9. [ ] Innovation
10. [ ] Customer focus

**Sessions 5-6: Practice**
- Record each story (2-3 mins max)
- Refine for clarity
- Practice conciseness

**Sessions 7-8: Company Research**
- Research target companies
- Read engineering blogs
- Understand products

**Session 9: Questions**
- Prepare questions to ask interviewers

**Checkpoint:** [ ] Completed | Stories: /10

---

### Day 88: Full Mock Interview - Technical
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Mock Interview (2 hours)**
- JavaScript fundamentals (30 mins)
- React implementation (45 mins)
- System design discussion (45 mins)

**Sessions 5-8: Post-Interview**
- Review performance
- Identify weak points
- Fix issues
- Practice improvements

**Session 9: Action Items**
- Document improvement areas

**Checkpoint:** [ ] Completed

---

### Day 89: Full Mock Interview - Full Loop
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-2: DSA Round**
- 2 problems (45 mins)

**Sessions 3-4: React Round**
- Build feature (45 mins)

**Sessions 5-6: System Design Round**
- Design system (45 mins)

**Sessions 7-8: Behavioral Round**
- STAR stories (45 mins)

**Session 9: Debrief**
- Full loop review
- Final gaps identified

**Checkpoint:** [ ] Completed

---

### Day 90: Final Review & Confidence
**Pomodoros: 9 | Tomatoes: [ ][ ][ ][ ][ ][ ][ ][ ][ ]**

**Sessions 1-4: Final Review**
- Skim all notes
- JavaScript cheat sheets
- React patterns
- System design templates
- DSA patterns

**Sessions 5-6: Light Practice**
- 5 easy problems (confidence)
- Explain 3 concepts aloud
- Review 1 system design

**Sessions 7-8: Logistics**
- Prepare interview space
- Test equipment
- Plan day-before relaxation

**Session 9: Mental Preparation**
- Visualize success
- Review accomplishments
- REST

**INTERVIEW READY! [ ]**

---

# Appendix A: Quick Reference Sheets

## JavaScript Cheat Sheet
- [ ] Event loop diagram
- [ ] Closure pattern
- [ ] `this` binding rules
- [ ] Prototype chain
- [ ] Promise methods
- [ ] Array methods
- [ ] ES6+ features

## React Cheat Sheet
- [ ] Hook rules
- [ ] Re-render triggers
- [ ] Performance patterns
- [ ] Common hooks
- [ ] Context patterns

## DSA Patterns
- [ ] Two pointers
- [ ] Sliding window
- [ ] Binary search templates
- [ ] BFS/DFS templates
- [ ] Backtracking template
- [ ] DP patterns

## System Design Template
- [ ] Requirements gathering
- [ ] Component architecture
- [ ] State management
- [ ] Data fetching
- [ ] Performance
- [ ] Accessibility
- [ ] Security

---

# Appendix B: Resource Library

## Books
- "You Don't Know JS" series (Kyle Simpson) - FREE
- "Functional-Light JavaScript" (Kyle Simpson) - FREE
- "Grokking Algorithms" (Aditya Bhargava)
- "Designing Data-Intensive Applications" (Martin Kleppmann)

## Courses
- React documentation (react.dev)
- Next.js documentation (nextjs.org)
- TypeScript Handbook
- NeetCode roadmap

## Practice
- LeetCode (DSA)
- GreatFrontEnd (frontend-specific)
- Frontend Mentor (projects)

## Videos
- Jake Archibald: "In The Loop"
- Lydia Hallie: JavaScript Visualized
- Fireship: Quick overviews
- Theo: React/Next.js

---

# Appendix C: Weekly Checkpoints

| Week | Focus | Target Score | Actual | Status |
|------|-------|--------------|--------|--------|
| 1 | Event Loop, Scope, Closures, This | 85% | | [ ] |
| 2 | Prototypes, OOP, TypeScript | 85% | | [ ] |
| 3 | Async Patterns, Performance | 85% | | [ ] |
| 4 | Functional Programming | 85% | | [ ] |
| 5 | JS Final + Modules | 85% | | [ ] |
| 6 | React Fundamentals | 85% | | [ ] |
| 7 | Advanced React | 85% | | [ ] |
| 8 | Next.js | 85% | | [ ] |
| 9 | React Ecosystem + AI | 85% | | [ ] |
| 10 | DSA Foundations | 80% | | [ ] |
| 11 | DSA Intermediate | 80% | | [ ] |
| 12 | DSA Practice | 80% | | [ ] |
| 13 | System Design Foundations | 85% | | [ ] |
| 14 | Real-World Design + Mock | 85% | | [ ] |

---

**Document Version:** 2.0  
**Last Updated:** ___________  
**Current Phase:** ___________  
**Overall Progress:** ___/90 days

---

*This is a living document. Update progress after each day's completion.*
