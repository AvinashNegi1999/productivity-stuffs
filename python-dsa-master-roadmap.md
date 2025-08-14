# 🐍 Python + 📊 DSA with Python — Deep Learning Roadmap

> **Goal:** From Python mastery → FAANG-level DSA problem solving.  
> **Pace:** ~15 hrs/week | Single-track | No major courses in parallel.  
> **Method:** Implement from scratch → Analyze complexity → Prove correctness → Test → Optimize.

---

## 📅 Overview Timeline
| Phase | Duration | Focus |
|-------|----------|-------|
| **0** | 1 Week   | Setup & Baseline |
| **1** | 11 Weeks | Python Mastery |
| **2** | 28 Weeks | DSA with Python |
| **Capstone** | 2 Weeks | Project + Mock Interviews |

---

## 📂 Phase 0 — Setup & Baseline (Week 1)
- [ ] Install Python 3.12+, `pyenv`/`venv`, VS Code.
- [ ] Setup `ruff`, `black`, `pytest`, `mypy`, `pre-commit`.
- [ ] Create CLI template (argparse, logging, timers).
- [ ] Bench harness (`timeit`, `perf_counter`), property tests.
- **🎯 Gate:** Repo bootstrapped with CI (lint + tests).

---

## 🐍 Phase 1 — Python Mastery (Weeks 2–12)

### 📌 Weeks 2–4: Core Python, Data Model & Idioms
- [ ] Variables, mutability, slicing, iterators, generators.
- [ ] `__iter__`, `__len__`, `__getitem__`, ordering/hash/equality.
- [ ] Builtins: `list`, `dict`, `set`, `heapq`, `deque`, `bisect` + complexities.
- [ ] **From-scratch:** Dynamic array (amortized analysis), hash map, `OrderedDict`.
- **🎯 Gate:** Explain why dict lookup is avg **O(1)**.

### 📌 Weeks 5–6: OOP, Protocols, Typing
- [ ] OOP vs duck typing, `@dataclass`, ABCs, generics.
- [ ] SOLID principles in Python.
- [ ] **From-scratch:** Plugin system, typed `Vector[T]`.
- **🎯 Gate:** Pass `mypy --strict` on mini-lib.

### 📌 Weeks 7–8: Standard Library & Performance
- [ ] `collections`, `math`, `functools`, `itertools`, `pathlib`, concurrency.
- [ ] Profiling (`cProfile`, `snakeviz`), optimization.
- [ ] **From-scratch:** Parallel map with process pool.
- **🎯 Gate:** Reduce runtime ≥ 25% via profiling.

### 📌 Weeks 9–10: Testing, Debugging, Packaging
- [ ] Unit, property, golden tests; mocking; coverage targets.
- [ ] Debugging (`pdb`, VS Code), structured logging.
- [ ] Packaging with `pyproject.toml`, semver, CLI entry points.
- **🎯 Gate:** Publish a local package with ≥ 90% test coverage.

### 📌 Weeks 11–12: CP-Friendly Python & Internals
- [ ] Recursion limits, iterative DP, fast I/O, custom sort keys.
- [ ] **From-scratch:** Stable mergesort, counting sort, radix sort.
- **🎯 Gate:** Choose optimal builtin DS for scenarios.

---

## 📊 Phase 2 — DSA with Python (Weeks 13–40)

### 🧮 Week 13: Math & Complexity
- [ ] Big-O, Θ, Ω, Master theorem.
- [ ] Proofs: induction, loop invariants, greedy exchange argument.
- **🎯 Gate:** Write invariant for insertion sort.

### 📏 Weeks 14–16: Arrays, Strings, Hashing
- [ ] Two pointers, sliding window, prefix/suffix arrays.
- [ ] **From-scratch:** Rabin–Karp, KMP.
- [ ] 60–70 problems.
- **🎯 Gate:** Prove KMP correctness.

### 🗂 Weeks 17–18: Stacks, Queues, Heaps
- [ ] Monotonic structures, heap variations.
- [ ] **From-scratch:** Binary heap, `MedianFinder`.
- **🎯 Gate:** Amortized proof for queue-with-two-stacks.

