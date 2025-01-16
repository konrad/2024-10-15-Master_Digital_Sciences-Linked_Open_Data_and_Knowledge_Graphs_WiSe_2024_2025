% Knowledge Graph Refinement: A Survey of Approaches and Evaluation Methods
% Kristan Boettjer
% November 2024

# Outline

1. Generell Information
2. Research Goal
3. Evaluation
4. Methods Used
5. Findings

# 1. Generell Information

**Authors**: Heiko Paulheim, Data and Web Science Group, University of Mannheim 
**Publication Year**: 2016\
**Focus**: The paper surveys methods and evaluation approaches for refining knowledge graphs, with emphasis on enhancing their completeness and correctness


--- 

# 2. Research Goal

## 2.1 Problem 
- Not about creation
- Knowledge Graphs (KG) cannot be 100% complete or correct
- Tradeoff between correctness and completness

## 2.2 Solution
Methods for enhancing the quality and completness of these existing KG's

---

# 3. Evaluation

To assess correctness/completeness, we need evaluations. The three most common ways to evaluate a KG are:

### 3.1 (Partial) Gold Standard
- Human labels or using other KGs.

### 3.2 Silver Standard
- Using the KG itself (assumes correctness -> can only be used for completeness).

### 3.3 Retrospective Evaluation


---


# 4. Methods Used
Only approaches for entity/relation completion/correctness are scrutinized.

## 4.1 Types of Methods
The Methods can be categorized under the following dimensions:

- Completeness/Correctness
- Internal/External


---

# 4.2 Methods for Completness 

## 4.2.1 Internal
 - Association Rule Mining (Types and Relations): Derives rules based on frequent co-occurrences in the KG. e.g. ingoing edges of type **Cast** → probability that the predicate is of type **Actor** is large
 - Logical Reasoning: Infer rules directly

 ---

# 4.2 Methods for Completness 

### 4.2.2 External
- Web search by generating search quieres, e.g. 'Relationship between Actor and Film'
- Using Abstracts of Wikipedia with NLP
- Using other KG's, identify patterns  

---

# 4.3 Methods for Correctness 

## 4.3.1 Internal
- Outlier Detection: taking the characteristics of the object and subject of the relationship and create distirubtion from it for each relation 
- Reasoning by looking at Classes (needs disjoint axioms)
- Classic Outlier Detection for numerical values
- Limitation: A lot of outliers are errors, but not all errors are outlier

---

# 4.3 Methods for Correctness 
## 4.3.2 External
- Web search: creating sentnces out of triples -> count hits -> generate probability
- Let Humans correct some samples -> hope to find root cause of erros 
- Linking different KG's -> Identify facts differing in one KG but aligning in others


---

# 5. Findings
- Many algorithms only focus on identifying erros, not fixing them
- Probalbistic methods such as "Association Rule Mining" could be used for Error detection and completion simultaneously 
- Algorithm efficency relvant for large KG's
- Most methods are only tested on one KG which limits the statistical significance of the results
- No benchmark method for completness or correctness



# Sources


1. https://www.semantic-web-journal.net/system/files/swj1167.pdf


---

Thank you for attending my presentation!
