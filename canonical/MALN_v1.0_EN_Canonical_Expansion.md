# WLRT / WaveCounter  
# Multi-Asset Liquidity Networks (MALN)  
## Canonical Start v1.0  
### English Working Fixation

---

## 0. Document Status

This document defines the initial theoretical foundation of Multi-Asset Liquidity Networks (MALN) as a distinct layer within the Wave Liquidity Redistribution Theory (WLRT) / WaveCounter framework.

Status:

MALN v1.0 = canonical starting framework, but not yet a complete formal mathematical theory.

At this stage, we fix:

- the object of study  
- the base ontology  
- the topological nature of high-dimensional liquidity systems  
- the operator-based dynamics of fragility  
- the principle of optimal complexity  
- the transition to spectral control  

Not yet fixed:

- specific metrics  
- numerical formulations (LFI/MALN)  
- operational control algorithms  
- full mathematical stability theory  

---

## 1. Core Transition

n ↑ ⇒ Liquidity Pool → Directed Liquidity Network

Meaning:

For a small number of assets, the system can be described as a pool.  
With increasing dimensionality, it ceases to be a simple aggregation and becomes a directed liquidity network.

---

### Canonical Statement 1

A high-dimensional liquidity system is a directed topological network.

---

## 2. Base Object

G = (V, E)

Where:

- V — set of nodes  
- E — set of directed edges  

A node represents a local carrier of liquidity.  
An edge represents an admissible directed channel for the transfer of liquidity, fragility, cost, and transition regime.

---

## 3. Nodes

v_i = (a_i, c_i, r_i, ε_i, F_i(t), E_i(t), S_i(t))

Where:

- a_i — asset class  
- c_i — functional role  
- r_i — structural status  
- ε_i — observation scale  
- F_i(t) — local fragility  
- E_i(t) — local energy  
- S_i(t) — state  

---

### Canonical Statement 2

A MALN node is not simply an asset; it is a local carrier of liquidity defined by role and state.

---

## 4. Edges

e_ij = (A_ij, w_ij, ε_ij, E_ij, D_ij)

---

### Canonical Statement 3

e_ij ≠ e_ji

---

### Implication

Liquidity and fragility transmission are directional.

---

## 5. Routes

R(i → j)

---

### Canonical Statement 4

Different routes between the same nodes are not equivalent.

---

### Implication

Routes affect:

- fragility  
- cost  
- observability  
- admissibility  
- speed  
- residual system state  

---

## 6. Non-locality

S_i(t) = f(N(i), G, F(t))

---

### Canonical Statement 5

Node state is structurally non-local.

---

## 7. Clusters and Hierarchy

System levels:

- nodes  
- clusters  
- inter-cluster links  
- full network  

---

### Canonical Statement 6

Flat control of a high-dimensional liquidity network is structurally invalid.

---

## 8. ε-field

ε: V ∪ E → ℝ⁺

---

### Invariant

ε_i ~ ε_ij ~ ε_j

---

### Canonical Statement 7

Violation of ε-consistency leads to loss of observability.

---

## 9. System Energy

E_total = ΣE_i + ΣE_ij

---

### Canonical Statement 8

System energy is determined by topology, not only by nodes.

---

## 10. Fragility

F_i(t), F(t)

F(t+1) = D F(t) + Pᵀ F(t) + η(t)

---

### Canonical Statement 9

Fragility is a propagating quantity.

---

## 11. Full Operator

F(t+1) = L F(t) + η(t)

L = D + Pᵀ

---

### Canonical Statement 10

L is the fragility evolution operator.

---

## 12. Cascades

ρ(L) > 1 ⇒ cascade

---

### Canonical Statement 11

A cascade is a regime where fragility amplifies through the network.

---

## 13. Spectral Structure

λ_k ∈ spectrum(L)

---

### Canonical Statement 12

System stability is determined by the spectrum of L.

---

## 14. Modes

F(t) = Σ α_k v_k

---

### Canonical Statement 13

Fragility propagates through eigenmodes of the network.

---

## 15. Fragility Centrality

C_i = Σ |v_k(i)| g(λ_k)

---

### Canonical Statement 14

Critical nodes are those participating in dominant fragility modes.

---

## 16. Bridges

---

### Canonical Statement 15

Breaking a bridge produces a disproportionate effect.

---

## 17. Network Fragility

F_net ≠ ΣF_i

---

### Canonical Statement 16

Network fragility is not equal to the sum of local fragilities.

---

## 18. Complexity

B(n), Q(n)

Π(n) = B(n) − Q(n)

---

## 19. Optimal Complexity

n* = argmax Π(n)

---

### Canonical Statement 17

The system has an optimal dimensionality.

---

## 20. Admissibility Limit

F_net ≤ F_crit

n_max

---

### Key Difference

n* ≠ n_max

---

## 21. Optimal Complexity Rule

System growth is admissible only if efficiency increases.

---

### Canonical Statement 18

Adding an asset is valid only if it improves the network, not just increases size.

---

## 22. Extended Form

Π(n) = χ_ε B(...) − Q(...)

---

## 23. Control

F(t+1) = L F(t) + u(t)

---

### Canonical Statement 19

Control of MALN = control of operator L.

---

## 24. Spectral Control

---

### Canonical Statement 20

Liquidity control = control of the fragility spectrum.

---

## 25. Minimal Deformation Principle

---

### Canonical Statement 21

Optimal control minimally deforms topology.

---

## 26. Local vs Global Control

---

### Canonical Statement 22

Local actions can produce global spectral changes.

---

## 27. Critical Nodes

---

### Canonical Statement 23

Control is achieved through a limited set of critical nodes.

---

## 28. Main Hypothesis

System stability is determined by topology and fragility dynamics.

---

## 29. Relation to WLRT

- WLRT — environment and fragility  
- WaveCounter — structure  
- DLAT — admissibility  
- MALN — topology  

---

### Canonical Relation

WLRT = local physics  
MALN = global dynamics  

---

## 30. Unifying Formula

Fragility = distance to inadmissibility in a topological liquidity system

---

## 31. Canonical Set

(список сохраняется структурно — можно оставить или сократить при необходимости)

---

## 32. Not Yet Canonical

(аналогично RU)

---

## 33. Final Formulation

MALN treats high-dimensional liquidity systems as directed topological networks with propagating fragility.

---

## 34. Short Form

MALN = theory of directed topological liquidity networks with propagating fragility.

---

## 35. Stop Point

MALN v1.0 is considered fixed at this stage.
