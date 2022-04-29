# Three-Input NPN Gate Library for Silicon Atomic Quantum-dot Circuits

This repository provides supplementary data for the paper *Three-input NPN Class Gate Library for Atomic Silicon Quantum-dot* by Maria D. Vieira, Samuel S. H. Ng, Marcel Walter, Robert Wille, Konrad Walus Ricardo S. Ferreira, Omar P. Vilela Neto, José A. M. Nacif published in Design&Test 2022.

## 3-input SiDB based gates

All proposed 3-input gates that compose our library are included in the `gates` directory. Each one of those gates corresponds to one Negation-Permutation-Negation(NPN) class.

Those designs are named:
* `and:` x ∧ y ∧ z 
* `majority[1]:`〈xyz〉
* `orand[2]:` x ∧ (y ∨ z) 
* `onehor:` x ∧  ̄y ∧  ̄z ⊕  ̄x ∧ y ∧  ̄z ⊕  ̄x ∧  ̄y ∧ z
* `xor[1]:` x ⊕ y ⊕ z
* `mux:` x ? y : z
* `andxor:` x ⊕ y ∧ z 
* `xorand:` x ∧ (y ⊕ z)
* `dot:` x ⊕ (z ∨ x ∧ y) 
* `gamble:` x ∧ y ∧ z ⊕  ̄x ∧  ̄y ∧  ̄z 

[1] A. N. Bahar, K. A. Wahid, S. S. Ahmadpour, and M. Mosleh, “Atomic silicon quantum dot: A new designing paradigm of an atomic logic circuit,” IEEE Transactions on Nanotechnology, vol. 19, 2020.

[2] M. D. Vieira, I. G. S. Moreira, P. A. R. L. Silva, L. O. Luz, R. S. Ferreira,O. P. Vilela Neto, and J. A. M. Nacif, “Novel three-input gates for silicon quantum dot,” in 2021 34th SBC/SBMicro/IEEE/ACM Symposium on Integrated Circuits and Systems Design (SBCCI), 2021, pp. 1–6.

## Operational domain

The operational domain of the SiDB-based *AND* desing is available in the `operational_domain` directory.  
