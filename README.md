# AI Foundations I: The Lost Book of Perceptrons

**CyLabs Security Academy Learning Path**  
**Event:** June 16 – June 29, 2026  
**Difficulty:** Easy  
**Status:** Completed (16/16 challenges)

A comprehensive journey through AI fundamentals, starting with perceptron black-box experimentation and progressing to mathematical understanding, manual design, automated training, and ethical considerations.

---

## Complete Challenge List

### Phase 1: Recovering Clues (Black-Box Exploration)

#### 1. **Neuron Meet 0** | 1 pt
Probe a 1D perceptron over the network using binary search to find the decision boundary, then generate the 8-bit pattern `01110000` (ASCII 'p').

**Connection:** `nc aureolin-pixie.cylabacademy.net 58918`  
**Key Technique:** Binary search to locate threshold  
**Output:** ASCII pattern generation via boundary knowledge

#### 2. **Neuron Meet 2D-0** | 1 pt
Extend the 1D technique to 2D: probe a 2D perceptron with (x, y) coordinate pairs to find the linear decision boundary, then generate the same ASCII pattern.

**Connection:** `nc aureolin-pixie.cylabacademy.net 50601`  
**Key Technique:** 2D binary search; linear boundary in plane  
**Output:** ASCII pattern via 2D coordinate pairs

---

### Phase 2: Reading Restored Pages (Mathematical Expression)

#### 3. **Neuron Express 0** | 1 pt
Translate 1D perceptron behavior into mathematical form: **w·x + b**

Given a 1D perceptron's decision boundary, express the underlying weight and bias as a linear equation.

**Connection:** `nc aureolin-pixie.cylabacademy.net 59148`  
**Key Technique:** TEST command to verify guesses  
**Output:** Correct (w, b) pair

#### 4. **Neuron Express 2D-0** | 1 pt
Extend to 2D: express a 2D perceptron as **w₁·x + w₂·y + b**

**Connection:** `nc aureolin-pixie.cylabacademy.net 50783`  
**Key Technique:** Systematic testing to isolate weights and bias  
**Output:** Correct (w₁, w₂, b) triple with integers

---

### Phase 3: Rebuilding the Craft (Manual Design)

#### 5. **Perceptron Play 1D Alpha** | 1 pt
Design a 1D perceptron manually: given labeled points, find (w, b) that correctly classify all of them.

**Connection:** `http://aureolin-pixie.cylabacademy.net:63518`  
**Key Technique:** Geometric reasoning; threshold placement  
**Output:** Correct weight and bias values

#### 6. **Perceptron Play Alpha** | 1 pt
Design a 2D perceptron: given scattered labeled points in 2D space, find (w₁, w₂, b) that separate the two categories with a single line.

**Connection:** `http://aureolin-pixie.cylabacademy.net:63445`  
**Key Technique:** Real-time ASCII visualization; iterative tuning  
**Output:** Separating line parameters

#### 7. **Perceptron Play Naught** | 1 pt
Another 2D classification task with a different dataset. Same approach, new challenge.

**Connection:** `http://aureolin-pixie.cylabacademy.net:63532`  
**Key Technique:** Pattern recognition; boundary visualization  
**Output:** Correct perceptron parameters

---

### Phase 4: Automation (Learning Algorithms)

#### 8. **Perceptron Train Classic 0** | 1 pt
Implement the perceptron learning algorithm: find any learning rate that converges to correct classification.

**Connection:** `http://aureolin-pixie.cylabacademy.net:55349`  
**Key Technique:** Learning rate selection; convergence observation  
**Output:** Successfully trained model

#### 9. **Perceptron Train Classic 1** | 1 pt
Find 5 different learning rates that successfully train the perceptron on a given dataset.

**Connection:** `http://aureolin-pixie.cylabacademy.net:61578`  
**Key Technique:** Hyperparameter tuning; binary search for good rates  
**Output:** 5 distinct learning rates achieving 100% accuracy

#### 10. **Perceptron Train Classic 2 Alpha** | 1 pt
Find 5 learning rates on a more challenging (less linearly separable) dataset.

**Connection:** `http://aureolin-pixie.cylabacademy.net:63432`  
**Key Technique:** Hyperparameter sensitivity; strategic rate selection  
**Output:** 5 learning rates that converge despite noisier data

---

### Phase 5: Understanding Limitations (Non-Linearly Separable Problems)

#### 11. **Perceptron Train XOR** | 1 pt
Attempt to train on XOR data. Recognize that a single perceptron cannot achieve 100% accuracy.

**Connection:** `http://aureolin-pixie.cylabacademy.net:51749`  
**Goal:** Reach 75% accuracy; understand why 100% is impossible  
**Key Insight:** XOR requires non-linear decision boundary

#### 12. **Perceptron Train XNOR** | 1 pt
Similar to XOR: train on XNOR (exclusive nor) data and recognize the limitation.

**Connection:** `http://aureolin-pixie.cylabacademy.net:50580`  
**Goal:** Reach 75% accuracy  
**Key Insight:** Mathematical structure of problem determines solvability

#### 13. **Perceptron Train Hole in Middle** | 1 pt
Classify a "hole in middle" pattern: positive points surrounding a negative center. Inherently non-linearly separable.

