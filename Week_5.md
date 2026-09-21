# 🚀 VisionX Season 2

**Organized by:** MSC-PRPCEM, Global AI Amravati, and P.R. Pote Patil College of Engineering and Management

**Event Type:** Online Quiz Competition (Every Monday)

**Date & Time:** 23rd August – 27th September 2026

---

## Quiz Questions

### Question 1

**Question:** A hash table uses open addressing with linear probing. Under a high load factor, which phenomenon most directly explains the degradation in expected lookup performance?

- **A.** Primary clustering
- **B.** Tree imbalance
- **C.** External fragmentation
- **D.** Path compression

**Correct Answer:** A

**Question Type:** Single Choice

**Explanation:** Linear probing causes primary clustering: consecutive occupied slots form long runs, increasing probe lengths as the table becomes crowded.

---

### Question 2

**Question:** An array contains n distinct elements. What is the tightest worst-case time complexity of finding whether any two elements sum to a target if the array is first sorted and then processed with two pointers?

- **A.** O(n)
- **B.** O(log n)
- **C.** O(n log n)
- **D.** O(n²)

**Correct Answer:** C

**Question Type:** Single Choice

**Explanation:** Sorting takes O(n log n), while the two-pointer scan takes O(n), so the total is O(n log n).

---

### Question 3

**Question:** In a directed acyclic graph (DAG), which technique can produce a valid ordering in which every directed edge u→v places u before v?

- **A.** Topological sorting
- **B.** Dijkstra's algorithm
- **C.** Union-Find
- **D.** Floyd–Warshall

**Correct Answer:** A

**Question Type:** Single Choice

**Explanation:** Topological sorting orders vertices so every directed edge goes from an earlier vertex to a later vertex; it exists for DAGs.

---

### Question 4

**Question:** A binary search tree is constructed by inserting keys in strictly increasing order. What is the resulting worst-case height in terms of n?

- **A.** O(log n)
- **B.** O(n log n)
- **C.** O(1)
- **D.** O(n)

**Correct Answer:** D

**Question Type:** Single Choice

**Explanation:** Increasing insertion order creates a degenerate chain, so the height is n-1, which is O(n).

---

### Question 5

**Question:** Which statement about AVL-tree rotations is correct after an insertion causes an LL imbalance?

- **A.** A left rotation at the unbalanced node is required
- **B.** A right rotation at the unbalanced node is required
- **C.** A left-right double rotation is required
- **D.** No rotation is required

**Correct Answer:** B

**Question Type:** Single Choice

**Explanation:** An LL imbalance is corrected with a single right rotation at the first unbalanced node.

---

### Question 6

**Question:** For a connected weighted graph with non-negative edge weights, which algorithm is designed to compute shortest paths from one source to all vertices?

- **A.** Dijkstra's algorithm
- **B.** Kruskal's algorithm
- **C.** Prim's algorithm
- **D.** Kosaraju's algorithm

**Correct Answer:** A

**Question Type:** Single Choice

**Explanation:** Dijkstra's algorithm computes single-source shortest paths when edge weights are non-negative.

---

### Question 7

**Question:** What is the worst-case time complexity of deleting a node with a known pointer from a doubly linked list when its predecessor and successor links can be updated directly?

- **A.** O(n)
- **B.** O(log n)
- **C.** O(1)
- **D.** O(n log n)

**Correct Answer:** C

**Question Type:** Single Choice

**Explanation:** With a direct pointer to the node, only its neighboring links need updating, so deletion is O(1).

---

### Question 8

**Question:** Which recurrence best represents the running time of merge sort on n elements?

- **A.** T(n)=T(n-1)+O(1)
- **B.** T(n)=2T(n/2)+O(n)
- **C.** T(n)=T(n/2)+O(1)
- **D.** T(n)=2T(n-1)+O(n)

**Correct Answer:** B

**Question Type:** Single Choice

**Explanation:** Merge sort recursively sorts two halves and merges them in linear time: T(n)=2T(n/2)+O(n).

---

### Question 9

**Question:** A min-heap contains n elements. After decreasing the key of a node, which operation restores the heap property when the node may now be smaller than its parent?

- **A.** Sift down
- **B.** Heapify the entire array
- **C.** Sift up
- **D.** Level-order traversal

**Correct Answer:** C

**Question Type:** Single Choice

**Explanation:** A decreased key may violate the parent-child relation upward, so the node is repeatedly swapped with its parent using sift-up.

---

### Question 10

**Question:** For an adjacency-list representation of a sparse graph, which traversal complexity is tight when every vertex and edge must be examined?

- **A.** O(V+E)
- **B.** O(V²)
- **C.** O(E log E)
- **D.** O(VE)

**Correct Answer:** A

**Question Type:** Single Choice

**Explanation:** BFS and DFS using adjacency lists visit each vertex and inspect each edge, giving O(V+E).

---

### Question 11

**Question:** Select the statements that correctly describe amortized analysis of a dynamic array that doubles its capacity. (Select all that apply)

