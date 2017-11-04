
SRCSP (Stochastic Resource Constrained Shortest Path)

- Shortest Path in a graph given : 
  - Weight on the vertices
  - Source node s
  - Sink node t
  - Stochastic resource consumption on a vertex (K resources)

II) Formulation
  Max Pr { a_k * x <= d_k | k = 1..K } with constraints:
    - c * x <= C
    - Mx = b
    - x in {0, 1}^n

  Given that:
  - The length of x is the number of vertices (x is a binary vector, x(e) = 1 <=> e is in the path P)
  - The length of a_k is the number of vertices (a_k(e) is normally distributed and they are all independent)
  - C is the maximum allowed weight of the path
  - M is the node-arc incidence matrix (M[i,e] = 1 if e = (., i), -1 if e = (i, .), 0 otherwise)
  - b is a vector with 0 everywhere except 1 for s (source node), -1 for t (sink node)


III) K = 1 (one resource)

IV) Joint Probability Constraints

V) Individually Relaxed




ETAT DE L'ART	