**Connection:** `http://aureolin-pixie.cylabacademy.net:49472`  
**Goal:** Reach 88.9% accuracy  
**Key Insight:** Spatial topology limits linear classifiers

#### 14. **Perceptron Train 3-Bit Parity** | 1 pt
Classify based on parity (even/odd count of 1s in 3-bit numbers) in 3D space.

**Connection:** `http://aureolin-pixie.cylabacademy.net:54852`  
**Goal:** Reach 75% accuracy  
**Key Insight:** Parity problems demonstrate fundamental perceptron limits

---

### Phase 6: Guarding the Archive (Ethics & Critical Thinking)

#### 15. **Trust But Verify** | 1 pt
Interactive fiction: explore verification strategies when AI outputs seem confident but may be wrong.

**Connection:** `nc aureolin-pixie.cylabacademy.net 59653`  
**Key Concept:** Verification, fact-checking, critical evaluation  
**Output:** Understand practical AI safety habits

#### 16. **Assistant or Agent?** | 1 pt
Interactive fiction: explore the difference between AI assistants and agents, and ethical implications.

**Connection:** `nc aureolin-pixie.cylabacademy.net 61332`  
**Key Concept:** Autonomy, permissions, guardrails, responsibility  
**Output:** Understand when to use different AI modalities

---

## Learning Progression

1. **Empirical Discovery** → Treat perceptrons as black boxes; probe to understand behavior
2. **Mathematical Expression** → Convert observed behavior into equations
3. **Design & Construction** → Manually create perceptrons to solve problems
4. **Automation** → Use algorithms to find solutions automatically
5. **Limitation Recognition** → Understand what perceptrons cannot do
6. **Ethical Integration** → Consider responsibilities and verification

---

## Key Concepts Covered

- **Decision Boundaries:** Linear separation in 1D, 2D, and higher dimensions
- **Binary Search:** Efficient exploration of continuous spaces
- **Weight & Bias:** Parameters that define perceptron behavior
- **Learning Algorithms:** Iterative parameter adjustment based on errors
- **Hyperparameter Tuning:** Learning rate selection and sensitivity analysis
- **Linearly Separable vs. Non-Separable:** Mathematical distinction affecting solvability
- **AI Ethics:** Trust, verification, autonomy, and responsibility

---

## Technologies & Concepts

- **Perceptrons:** Foundational building block of neural networks
- **Linear Classification:** Binary decision via linear functions
- **Supervised Learning:** Learning from labeled examples
- **Network Communication:** Netcat and HTTP-based challenge interfaces
- **Interactive Visualization:** ASCII plots and real-time feedback
- **Ethical Reasoning:** Critical thinking about AI systems

---

## Event Information

- **Platform:** CyLab Security Academy (Carnegie Mellon University)
- **Institution:** CMU CyLab Security and Privacy Institute
- **Type:** Non-competitive, self-paced learning event
- **Registration:** June 15, 2026 4:00 AM – June 29, 2026 4:00 AM
- **Event Duration:** June 16, 2026 12:00 AM – June 29, 2026 4:00 AM
- **Total Challenges:** 16
- **Points:** 16 (1 pt each)

---

## Repository Structure

```
ai-foundations-i-perceptrons/
├── README.md                        # This file
├── CHALLENGES.md                    # Detailed challenge guide
├── .gitignore                       # Git ignore rules
├── solutions/
│   ├── neuron_meet_0.py
│   ├── neuron_meet_2d_0.py
│   ├── neuron_express_0.py
│   ├── neuron_express_2d_0.py
│   └── [remaining solutions]
├── notes/
│   ├── perceptron_theory.md
│   ├── learning_rates.md
│   └── ethics_considerations.md
└── screenshots/
    └── [challenge screenshots]
```

---

## Key Insights & Takeaways

1. **Understanding from First Principles:** Start with observation, move to theory, then to application.

2. **Linear Algebra Matters:** Perceptrons are linear; their power and limitations are determined by linear algebra.

3. **Hyperparameters are Critical:** A tiny change in learning rate can mean convergence or divergence.

4. **Not All Problems Are Equal:** Some problems are fundamentally unsolvable by linear models, regardless of effort.

5. **Ethics ≠ Separate:** Responsible AI is integrated into every design decision, not bolted on afterward.

6. **Verification is Essential:** Confident output ≠ correct output. Always verify.

7. **Limitations are Features:** Understanding what your tools cannot do is as important as understanding what they can.

---

## Notes for Continuation

To complete the repository with full solution code and approach documentation:

1. For each challenge, document:
   - Problem statement and connection details
   - Key insights and approach strategy
   - Sample solution (if applicable)
   - Output/flag format

2. Add working scripts for network-based challenges (netcat)

3. Include screenshots from the learning path for visual reference

4. Create a study guide linking challenges to fundamental concepts

---

## Contact & References

- **GitHub Handle:** 6876h9
- **Platform:** CyLab Security Academy
- **Official Site:** https://cylabacademy.org/

---

**Completed:** June 26, 2026  
**Repository Version:** 2.0 (Complete Challenge Coverage)