- **A.** A single resize can cost O(n).
- **B.** The amortized cost per append is O(1).
- **C.** Every append operation costs O(1) in the worst case.
- **D.** The total cost of n appends is O(n).

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** Resizing copies existing elements and can cost O(n), but resizes occur geometrically, making the amortized append cost O(1) and n appends O(n).

---

### Question 12

**Question:** Identify the properties that are true for a red-black tree. (Select all that apply)

- **A.** Every path from a node to a descendant NIL leaf has the same black height.
- **B.** A red node cannot have a red child.
- **C.** The tree is always a complete binary tree.
- **D.** The root is black in the standard formulation.

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** These are standard red-black invariants. Completeness is not required.

---

### Question 13

**Question:** Choose the statements that are correct about topological sorting. (Select all that apply)

- **A.** It is defined for directed acyclic graphs.
- **B.** A graph can have more than one valid topological ordering.
- **C.** A directed cycle makes a valid topological ordering impossible.
- **D.** It requires the graph to be undirected.

**Correct Answer:** A, B, C

**Question Type:** Multiple Choice

**Explanation:** Topological ordering applies to DAGs; multiple orders may exist, and a directed cycle prevents any valid ordering.

---

### Question 14

**Question:** Select the statements that correctly compare BFS and DFS. (Select all that apply)

- **A.** BFS commonly uses a queue.
- **B.** DFS can be implemented with an explicit stack.
- **C.** BFS always uses less memory than DFS.
- **D.** BFS finds shortest paths in unweighted graphs when starting from the source.

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** BFS uses a queue and gives shortest edge-count paths in unweighted graphs. DFS can use a stack; neither always uses less memory.

---

### Question 15

**Question:** Identify the statements that are true about a graph represented by an adjacency matrix. (Select all that apply)

- **A.** Testing whether an edge (u,v) exists can be O(1).
- **B.** The representation requires O(V²) space.
- **C.** It is usually preferable to an adjacency list for very sparse graphs.
- **D.** It can represent directed graphs using an asymmetric matrix.

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** Adjacency matrices use O(V²) space and allow constant-time edge checks. Directed graphs can have asymmetric matrices.

---

### Question 16

**Question:** Select the statements that correctly describe union-find (disjoint-set union). (Select all that apply)

- **A.** Path compression can reduce the cost of future find operations.
- **B.** Union by rank/size helps keep trees shallow.
- **C.** It is commonly used for cycle detection in undirected graphs.
- **D.** It directly computes shortest paths between all vertex pairs.

**Correct Answer:** A, B, C

**Question Type:** Multiple Choice

**Explanation:** Union-find maintains disjoint sets efficiently and is useful for connectivity and undirected cycle detection; it is not a shortest-path algorithm.

---

### Question 17

**Question:** Choose the valid statements about a monotonic stack. (Select all that apply)

- **A.** It can solve next-greater-element style problems efficiently.
- **B.** Each element is typically pushed and popped at most once in a standard linear-time implementation.
- **C.** It always keeps all elements in globally sorted order.
- **D.** It can reduce some nested-loop array problems from O(n²) to O(n).

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** Monotonic stacks maintain a directional ordering and are used for next greater/smaller problems, often in O(n) total time.

---

### Question 18

**Question:** Identify the statements that are true about dynamic programming. (Select all that apply)

- **A.** It is useful when subproblems overlap.
- **B.** A recurrence can express the relationship between states.
- **C.** Memoization is a top-down approach.
- **D.** Dynamic programming always produces an O(log n) algorithm.

**Correct Answer:** A, B, C

**Question Type:** Multiple Choice

**Explanation:** DP exploits overlapping subproblems and optimal substructure through states/recurrences. Memoization is top-down; DP does not imply a particular complexity.

---

### Question 19

**Question:** Select the statements that correctly describe a trie used for strings. (Select all that apply)

- **A.** Prefix queries can be efficient.
- **B.** Search time can depend on the length of the queried string rather than the number of stored strings.
- **C.** A trie must use exactly one node for every stored string.
- **D.** Shared prefixes can be represented by shared paths.

**Correct Answer:** A, B, D

**Question Type:** Multiple Choice

**Explanation:** Tries share prefix paths, making prefix and string operations dependent largely on query length; they do not require one node per string.

---

### Question 20

**Question:** Choose the statements that are correct about minimum spanning trees (MSTs). (Select all that apply)

- **A.** An MST of a connected weighted undirected graph contains V-1 edges.
- **B.** Kruskal's algorithm can use union-find to avoid cycles.
- **C.** Prim's algorithm grows a spanning tree by repeatedly selecting a minimum-weight crossing edge.
- **D.** An MST is necessarily a shortest-path tree from a chosen source.

**Correct Answer:** A, B, C

**Question Type:** Multiple Choice

**Explanation:** MSTs minimize total edge weight, not source-to-vertex distances. Kruskal uses cycle checks and Prim grows the tree using crossing edges.
