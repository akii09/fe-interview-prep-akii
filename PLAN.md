# 84-Day Senior Frontend Interview Preparation Plan

**Target:** Sr/Lead roles at top product companies  
**Daily Commitment:** 4.5 hours  
**Start Date:** Today  
**Interview Ready Date:** Day 85

---

## Plan Structure

### Phase 1: JavaScript Foundations (Days 1-28)
### Phase 2: React & Ecosystem (Days 29-49)
### Phase 3: DSA for Frontend (Days 50-63)
### Phase 4: System Design (Days 64-77)
### Phase 5: Mock Interviews & Polish (Days 78-84)

---

# PHASE 1: JavaScript Foundations (Days 1-28)

## Week 1: Execution Model & Core Concepts (Days 1-7)

### Day 1: Event Loop & Execution Context
**Time: 4.5 hours**

**Morning (2 hours): Study**
- How JavaScript executes code (call stack)
- Execution context (global, function)
- Event loop phases: Call Stack → Microtask Queue → Macrotask Queue
- `setTimeout` vs `Promise` timing
- Microtasks vs Macrotasks

**Resources:**
- Jake Archibald's "In The Loop" talk (YouTube)
- JavaScript.info: Event Loop chapter
- Lydia Hallie's JavaScript Visualized series

**Afternoon (2 hours): Practice**
- 20 output prediction problems (event loop)
- Explain each answer out loud
- Create a mental model diagram

**Evening (30 mins): Review**
- Write down 5 key insights
- Note confusing parts for tomorrow

**Deliverable:** Can predict output of mixed async code confidently

---

### Day 2: Event Loop Deep Dive + Testing
**Time: 4.5 hours**

**Morning (1.5 hours): Advanced Concepts**
- `process.nextTick` vs `setImmediate` (Node.js)
- `queueMicrotask` API
- Starvation scenarios
- `async/await` execution order

**Afternoon (2 hours): Coding**
- Implement a simple task scheduler
- Build a custom Promise.resolve
- Solve 15 more output prediction problems

**Evening (1 hour): TEST WITH ME**
- Post "Day 2 complete, ready for test"
- I'll give you 10 rapid-fire questions
- Must score 8/10 to move forward

**Blocker:** If you score <8/10, repeat Day 2

---

### Day 3: Scope, Hoisting, TDZ
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Lexical scope vs dynamic scope
- Scope chain resolution
- Hoisting (var, let, const, function)
- Temporal Dead Zone (TDZ)
- Block scope vs function scope

**Afternoon (2 hours): Practice**
- 25 output prediction problems (scope/hoisting)
- Fix 10 scope-related bugs
- Explain hoisting to yourself aloud

**Evening (30 mins): Create Cheat Sheet**
- var vs let vs const (all differences)
- Hoisting rules
- TDZ examples

---

### Day 4: Closures (Part 1)
**Time: 4.5 hours**

**Morning (2 hours): Study**
- What is a closure?
- How closures are created
- Closure use cases (data privacy, function factories)
- Memory implications
- Classic loop + setTimeout bug

**Resources:**
- MDN: Closures
- "You Don't Know JS: Scope & Closures" (Chapter 5)

**Afternoon (2 hours): Coding**
- Fix var/setTimeout bug (3 different ways)
- Create private counter
- Implement `once()` function
- Build function that returns incrementing IDs

**Evening (30 mins): Explain**
- Record yourself explaining closures (audio/video)
- Listen back—are you clear?

---

### Day 5: Closures (Part 2) + Testing
**Time: 4.5 hours**

**Morning (1.5 hours): Advanced Patterns**
- Partial application
- Currying with closures
- Memoization using closures
- Module pattern (IIFE)

**Afternoon (2 hours): Coding**
- Implement memoize function
- Build a cache with TTL using closures
- Solve 5 LeetCode-style closure problems

**Evening (1 hour): TEST WITH ME**
- Post "Day 5 complete, ready for closure test"
- I'll ask implementation + explanation questions
- Must demonstrate clear understanding

---

### Day 6: `this` Binding (Critical)
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Default binding (strict vs non-strict mode)
- Implicit binding (method calls)
- Explicit binding (call, apply, bind)
- `new` binding
- Arrow functions (lexical `this`)
- Precedence rules

**Resources:**
- "You Don't Know JS: this & Object Prototypes"
- Tyler McGinnis: "JavaScript this Keyword"

**Afternoon (2 hours): Practice**
- 30 "what is `this`?" prediction problems
- Fix 10 context-loss bugs
- Implement scenarios for each binding type

**Evening (30 mins): Create Reference**
- `this` determination flowchart
- All binding rules with examples

**Critical:** This is your weakest area—invest extra focus

---

### Day 7: `this` Deep Dive + Implementation
**Time: 4.5 hours**

**Morning (2 hours): Implementations**
- Implement `Function.prototype.bind` from scratch
- Implement `Function.prototype.call`
- Implement `Function.prototype.apply`
- Understand how `new` operator works with `this`

**Afternoon (1.5 hours): Coding**
- Fix real-world callback context bugs
- Convert functions to arrow functions (and vice versa)
- Solve class method binding problems

**Evening (1 hour): TEST WITH ME**
- Post "Day 7 complete, ready for `this` test"
- Implementation + explanation questions
- Must score 9/10—this is critical

---

## Week 2: Prototypes & OOP (Days 8-14)

### Day 8: Prototypes (Part 1)
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- `__proto__` vs `prototype`
- Prototype chain traversal
- How property lookup works
- Constructor functions
- `Object.create()`

**Resources:**
- MDN: Inheritance and the prototype chain
- JavaScript.info: Prototypes

**Afternoon (2 hours): Practice**
- Trace prototype chains in 15 examples
- Create objects with `Object.create()`
- Build inheritance without classes

---

### Day 9: Prototypes (Part 2)
**Time: 4.5 hours**

**Morning (2 hours): Advanced Concepts**
- Adding methods to prototypes
- Prototype pollution (security concern)
- `Object.getPrototypeOf()`, `Object.setPrototypeOf()`
- `instanceof` operator internals

