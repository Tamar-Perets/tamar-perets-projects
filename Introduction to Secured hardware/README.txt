# Cybersecurity & Hardware Security Projects

Introduction to Secured Hardware

1. Cryptanalysis Challenges
* **Description:** Breaking Vigenère, Hill, and advanced ciphers using cryptanalysis techniques to recover keys and hidden plaintexts with a known block size of 5.

2. Timing Attack Password Recovery
* **Description:** Exploiting string-comparison timing variances to execute a timing attack, recovering a masked password up to 100 characters long.

3. Correlation Power Analysis (CPA) Attack
* **Description:** Recovering a secret cryptographic key from hardware FPGA power traces (SBOX(p ⊕ k)) using CPA across Hamming Weight, Hamming Distance, and Value models.

4. Differential Power Analysis (DPA) Attack
* **Description:** Characterizing a target hardware system and executing a statistical DPA attack via ChipWhisperer to recover a verified ID byte-by-byte from power consumption traces.  

5. Template Attack
* **Description:** Implementing a profiling-based Template Attack (Training and Attack phases) via ChipWhisperer on an AES encryption function to successfully extract the secret key. 

---
*Note: These implementations are contained within Jupyter Notebooks (`.ipynb`), showcasing both the underlying logic and executed outputs.*