### 🔗 Week 19: Linked Lists
- [ ] In-place reversal, Floyd cycle detection.
- [ ] **From-scratch:** Persistent linked list.
- **🎯 Gate:** Explain structural sharing.

### ⚡ Weeks 20–21: Sorting & Binary Search
- [ ] Mergesort, quicksort, randomized select.
- [ ] Binary search patterns (on value/answer).
- **🎯 Gate:** Prove binary search correctness.

### 🌳 Weeks 22–23: Trees & BST
- [ ] Traversals, LCA, AVL/Red-Black Tree.
- **🎯 Gate:** Prove AVL height bound.

### 🔍 Week 24: Tries & String DS
- [ ] Trie, compressed trie, suffix array + LCP.
- **🎯 Gate:** Explain SA sorting + LCP.

### 🌐 Weeks 25–27: Graphs I — Traversals, Shortest Paths, MST
- [ ] BFS, DFS, topo sort, SCC.
- [ ] Dijkstra, 0-1 BFS, Bellman–Ford.
- [ ] MST: Kruskal (DSU), Prim (heap).
- **🎯 Gate:** Prove Dijkstra correctness.

### 💡 Week 28: Greedy
- [ ] Interval scheduling, Huffman coding.
- **🎯 Gate:** Exchange argument proof.

### 🏆 Weeks 29–31: Dynamic Programming
- [ ] 1D/2D DP, LIS, edit distance, bitmask DP.
- [ ] Divide & conquer, monotone queue DP.
- **🎯 Gate:** Derive DP + prove acyclicity.

### 📏 Week 32: Union-Find, Range Structures
- [ ] Segment tree (lazy), Fenwick tree.
- **🎯 Gate:** Prove lazy propagation correctness.

### 🗺 Week 33: Advanced Graphs & LCA
- [ ] Binary lifting, Euler tour, bridges, articulation points.
- **🎯 Gate:** DFS lowlink invariant.

### 🧵 Week 34: Strings II & Math
- [ ] Aho–Corasick, polynomial hash, sieve, combinatorics.
- **🎯 Gate:** Explain hash collision handling.

### 🔁 Week 35: Re-implementation Week
- [ ] Rebuild DSU, Heap, Segment Tree, Trie, LRU from memory.
- **🎯 Gate:** ≥ 60% success rate on hard problems.

### 🎯 Weeks 36–38: Mixed Sets & Mock Interviews
- [ ] Daily: 1 easy, 2–3 medium, 1 hard.
- [ ] 4 mock interviews (algorithms, debugging, DS design).
- **🎯 Gate:** ≥ 80% pass rate.

### 🏁 Weeks 39–40: Capstone
Pick 1:
- [ ] **Competitive Toolkit** (typed DS/Algos library).
- [ ] **Pathfinding Visualizer**.
- [ ] **Indexing Engine**.

---

## 📊 Problem Quotas
| Topic | Target Problems |
|-------|-----------------|
| Arrays/Strings | 70 |
| Hash/Map | 30 |
| Two Pointers | 20 |
| Sliding Window | 25 |
| Stack/Queue | 35 |
| Linked List | 25 |
| Binary Search | 25 |
| Sorting | 10 |
| Trees | 35 |
| Graphs | 55 |
| DP | 70 |
| Heaps | 15 |
| Intervals | 15 |
| Math/Bit | 20 |

---

## 📚 Resources
- **Python Deep**: [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/), [Effective Python](https://effectivepython.com/)
- **DSA Theory**: [CLRS](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/), [CP Handbook](https://cses.fi/book/book.pdf)
- **Practice**: [LeetCode](https://leetcode.com/), [Codeforces](https://codeforces.com/), [CP-Algorithms](https://cp-algorithms.com/)

---

## ✅ Progress Tracking
- [ ] **Phase 0** — Setup
- [ ] **Phase 1** — Python Mastery
- [ ] **Phase 2** — DSA with Python
- [ ] **Capstone Project**