**Afternoon (2 hours): Implementations**
- Implement `Object.create()` polyfill
- Implement `instanceof` from scratch
- Implement `new` operator behavior
- Create deep inheritance chain

**Evening (30 mins): Diagrams**
- Draw prototype chains for complex scenarios

---

### Day 10: ES6 Classes & Inheritance
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Class syntax (syntactic sugar)
- Constructor vs class methods
- `super` keyword
- Static methods
- Private fields (#field)
- Getters and setters

**Afternoon (2 hours): Practice**
- Convert constructor functions to classes
- Implement inheritance with extends
- Create abstract patterns with classes
- Build real-world class hierarchies

**Evening (30 mins): Compare**
- Class vs constructor function (pros/cons)
- When to use each

---

### Day 11: Object Mastery
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Property descriptors (writable, enumerable, configurable)
- `Object.defineProperty()`
- `Object.freeze()`, `Object.seal()`, `Object.preventExtensions()`
- Getters/setters with descriptors
- Computed property names
- Object destructuring (all forms)

**Afternoon (2 hours): Coding**
- Deep clone object (handle circular references)
- Deep freeze object
- Implement getter/setter validation
- Solve 10 object manipulation problems

**Evening (30 mins): Patterns**
- When to use freeze vs seal
- Immutability patterns

---

### Day 12: Prototypes + Objects Testing
**Time: 4.5 hours**

**Morning (2 hours): Review & Reinforce**
- Redo problems from Days 8-11
- Fill any conceptual gaps
- Create consolidated notes

**Afternoon (1.5 hours): Coding Challenge**
- Build a complete inheritance system
- Implement object utility functions
- Solve complex prototype problems

**Evening (1 hour): TEST WITH ME**
- Post "Day 12 complete, ready for OOP test"
- Prototype chain + implementation questions
- Explanation of concepts

---

### Day 13: Async Foundations - Callbacks & Promises
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Callbacks and callback hell
- Error-first callback convention
- Promise states (pending, fulfilled, rejected)
- Promise chaining
- Error propagation in promises
- `then()`, `catch()`, `finally()`

**Resources:**
- JavaScript.info: Promises
- Exploring JS: Promises

**Afternoon (2 hours): Practice**
- Convert callbacks to promises
- Chain promises correctly
- Handle errors in promise chains
- Understand `fetch` promise behavior (404 vs network error)

---

### Day 14: Promise APIs & Implementation
**Time: 4.5 hours**

**Morning (2 hours): Study & Code**
- `Promise.all()` - parallel execution, fail-fast
- `Promise.race()` - first settled
- `Promise.allSettled()` - all results regardless
- `Promise.any()` - first fulfilled

**Afternoon (2 hours): Implementations**
- Implement `Promise.all()` from scratch
- Implement `Promise.race()`
- Implement `Promise.allSettled()`
- Add timeout wrapper for promises
- Retry failed promises N times

**Evening (30 mins): Patterns**
- When to use each Promise API
- Sequential vs parallel execution trade-offs

---

## Week 3: Async Patterns & Performance (Days 15-21)

### Day 15: Async/Await Mastery
**Time: 4.5 hours**

**Morning (2 hours): Study**
- async/await as syntactic sugar
- Error handling (try-catch)
- Sequential vs parallel with async/await
- Top-level await
- Async iteration (for-await-of)
- Common pitfalls

**Afternoon (2 hours): Practice**
- Convert promise chains to async/await
- Handle errors properly
- Sequential execution patterns
- Parallel execution patterns
- Mixed async patterns

**Evening (30 mins): Patterns**
- When to use .then() vs async/await
- Error handling best practices

---

### Day 16: Advanced Async Patterns
**Time: 4.5 hours**

**Morning (2 hours): Implementations**
- Sequential promise execution
- Parallel with concurrency limit
- Request queue with rate limiting
- Retry with exponential backoff
- Timeout for async operations

**Afternoon (2 hours): Real-World**
- Build API client with retry logic
- Implement rate-limited API caller
- Create async task scheduler
- Handle race conditions

**Evening (30 mins): Review**
- Common async bugs and fixes

---

### Day 17: Debounce & Throttle (Critical)
**Time: 4.5 hours**

**Morning (2 hours): Study & Understand**
- What is debouncing? (wait for silence)
- What is throttling? (limit execution rate)
- Use cases for each
- Implementation requirements

**Afternoon (2 hours): Implementations**
- Implement debounce from scratch (with leading/trailing options)
- Implement throttle from scratch
- Implement debounce with immediate execution
- Add cancel method to both

**Evening (30 mins): Practice**
- Use debounce for search input
- Use throttle for scroll handler
- Compare performance

**Critical:** You got this completely wrong—focus deeply

---

### Day 18: Memoization & Performance
**Time: 4.5 hours**

**Morning (2 hours): Study**
- What is memoization?
- When to use it
- Cache invalidation strategies
- LRU cache concept

**Afternoon (2 hours): Implementations**
- Implement simple memoize function
- Memoize with multiple arguments
- Implement LRU cache
- Memoize with TTL (time-to-live)
- Fibonacci with memoization

**Evening (30 mins): Patterns**
- When memoization helps vs hurts
- Memory trade-offs

---

### Day 19: Memory Management & Optimization
**Time: 4.5 hours**

**Morning (2 hours): Study**
- JavaScript garbage collection (mark-and-sweep)
- Memory leaks (closures, timers, DOM refs, event listeners)
- WeakMap and WeakSet (garbage collection friendly)
- Reference vs value
- Memory profiling basics

**Afternoon (2 hours): Practice**
- Identify memory leaks in code samples
- Fix closure-based memory leaks
- Use WeakMap for caching
- Clean up timers and event listeners properly

**Evening (30 mins): Checklist**
- Common memory leak patterns
- Prevention strategies

---

### Day 20: Async + Performance Testing
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Redo problems from Days 15-19
- Consolidate learnings

**Afternoon (2 hours): Coding Challenge**
- Build complete async utilities library
- Solve 10 performance optimization problems
- Implement real-world scenarios

**Evening (1 hour): TEST WITH ME**
- Post "Day 20 complete, ready for async test"
- Implement debounce/throttle/memoize
- Explain async patterns
- Handle edge cases

---

### Day 21: Rest Day & Consolidation
**Time: 4.5 hours**

**Morning (2 hours): Review Week 1-3**
- Redo failed test questions
- Strengthen weak areas
- Create summary notes

**Afternoon (2 hours): Practice**
- Solve 20 mixed problems (all topics so far)
- Explain concepts out loud
- Identify remaining gaps

**Evening (30 mins): Prepare**
- Plan for Week 4
- Set goals for functional programming

---

## Week 4: Functional Programming & Advanced Concepts (Days 22-28)

### Day 22: Functional Programming Foundations
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Pure functions (no side effects)
- Immutability principles
- First-class functions
- Higher-order functions
- Function composition
- Declarative vs imperative

**Resources:**
- "Functional-Light JavaScript" by Kyle Simpson
- "Professor Frisby's Mostly Adequate Guide"

**Afternoon (2 hours): Practice**
- Convert imperative code to functional
- Write pure functions
- Compose functions
- Chain array methods

---

### Day 23: Array Methods Deep Dive
**Time: 4.5 hours**

**Morning (2 hours): Study**
- `map`, `filter`, `reduce` internals
- `forEach`, `find`, `findIndex`
- `some`, `every`
- `flat`, `flatMap`
- Method chaining performance
- Mutation vs non-mutation methods

**Afternoon (2 hours): Implementations**
- Implement `map` from scratch
- Implement `filter` from scratch
- Implement `reduce` from scratch
- Implement `flat` (all levels)
- Implement `flatMap`

**Evening (30 mins): Patterns**
- When to use reduce vs map+filter
- Performance considerations

---

### Day 24: Currying & Composition
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Currying concept
- Partial application
- Difference between currying and partial application
- Function composition
- Pipe vs compose

**Afternoon (2 hours): Implementations**
- Implement curry function (with placeholders)
- Implement partial application
- Implement compose function
- Implement pipe function
- Build real-world curried utilities

**Evening (30 mins): Practice**
- Curry existing functions
- Compose complex transformations

---

### Day 25: ES6+ Features
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Destructuring (all forms: array, object, nested, defaults)
- Spread operator (objects, arrays)
- Rest parameters
- Default parameters
- Template literals (including tagged templates)
- Symbols
- Iterators and generators
- for...of loops

**Afternoon (2 hours): Practice**
- Use destructuring in complex scenarios
- Create custom iterators
- Implement generator functions
- Write generator for Fibonacci
- Use symbols for privacy

---

### Day 26: Advanced ES6+ & Proxies
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Proxy object
- Reflect API
- Proxy traps (get, set, has, deleteProperty, etc.)
- WeakMap and WeakSet
- Map vs Object, Set vs Array
- Use cases for each

**Afternoon (2 hours): Implementations**
- Create validation proxy
- Implement observable pattern with proxy
- Build property access logger
- Use WeakMap for private data
- Solve problems with Map/Set

**Evening (30 mins): Patterns**
- When to use Proxy vs Object.defineProperty
- WeakMap use cases

---

### Day 27: Error Handling & Modules
**Time: 4.5 hours**

**Morning (2 hours): Study**
**Error Handling:**
- try-catch-finally
- Error types (TypeError, ReferenceError, SyntaxError)
- Custom errors
- Error propagation
- Global error handling

**Module Systems:**
- CommonJS vs ES Modules
- Named vs default exports
- Dynamic imports
- Circular dependencies
- Tree shaking

**Afternoon (2 hours): Practice**
- Create custom error classes
- Handle async errors properly
- Use dynamic imports for code splitting
- Resolve circular dependency issues

**Evening (30 mins): Patterns**
- Error handling strategies
- Module organization best practices

---

### Day 28: Week 4 Testing & Phase 1 Review
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Functional programming concepts
- Array method implementations
- ES6+ features
- Fill gaps from Days 22-27

**Afternoon (2 hours): Comprehensive Coding**
- Solve 15 mixed problems (FP, arrays, ES6+)
- Implement utilities using all learned concepts
- Real-world scenario problems

**Evening (1 hour): PHASE 1 FINAL TEST WITH ME**
- Post "Phase 1 complete, ready for comprehensive test"
- I'll test all JavaScript fundamentals
- Mixed questions across all 4 weeks
- Must score 80%+ to move to React

**Blocker:** If <80%, identify weak areas and spend 2-3 extra days

---

# PHASE 2: React & Ecosystem (Days 29-49)

## Week 5: React Foundations (Days 29-35)

### Day 29: React Fundamentals
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- React philosophy (declarative, component-based)
- JSX syntax and transforms
- Components (functional vs class)
- Props and prop drilling
- Children prop
- Composition vs inheritance
- Controlled vs uncontrolled components

**Resources:**
- Official React docs (new beta docs)
- "React - The Complete Guide" (Udemy - first 4 hours)

**Afternoon (2 hours): Practice**
- Build 5 basic components
- Pass data with props
- Compose components
- Handle form inputs (controlled)

---

### Day 30: State & Events
**Time: 4.5 hours**

**Morning (2 hours): Study**
- State concept
- `useState` hook
- State updates (async, batching)
- Event handling in React
- Synthetic events
- State lifting
- Immutable state updates

**Afternoon (2 hours): Practice**
- Build stateful components
- Lift state to parent
- Handle multiple input fields
- Update nested state immutably
- Build simple counter, todo app

**Evening (30 mins): Patterns**
- When to lift state
- State update patterns

---

### Day 31: Component Lifecycle & useEffect
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Component lifecycle (mount, update, unmount)
- `useEffect` hook
- Dependency array rules
- Cleanup functions
- Effect execution timing
- Common pitfalls (infinite loops, missing deps)
- Class lifecycle methods (for comparison)

**Afternoon (2 hours): Practice**
- Fetch data with useEffect
- Set up timers with cleanup
- Subscribe to events with cleanup
- Handle dependencies correctly
- Debug infinite effect loops

---

### Day 32: Refs & DOM Interaction
**Time: 4.5 hours**

**Morning (2 hours): Study**
- `useRef` hook
- Ref vs state (when to use each)
- Accessing DOM elements
- Storing mutable values
- `forwardRef`
- `useImperativeHandle`
- Callback refs

**Afternoon (2 hours): Practice**
- Focus input on mount
- Measure DOM elements
- Integrate third-party DOM libraries
- Build custom input component with ref
- Store previous values with ref

**Evening (30 mins): Patterns**
- Ref use cases
- Ref vs state decision tree

---

### Day 33: Lists, Keys & Reconciliation
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Rendering lists
- Key prop (why it matters)
- Reconciliation algorithm
- Virtual DOM concept
- React Fiber basics
- Diffing algorithm
- Index as key (pitfalls)

**Afternoon (2 hours): Practice**
- Render dynamic lists
- Handle key correctly
- Build todo list with add/remove
- Reorder items properly
- Optimize list rendering

**Evening (30 mins): Debugging**
- Identify key-related bugs
- Fix reconciliation issues

---

### Day 34: Forms & Validation
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Controlled components (inputs, textarea, select)
- Uncontrolled components with refs
- Form submission handling
- Validation strategies
- Form libraries (react-hook-form concepts)

**Afternoon (2 hours): Practice**
- Build multi-field form
- Implement validation logic
- Show error messages
- Handle dynamic form fields
- Form with checkbox/radio groups

**Evening (30 mins): Patterns**
- Controlled vs uncontrolled decision
- Validation approaches

---

### Day 35: React Fundamentals Testing
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Components, props, state
- useEffect, useRef
- Lists and keys
- Forms

**Afternoon (2 hours): Build Project**
- Complete todo app with:
  - Add/edit/delete
  - Mark complete
  - Filter (all/active/completed)
  - Local storage persistence
  - Form validation

**Evening (1 hour): TEST WITH ME**
- Post "Day 35 complete, ready for React basics test"
- Explain rendering behavior
- Debug component issues
- Implement features live

---

## Week 6: Advanced React (Days 36-42)

### Day 36: Context API & Prop Drilling Solutions
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Prop drilling problem
- Context API (`createContext`, `Provider`, `Consumer`)
- `useContext` hook
- Multiple contexts
- Context performance implications
- When to use vs avoid context

**Afternoon (2 hours): Practice**
- Build theme context
- Build auth context
- Avoid unnecessary re-renders with context
- Split contexts by concern
- Combine context with custom hooks

**Evening (30 mins): Patterns**
- Context design patterns
- Performance optimization with context

---

### Day 37: Custom Hooks
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Rules of hooks
- Creating custom hooks
- Hook composition
- Sharing stateful logic
- Testing custom hooks
- Common custom hook patterns

**Afternoon (2 hours): Implementations**
- `useLocalStorage` hook
- `useFetch` hook
- `useDebounce` hook
- `useToggle` hook
- `usePrevious` hook
- `useEventListener` hook

**Evening (30 mins): Library**
- Create personal hook library
- Document each hook

---

### Day 38: Performance Optimization
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- React.memo (when to use)
- `useMemo` hook
- `useCallback` hook
- Difference between useMemo and useCallback
- Expensive computation memoization
- Referential equality issues
- Performance profiling (React DevTools)
- Code splitting with lazy and Suspense

**Afternoon (2 hours): Practice**
- Optimize expensive list rendering
- Prevent unnecessary re-renders
- Use React.memo appropriately
- Lazy load components
- Profile component performance
- Fix performance issues

---

### Day 39: Advanced Patterns
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Higher-Order Components (HOC)
- Render props pattern
- Compound components
- State reducer pattern
- Controlled component props
- React design patterns

**Afternoon (2 hours): Implementations**
- Build HOC for authentication
- Create render prop component
- Implement compound component (Tabs)
- Build controlled/uncontrolled component

**Evening (30 mins): Compare**
- HOC vs render props vs hooks
- When to use each pattern

---

### Day 40: Error Boundaries & Portals
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Error boundaries (class-based)
- Error catching in React
- Graceful error handling
- Portals (ReactDOM.createPortal)
- Use cases for portals (modals, tooltips)

**Afternoon (2 hours): Practice**
- Create error boundary component
- Build modal with portal
- Build tooltip with portal
- Handle errors gracefully
- Create notification system with portal

**Evening (30 mins): Patterns**
- Error boundary placement strategy
- Portal use cases

---

### Day 41: React 18+ Features
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Concurrent rendering
- `useTransition` hook
- `useDeferredValue` hook
- Automatic batching
- Suspense for data fetching
- Server Components (conceptual understanding)
- New Suspense features

**Afternoon (2 hours): Practice**
- Use useTransition for non-urgent updates
- Implement search with useDeferredValue
- Optimize with concurrent features
- Understand Suspense boundaries

**Evening (30 mins): New Features**
- What's new in React 18+
- Migration considerations

---

### Day 42: Advanced React Testing
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Context, custom hooks
- Performance optimization
- Advanced patterns
- React 18 features

**Afternoon (2 hours): Build Project**
- E-commerce product filter:
  - Search with debounce
  - Category filters
  - Price range slider
  - Infinite scroll/pagination
  - Context for cart
  - Performance optimizations

**Evening (1 hour): TEST WITH ME**
- Post "Day 42 complete, ready for advanced React test"
- Explain re-rendering behavior
- Debug performance issues
- Implement optimizations live

---

## Week 7: Next.js & Ecosystem (Days 43-49)

### Day 43: Next.js Fundamentals
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Next.js philosophy (React framework)
- File-based routing (Pages Router)
- App Router (Next.js 13+)
- Pages vs App directory
- Link component
- Image component
- next.config.js basics

**Resources:**
- Official Next.js docs
- Next.js 13+ crash course

**Afternoon (2 hours): Practice**
- Create Next.js project
- Build multi-page app with routing
- Use Link and Image components
- Create nested routes
- Dynamic routes ([id].js)

---

### Day 44: Data Fetching in Next.js
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Static Generation (SSG) vs Server-Side Rendering (SSR)
- `getStaticProps`, `getStaticPaths`
- `getServerSideProps`
- Incremental Static Regeneration (ISR)
- App Router data fetching (async components)
- Client-side fetching
- SWR and React Query concepts

**Afternoon (2 hours): Practice**
- Build page with getStaticProps
- Build page with getServerSideProps
- Dynamic routes with getStaticPaths
- Implement ISR
- Fetch data on client with SWR

---

### Day 45: App Router Deep Dive
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Server Components vs Client Components
- `use client` directive
- `use server` directive
- Layouts and templates
- Loading and error states (loading.js, error.js)
- Parallel and intercepted routes
- Route groups

**Afternoon (2 hours): Practice**
- Build app with App Router
- Create layouts
- Implement loading states
- Add error boundaries
- Use server and client components correctly

**Evening (30 mins): Patterns**
- When to use Server vs Client Components
- App Router best practices

---

### Day 46: API Routes & Middleware
**Time: 4.5 hours**

**Morning (2 hours): Study**
- API routes in Pages Router
- Route handlers in App Router
- Request and response handling
- Middleware (middleware.ts)
- Authentication with middleware
- Edge runtime vs Node runtime

**Afternoon (2 hours): Practice**
- Create REST API endpoints
- Handle GET/POST/PUT/DELETE
- Implement middleware for auth
- Edge middleware examples
- Connect to database (conceptual)

**Evening (30 mins): Security**
- API route security best practices
- CORS handling

---

### Day 47: Styling & Optimization
**Time: 4.5 hours**

**Morning (2 hours): Study**
- CSS Modules
- Tailwind CSS with Next.js
- CSS-in-JS options (styled-components, emotion)
- Font optimization (next/font)
- Image optimization
- Script optimization (next/script)
- Bundle analysis

**Afternoon (2 hours): Practice**
- Style components with CSS Modules
- Set up Tailwind CSS
- Optimize fonts and images
- Analyze bundle size
- Lazy load components

---

### Day 48: Deployment & Full Next.js Project
**Time: 4.5 hours**

**Morning (1.5 hours): Study**
- Vercel deployment
- Environment variables
- Build optimization
- Caching strategies
- Static exports

**Afternoon (3 hours): Build Complete Project**
- Blog with Next.js:
  - List of posts (SSG)
  - Individual post pages (SSG with dynamic routes)
  - Search (client-side)
  - Categories (static)
  - Contact form (API route)
  - Responsive design
  - Image optimization
  - SEO optimization

---

### Day 49: React Ecosystem & Phase 2 Final Test
**Time: 4.5 hours**

**Morning (1.5 hours): Study**
- State management overview (Redux, Zustand, Jotai)
- React Query / TanStack Query (data fetching)
- Form libraries (React Hook Form, Formik)
- Testing (Jest, React Testing Library basics)
- TypeScript with React (basics)

**Afternoon (1.5 hours): Review**
- Review all React and Next.js concepts
- Consolidate notes
- Identify weak areas

**Evening (1.5 hours): PHASE 2 FINAL TEST WITH ME**
- Post "Phase 2 complete, ready for React/Next.js test"
- Build features live
- Explain rendering, SSR vs SSG
- Debug issues
- Optimize performance
- Must score 80%+

---

# PHASE 3: DSA for Frontend (Days 50-63)

## Week 8: DSA Foundations (Days 50-56)

### Day 50: DSA Mindset & Big O
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Why DSA matters for frontend
- Big O notation (time and space)
- Common complexities (O(1), O(n), O(log n), O(n²))
- Best, average, worst case
- Space complexity

**Resources:**
- "Grokking Algorithms" (Chapter 1)
- BigO cheat sheet

**Afternoon (2 hours): Practice**
- Analyze complexity of existing code
- Calculate Big O for 20 code snippets
- Optimize code based on complexity

**Evening (30 mins): Reference**
- Create Big O quick reference
- Common pattern complexities

---

### Day 51: Arrays & Strings
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Array operations (insert, delete, search)
- Two-pointer technique
- Sliding window
- String manipulation patterns

**Afternoon (3 hours): LeetCode Practice**
**Easy (10 problems):**
- Two Sum
- Best Time to Buy and Sell Stock
- Contains Duplicate
- Valid Anagram
- Valid Palindrome
- Reverse String
- Merge Sorted Array
- Remove Duplicates from Sorted Array
- Plus One
- Move Zeroes

**Target:** Solve each in <20 mins

---

### Day 52: Arrays & Strings (Advanced)
**Time: 4.5 hours**

**Morning (1.5 hours): Patterns**
- Sliding window (fixed and variable)
- Two-pointer (same direction, opposite)
- Prefix sum
- Kadane's algorithm

**Afternoon (3 hours): LeetCode Practice**
**Medium (8 problems):**
- Longest Substring Without Repeating Characters
- 3Sum
- Container With Most Water
- Product of Array Except Self
- Maximum Subarray
- Group Anagrams
- Longest Palindromic Substring
- String to Integer (atoi)

**Target:** Solve each in <30 mins

---

### Day 53: Hash Tables & Sets
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Hash table implementation
- Collision resolution
- Map vs Object in JavaScript
- Set operations
- When to use hash tables

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (10 problems):**
- Two Sum (with hash map)
- Valid Anagram (optimal solution)
- Intersection of Two Arrays
- Happy Number
- Isomorphic Strings
- Word Pattern
- Contains Duplicate II
- Logger Rate Limiter
- Design HashMap
- First Unique Character in a String

---

### Day 54: Stacks & Queues
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Stack (LIFO) - implementation and use cases
- Queue (FIFO) - implementation and use cases
- Monotonic stack
- Deque (double-ended queue)

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (10 problems):**
- Valid Parentheses
- Implement Queue using Stacks
- Implement Stack using Queues
- Min Stack
- Backspace String Compare
- Daily Temperatures
- Next Greater Element I
- Evaluate Reverse Polish Notation
- Simplify Path
- Decode String

---

### Day 55: Linked Lists
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Singly linked list
- Doubly linked list
- Fast & slow pointer (Floyd's cycle detection)
- Reverse linked list pattern

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (8 problems):**
- Reverse Linked List
- Merge Two Sorted Lists
- Linked List Cycle
- Remove Nth Node From End
- Middle of Linked List
- Palindrome Linked List
- Intersection of Two Linked Lists
- Add Two Numbers

---

### Day 56: Trees (Part 1)
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Binary tree terminology
- Tree traversals (inorder, preorder, postorder)
- DFS vs BFS
- Level-order traversal

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (8 problems):**
- Maximum Depth of Binary Tree
- Same Tree
- Invert Binary Tree
- Symmetric Tree
- Path Sum
- Binary Tree Level Order Traversal
- Binary Tree Inorder Traversal
- Binary Tree Preorder Traversal

---

## Week 9: DSA Intermediate (Days 57-63)

### Day 57: Trees (Part 2)
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Binary Search Tree (BST)
- BST properties and operations
- Lowest Common Ancestor
- Tree construction from traversals

**Afternoon (3 hours): LeetCode Practice**
**Medium (8 problems):**
- Validate Binary Search Tree
- Kth Smallest Element in BST
- Lowest Common Ancestor of BST
- Binary Tree Right Side View
- Construct Binary Tree from Preorder and Inorder
- Path Sum II
- Count Good Nodes in Binary Tree
- Diameter of Binary Tree

---

### Day 58: Recursion & Backtracking
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Recursion fundamentals
- Base case and recursive case
- Backtracking pattern
- When to use backtracking

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (8 problems):**
- Fibonacci Number
- Climbing Stairs
- Pow(x, n)
- Subsets
- Permutations
- Combination Sum
- Generate Parentheses
- Letter Combinations of Phone Number

---

### Day 59: Dynamic Programming (Intro)
**Time: 4.5 hours**

**Morning (2 hours): Concepts**
- DP philosophy (optimal substructure, overlapping subproblems)
- Memoization (top-down)
- Tabulation (bottom-up)
- 1D DP patterns

**Afternoon (2.5 hours): LeetCode Practice**
**Easy to Medium (6 problems):**
- Climbing Stairs (DP approach)
- Min Cost Climbing Stairs
- House Robber
- Maximum Subarray (DP approach)
- Coin Change
- Longest Increasing Subsequence

---

### Day 60: Graphs (Basics)
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Graph representation (adjacency list, matrix)
- DFS in graphs
- BFS in graphs
- Connected components

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (6 problems):**
- Number of Islands
- Clone Graph
- Pacific Atlantic Water Flow
- Course Schedule
- Number of Connected Components
- Graph Valid Tree

---

### Day 61: Binary Search
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Binary search template
- Search space reduction
- Binary search on answer
- Rotated array searches

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (8 problems):**
- Binary Search
- First Bad Version
- Search Insert Position
- Find Peak Element
- Search in Rotated Sorted Array
- Find Minimum in Rotated Sorted Array
- Koko Eating Bananas
- Time Based Key-Value Store

---

### Day 62: Heaps & Priority Queue
**Time: 4.5 hours**

**Morning (1.5 hours): Concepts**
- Min heap and max heap
- Heap operations
- Priority queue use cases
- Top K patterns

**Afternoon (3 hours): LeetCode Practice**
**Easy to Medium (6 problems):**
- Kth Largest Element in Array
- Top K Frequent Elements
- Merge K Sorted Lists
- Find Median from Data Stream
- Last Stone Weight
- K Closest Points to Origin

---

### Day 63: DSA Phase Final Test
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Review all data structures
- Review patterns
- Redo difficult problems

**Afternoon (2 hours): Mixed Practice**
- Solve 10 random medium problems
- Time yourself (<30 mins each)
- Focus on explaining approach

**Evening (1 hour): TEST WITH ME**
- Post "Phase 3 complete, ready for DSA test"
- Solve 3 problems live (easy, medium, medium)
- Explain approach before coding
- Analyze complexity
- Must complete all 3 correctly

---

# PHASE 4: System Design (Days 64-77)

## Week 10: Frontend System Design Foundations (Days 64-70)

### Day 64: System Design Fundamentals
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- What is frontend system design?
- Design interview format and expectations
- Gathering requirements
- Defining scope
- Clarifying questions framework
- High-level vs detailed design

**Resources:**
- "Frontend System Design Guidebook" by GreatFrontEnd
- System design primer

**Afternoon (2 hours): Practice**
- Watch 2 system design interview videos
- Practice asking clarifying questions
- Create requirements checklist template

---

### Day 65: Component Architecture & State Management
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Component design principles
- Component composition
- Prop drilling vs state management
- When to use Context vs Redux vs Zustand
- State normalization
- Client state vs server state

**Afternoon (2.5 hours): Practice**
- Design component hierarchy for:
  - E-commerce product page
  - Social media feed
  - Dashboard with widgets
- Decide state management approach for each
- Draw component trees

---

### Day 66: Data Fetching & Caching
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Data fetching strategies (fetch on mount, lazy, prefetch)
- Caching strategies (in-memory, localStorage, IndexedDB)
- Cache invalidation
- Optimistic updates
- Polling vs WebSockets vs SSE
- React Query / SWR patterns

**Afternoon (2.5 hours): Practice**
- Design data flow for:
  - News feed with infinite scroll
  - Real-time chat application
  - Dashboard with live data
- Choose fetching and caching strategy
- Handle loading, error, empty states

---

### Day 67: Performance Optimization
**Time: 4.5 hours**

**Morning (2.5 hours): Study**
- Performance metrics (FCP, LCP, CLS, FID, TTI)
- Code splitting strategies
- Lazy loading (images, components, routes)
- Bundle optimization
- Tree shaking
- Critical rendering path
- Resource prioritization
- Virtualization (windowing)

**Afternoon (2 hours): Practice**
- Optimize designs from Day 65:
  - Identify performance bottlenecks
  - Apply code splitting
  - Add lazy loading
  - Implement virtualization where needed
- Create performance checklist

---

### Day 68: Accessibility & Responsive Design
**Time: 4.5 hours**

**Morning (2 hours): Study**
- WCAG guidelines (A, AA, AAA)
- Semantic HTML
- ARIA roles and attributes
- Keyboard navigation
- Screen reader considerations
- Responsive design principles
- Mobile-first approach
- Touch vs mouse interactions

**Afternoon (2.5 hours): Practice**
- Add accessibility to previous designs:
  - Keyboard navigation
  - ARIA labels
  - Focus management
  - Screen reader support
- Design responsive layouts:
  - Mobile, tablet, desktop
  - Breakpoint strategy

---

### Day 69: API Design & Error Handling
**Time: 4.5 hours**

**Morning (2 hours): Study**
- REST API design
- GraphQL basics
- API versioning
- Rate limiting
- Error handling strategies
- Retry logic
- Fallback mechanisms
- Graceful degradation

**Afternoon (2.5 hours): Practice**
- Design API layer for applications:
  - Define endpoints
  - Handle errors gracefully
  - Implement retry logic
  - Add loading states
  - Plan fallbacks

---

### Day 70: Security & Testing Strategy
**Time: 4.5 hours**

**Morning (2 hours): Study**
- XSS prevention
- CSRF protection
- Content Security Policy
- Authentication (JWT, OAuth, session)
- Authorization patterns
- HTTPS and secure connections
- Testing pyramid (unit, integration, e2e)
- Test strategy for components

**Afternoon (2.5 hours): Practice**
- Add security to previous designs:
  - Authentication flow
  - Authorization checks
  - Secure API calls
  - Input sanitization
- Define testing strategy:
  - What to unit test
  - What to integration test
  - E2E test scenarios

---

## Week 11: Real-World System Design (Days 71-77)

### Day 71: Design Common Applications (Part 1)
**Time: 4.5 hours**

**Full Day: Design 2 Systems**

**System 1: News Feed (2 hours)**
- Requirements gathering
- Component architecture
- Data fetching (infinite scroll)
- State management
- Performance (virtualization)
- Real-time updates

**System 2: Autocomplete/Typeahead (2.5 hours)**
- Requirements
- Debouncing
- Caching results
- Keyboard navigation
- Accessibility
- API design
- Performance

**Document both with diagrams**

---

### Day 72: Design Common Applications (Part 2)
**Time: 4.5 hours**

**Full Day: Design 2 Systems**

**System 1: Image Gallery/Carousel (2 hours)**
- Requirements
- Lazy loading images
- Thumbnail generation
- Swipe gestures
- Keyboard controls
- Responsive design
- Performance

**System 2: Chat Application (2.5 hours)**
- Requirements
- Real-time messaging (WebSocket)
- Message history
- Online status
- Typing indicators
- Optimistic updates
- State management

---

### Day 73: Design Common Applications (Part 3)
**Time: 4.5 hours**

**Full Day: Design 2 Systems**

**System 1: E-commerce Product Listing (2 hours)**
- Requirements
- Filters and sorting
- Pagination vs infinite scroll
- URL state management
- Performance
- SEO considerations

**System 2: Video Player (2.5 hours)**
- Requirements
- Controls (play, pause, seek, volume)
- Quality selection
- Subtitles/captions
- Keyboard shortcuts
- Accessibility
- Performance (buffering)

---

### Day 74: Design Common Applications (Part 4)
**Time: 4.5 hours**

**Full Day: Design 2 Systems**

**System 1: Dashboard with Widgets (2 hours)**
- Requirements
- Widget library
- Drag and drop
- Customization
- Data refresh
- Performance

**System 2: Notification System (2.5 hours)**
- Requirements
- Real-time notifications
- Notification types
- Persistence
- Read/unread state
- Permissions (browser notifications)

---

### Day 75: Advanced Topics
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Micro-frontends
- Server-side rendering (SSR) architecture
- Static site generation (SSG)
- Progressive Web Apps (PWA)
- Web Workers
- Service Workers
- CDN strategy
- Multi-region deployment

**Afternoon (2.5 hours): Practice**
- Design architecture for:
  - Multi-tenant application
  - Global application (i18n, multiple regions)
  - Offline-first application
- Discuss trade-offs for each

---

### Day 76: Trade-offs & Scalability
**Time: 4.5 hours**

**Morning (2 hours): Study**
- Common trade-offs in frontend:
  - Performance vs maintainability
  - SSR vs CSR vs SSG
  - Monolith vs micro-frontends
  - REST vs GraphQL
  - Client state vs server state
- Scalability patterns
- Monitoring and observability

**Afternoon (2.5 hours): Practice**
- Revisit previous designs
- Identify trade-offs made
- Discuss alternatives
- Plan for scale (10x, 100x traffic)

---

### Day 77: System Design Phase Test
**Time: 4.5 hours**

**Morning (1.5 hours): Review**
- Review all system designs
- Consolidate patterns
- Create design checklist

**Afternoon (1.5 hours): Practice**
- Redesign 2 systems from scratch
- Time yourself (45 mins each)

**Evening (1.5 hours): TEST WITH ME**
- Post "Phase 4 complete, ready for system design test"
- Design 1 complete system live (1 hour)
- Must cover:
  - Requirements
  - Architecture
  - State management
  - Performance
  - Accessibility
  - Trade-offs
- I'll interrupt with follow-ups

---

# PHASE 5: Final Preparation & Mock Interviews (Days 78-84)

### Day 78: Behavioral Preparation
**Time: 4.5 hours**

**Morning (2 hours): Prepare Stories**
- STAR method (Situation, Task, Action, Result)
- Prepare 10 stories:
  - Leadership/ownership
  - Conflict resolution
  - Technical decision
  - Failure and learning
  - Challenging project
  - Performance optimization
  - Scalability challenge
  - Team collaboration
  - Tight deadline
  - Innovation

**Afternoon (2 hours): Practice**
- Record yourself answering
- Refine each story to 2-3 mins
- Practice conciseness

**Evening (30 mins): Company Research**
- Research target companies
- Understand their products
- Read engineering blogs

---

### Day 79: Full Mock Interview - JavaScript
**Time: 4.5 hours**

**Full Mock Interview with Me (2 hours):**
- JavaScript fundamentals (30 mins)
- Coding problem (45 mins)
- System discussion (45 mins)

**Post-Interview (2.5 hours):**
- Review feedback
- Fix weak areas
- Redo failed questions
- Practice improvements

---

### Day 80: Full Mock Interview - React
**Time: 4.5 hours**

**Full Mock Interview with Me (2 hours):**
- React concepts (30 mins)
- Build feature live (1 hour)
- Performance optimization (30 mins)

**Post-Interview (2.5 hours):**
- Review feedback
- Rebuild feature better
- Practice verbal explanations

---

### Day 81: Full Mock Interview - System Design
**Time: 4.5 hours**

**Full Mock Interview with Me (1.5 hours):**
- Design complete system
- Handle follow-ups
- Discuss trade-offs

**Post-Interview (3 hours):**
- Review feedback
- Redesign with improvements
- Create final design templates

---

### Day 82: Problem Solving Marathon
**Time: 4.5 hours**

**Full Day: Timed Problem Solving**
- 2 easy LeetCode (15 mins each)
- 4 medium LeetCode (30 mins each)
- 2 hard LeetCode (45 mins each)

**No breaks between problems - simulate real conditions**

**Evening:** Review solutions, note patterns

---

### Day 83: Weak Area Blitz
**Time: 4.5 hours**

**Identify Your Top 3 Weakest Areas:**
- From all tests and mocks
- Spend 1.5 hours on each

**Practice:**
- Redo failed questions
- Solve similar problems
- Explain concepts clearly
- Build confidence

---

### Day 84: Final Review & Confidence Building
**Time: 4.5 hours**

**Morning (2 hours): Final Review**
- Skim all notes
- Review JavaScript cheat sheets
- Review React patterns
- Review system design templates
- Review behavioral stories

**Afternoon (1.5 hours): Light Practice**
- 5 easy problems (confidence boost)
- Explain 3 concepts aloud
- Design 1 simple system

**Evening (1 hour): Mental Preparation**
- Visualize successful interview
- Relax and rest
- Prepare logistics (quiet space, internet, etc.)

---

# Vue.js Quick Wrap-up (Optional: 1-2 Days)

## If You Need Vue.js Coverage

### Vue.js Day 1: Core Concepts
**Time: 4.5 hours**

**Morning (2 hours):**
- Vue instance and lifecycle
- Template syntax
- Directives (v-if, v-for, v-bind, v-on)
- Computed properties vs methods
- Watchers

**Afternoon (2 hours):**
- Components (props, events)
- Slots
- Component communication
- Vuex basics (state management)

**Evening (30 mins):**
- Vue vs React comparison
- When to use what

### Vue.js Day 2: Advanced (Optional)
**Time: 4.5 hours**

**Morning (2 hours):**
- Composition API
- Vue Router
- Lifecycle hooks
- Performance optimization

**Afternoon (2 hours):**
- Build small Vue app
- Compare to React implementation

---

# Daily Routine Structure

## How to Use Your 4.5 Hours

**Standard Day Structure:**

1. **Morning Block (2-2.5 hours):**
   - Study new concepts
   - Watch videos / read documentation
   - Take notes

2. **Afternoon Block (2 hours):**
   - Practice coding
   - Solve problems
   - Build projects
   - Implement concepts

3. **Evening Block (30-60 mins):**
   - Review and consolidate
   - Test with me (on test days)
   - Prepare for next day

**Test Days:**
- Reduced study time
- More practice time
- 1 hour test with me

---

# Study Resources

## JavaScript
- JavaScript.info (complete guide)
- "You Don't Know JS" book series (GitHub)
- MDN Web Docs
- Lydia Hallie's JavaScript Questions (GitHub)
- JS Visualized series

## React
- Official React Docs (new beta docs)
- Kent C. Dodds Epic React
- "React - The Complete Guide" (Udemy)
- React TypeScript Cheatsheet

## Next.js
- Official Next.js Docs
- Next.js 13+ tutorials
- Vercel guides

## DSA
- LeetCode (primary platform)
- "Grokking Algorithms" book
- NeetCode roadmap
- AlgoExpert (optional)

## System Design
- GreatFrontEnd System Design
- Frontend Interview Handbook
- "Designing Data-Intensive Applications" (relevant chapters)
- Company engineering blogs

---

# Testing Schedule

**JavaScript Tests:**
- Day 2, 5, 7, 12, 20, 28

**React Tests:**
- Day 35, 42, 49

**DSA Test:**
- Day 63

**System Design Test:**
- Day 77

**Mock Interviews:**
- Days 79, 80, 81

---

# Success Criteria

## To Move Forward from Each Phase:

**Phase 1 (JavaScript):** 80%+ on comprehensive test
**Phase 2 (React):** 80%+ on React test + can build features
**Phase 3 (DSA):** Solve 3/3 problems correctly in test
**Phase 4 (System Design):** Complete system design with good coverage
**Phase 5:** Pass mock interviews with strong performance

---

# Important Notes

1. **Don't Skip Tests:** If you fail a test, repeat that section before moving forward

2. **Daily Commitment:** 4.5 hours is non-negotiable—consistency matters more than intensity

3. **Ask for Help:** If stuck >30 mins, post question and move to next topic

4. **Practice Out Loud:** Explain concepts aloud—critical for interviews

5. **Code by Hand:** Practice writing code without autocomplete

6. **Time Yourself:** Simulate real interview pressure

7. **Stay Honest:** Don't look at solutions immediately—struggle builds skill

8. **Rest Days:** Take 1 full rest day per week (e.g., Sunday)

9. **Track Progress:** Mark completed items daily

10. **Interview Applications:** Start applying on Day 70 (interviews take 2-3 weeks to schedule)

---

# Ready to Start?

Post "Starting Day 1" when you're ready to begin.

I'll be here to:
- Clarify concepts when stuck
- Administer tests
- Conduct mock interviews
- Adjust the plan if needed
- Push you when you're slacking
- Support you through the journey

**Remember:** This is a marathon, not a sprint. Trust the process, stay consistent, and you'll be ready in 84 days.

Let's build your future. Go.