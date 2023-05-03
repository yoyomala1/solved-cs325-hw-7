Download Link: https://assignmentchef.com/product/solved-cs325-hw-7
<br>



<ol>

 <li>Let X and Y be two decision problems. Suppose we know that X reduces to Y in polynomial time. Which of the following can we infer? Explain.

  <ol>

   <li>If Y is NP-complete then so is X.</li>

   <li>If X is NP-complete then so is Y.</li>

   <li>If Y is NP-complete and X is in NP then X is NP-complete.</li>

   <li>If X is NP-complete and Y is in NP then Y is NP-complete.</li>

   <li>If X is in P, then Y is in P.</li>

   <li>If Y is in P, then X is in P.</li>

  </ol></li>

 <li>Consider the problem COMPOSITE: given an integer <em>y</em>, does <em>y </em>have any factors other than one and itself? For this exercise, you may assume that COMPOSITE is in NP, and you will be comparing it to the well-known NP-complete problem SUBSET-SUM: given a set S of <em>n </em>integers and an integer target <em>t</em>, is there a subset of <em>S </em>whose sum is exactly <em>t</em>?  Clearly explain whether or not each of the following statements follows from that fact that COMPOSITE is in NP and SUBSET-SUM is NP-complete:

  <ol>

   <li>SUBSET-SUM ≤p</li>

   <li>If there is an <em>O</em>(<em>n</em><sup>3</sup>) algorithm for SUBSET-SUM, then there is a polynomial time algorithm for COMPOSITE.</li>

   <li>If there is a polynomial algorithm for COMPOSITE, then P = NP.</li>

   <li>If P  NP, then <strong><em>no</em></strong> problem in NP can be solved in polynomial time.</li>

  </ol></li>

 <li><em> </em>A Hamiltonian path in a graph is a simple path that visits every vertex exactly once. Prove that HAM-PATH = { (G, u, v ): there is a Hamiltonian path from u to v in G }  is NP-complete.  You may use the fact that HAM-CYCLE is NP-complete.</li>

 <li><em>) </em>K-COLOR. Given a graph G = (V,E), a k-coloring is a function c: V -&gt; {1, 2, … , k} such that c(u)  c(v) for every edge (u,v)   In other words the number 1, 2, .., k represent the k colors and adjacent vertices must have different colors.  The decision problem K-COLOR asks if a graph can be colored with at most K colors.

  <ol>

   <li>The 2-COLOR decision problem is in P. Describe an efficient algorithm to determine if a graph has a 2-coloring.  What is the running time of your algorithm?</li>

  </ol></li>

</ol>




<ol>

 <li>It is known that the 3-COLOR decision problem is NP-complete by using a reduction from SAT. Use the fact that 3-COLOR is NP-complete to prove that 4-COLOR is NP-complete.</li>

</ol>


