## Hill Cipher Lab

### Overview
This Mathematica lab provides a hands-on approach to understanding the hill cipher encryption algorithm- a polygraphic substitution cipher rooted in linear algebra.

### Features
We use an alphabet of prime length (p = 29) including letters and some punctuation and implement modular arithmetic to ensure all calculations stay within the defined range. Matrix transformations are used to encode and decode messages, the central idea being that decryption uses the inverse of the encryption matrix.

### Example Commands
```mathematica
(* Encrypting a message *)
P = Transpose[{{8, 9, 4}, {5, 20, 8}, {9, 19, 13}, {5, 19, 19}, {1, 7, 5}}];
M = {{2, 7, 6}, {4, 5, 13}, {2, 6, 1}};
A = Mod[M.P, 29];  (* Resulting cipher matrix *)

(* Decrypting a message *)
InverseM = Inverse[M] * Det[M]^28;
DecryptedMessageP = Mod[InverseM.A, 29];
```

### License
Open-source and available for educational use.
