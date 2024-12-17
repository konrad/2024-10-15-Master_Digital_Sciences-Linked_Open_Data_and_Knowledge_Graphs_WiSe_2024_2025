% A Practical Framework for Evaluating the Quality of Knowledge Graph

---

# Table of contents

1. Intruduction
2. Quality of Knowledge Graph

    2.1. Quality Metrics for Knowledge Graph

    2.2. Approaches and Tools for Evaluating Quality of Knowledge Graph
3. A Recommended Framework for Quality Evaluation of Knowledge Graph
4. Related Work
5. Summary and future directions

---

# Introduction

**Knowledge graphs**

  - A graph representation of knowledge using entities, edges, and attributes.

  - Entities represent real-world objects; edges represent relationships; attributes define entities.

**Importance of knowledge graph quality**

  - Quality impacts system effectiveness and usability.

---

# Introduction

**Quality criteria**

  - Correctness, comprehensiveness, and freshness

**Limitations of current frameworks**

  - Some criteria may not be necessary for all applications

  - Validation of certain criteria might occur during application development

  - Handling low-quality items is often the responsibility of application developers

---

# Introduction

**Purpose**

  - Identify essential quality requirements for knowledge-based systems

  - Maps quality criteria to select metrics that can be used for evaluating basic quality standard of a knowledge graph

  - Investigate existing evaluation approaches and tools to propose one practical approach for evaluating

---

# Quality of Knowledge Graph

## Quality Metrics for Knowledge Graph

**Zaveri’s framework**

- Based on prior frameworks by Wang & Strong and Stvilia.

- Includes 18 quality dimensions and 69 metrics.

- Categories:
    - **Accessibility:** availability, licensing, interlinking, security, performance.
    - **Intrinsic:** syntactic validity, semantic accuracy, consistency, conciseness, completeness.
    - **Contextual:** relevancy, trustworthiness, understandability, timeliness.
    - **Representational:** representational conciseness, interoperability, interpretability, versatility.

---

# Quality Metrics for Knowledge Graph

**Examples of metrics**

- Availability: "Accessibility of RDF dumps"

- Security: "Usage of digital signatures", "Authenticity of the dataset."

- Semantic Accuracy: "No outliers", "No inaccurate values", "No misuse of properties."

- Interoperability: "Compliance with standards", "Usability in multiple systems."

**Challenges in defining metrics**

  - No complete set of metrics for every dimension.

  - Metrics must be adapted for specific domains or applications.

---

# Approaches and tools for evaluating quality of KG

## Evaluation approaches

**Test-Driven evaluation**

- Generates test cases using data schema constraints, patterns, and requirements

- Checks queried results against specific quality metrics


**Sampling for accuracy**

- Efficiently evaluates accuracy with strong statistical guarantees

---

# A recommended framework for quality evaluation of KG

**Categories of knowledge graph applications:**

- Semantic search

- Decision making

- Knowledge management

- Data mining

- Prediction

---

# A recommended framework for quality evaluation of KG

**Example Use Cases:**

  - **Recommendation systems:**

      - Represent semantic relationships between items.

      - Include diverse relationships to enhance recommendation variety.

      - Provide user history for explainability.

  - **Question answering:**

      - Ambiguity of entity names and partial names.

      - Scalability for adding new entities and relationships.

  - **Information retrieval:**

    - Entities associated with various names for better matching.

---

# A recommended framework for quality evaluation of KG

**Key quality dimensions for different applications:**

  - **Semantic search:** Syntactic Validity, Semantic Accuracy, Conciseness

  - **Decision making:** Trustworthiness, Accuracy, Relevancy

  - **Prediction:** Accuracy, Timeliness, Consistency

---

# A recommended framework for quality evaluation of KG

## Quality requirements for knowledge graphs

  1. Triples should be concise.
  2. Contextual information of entities should be captured.
  3. Redundant triples should be eliminated.
  4. Knowledge graph should support dynamic updates.
  5. Entities should be densely connected.
  6. Relationships among different types of entities should be included.
  7. Data sources should span multiple fields.
  8. Data for constructing the knowledge graph should come from diverse types and resources.
  9. Synonyms should be mapped, and ambiguities resolved.

---

  10. Structured triples should enable easy machine processing.
  11. Scalability to accommodate large graph sizes.
  12. Attributes of entities should not be omitted.
  13. Knowledge graph should be publicly available and proprietary.
  14. Authority of data should be ensured.
  15. The graph should remain concentrated on relevant entities.
  16. Triples should not contradict each other.
  17. Domain-specific tasks require domain-relevant data.
  18. Freshness of resources to ensure up-to-date information.

---

# Knowledge graph requirements produced from representative applications

![](<Knowledge graph requirements produced from representative applications.png>)

---

# Mapping knowledge graph requirements quality dimensions

![](<Mapping knowledge graph requirements quality dimensions.png>)

---

# Related Work

### Wang and Strong (1996)

- Proposed a hierarchical framework for data quality dimensions

### Stvilia et al. (2007)

- Investigated causes and effects of information quality changes

- Developed a taxonomy of quality dimensions and problems

### Zaveri et al. (2016)

- Evaluated DBPedia with a user-driven approach

- Reviewed frameworks for linked data

### Paulheim (2017)

- Evaluated methods based on target, method type, evaluation metrics, and computational performance


---

# Summary and future directions

**Focuses on balancing**

  - Comprehensive evaluation with measurable dimensions.

  - Scalability for large knowledge graphs.

**Future work**

Test framework effectiveness on large-scale knowledge graphs

---

# References

1. Chen, H., Cao, G., Chen, J., Ding, J. (2019). A Practical Framework for Evaluating the Quality of Knowledge Graph. In: Zhu, X., Qin, B., Zhu, X., Liu, M., Qian, L. (eds) Knowledge Graph and Semantic Computing: Knowledge Computing and Language Understanding. CCKS 2019. Communications in Computer and Information Science, vol 1134. Springer, Singapore. https://doi.org/10.1007/978-981-15-1956-7_10

