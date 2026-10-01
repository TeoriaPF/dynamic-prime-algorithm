markdown
# Dynamic Modulo Algorithm for Prime Number Generation

An experimental research project in computational mathematics that explores the generation of prime numbers using a dynamic, self-feeding algorithm (feedback loop).

## 📌 Project Overview
This project originated as an experimental mental journey to challenge the notion of whether a linear formula for prime numbers could be constructed. It documents 4 distinct phases of logical progression:

1. **Hypothesis 1:** Using the basic formula `(2 * 3) +/- 1` and expanding it. *(Result: Blocked very early on)*.
2. **Hypothesis 2 (Dynamic):** Introducing the formula `(p1 * p2) +/- d`, where `d` represents the dynamic distance between consecutive primes (*Prime Gaps*). *(Result: Left logical "holes" by missing primes like 29)*.
3. **Hypothesis 3 (Addition):** Shifting to the operation `(p1 + p2) +/- d` to slow down rapid growth. *(Result: Completely blocked due to parity rules yielding only even numbers)*.
4. **Hybrid Solution (100% Accuracy):** Building an algorithm that integrates modular arithmetic principles with an automated gap-checking mechanism (*Sieve & Wheel Factorization Hybrid*).

## 🚀 How the Algorithm Works
The algorithm initializes with a minimal base array `B =`. It dynamically multiplies pairs and calculates the distance `d` to the next sequential prime. Before advancing to the next prime family, an intelligent checking function scans the remaining space behind to catch and fill any prime numbers that were skipped by the multiplication, ensuring 100% accuracy toward infinity.

## 🛠️ Execution
To run this project locally, ensure you have Python installed and execute the following command:

```bash
python prime_algorithm.py
```

## 📈 Scientific Conclusion
This project experimentally demonstrates that prime numbers behave as "isolated i
