## <u>A Practical Framework for Evaluating the Quality of Knowledge Graph</u>

by Haihua Chen1, Gaohui Cao2, Jiangping Chen1, and Junhua Ding

## Presentation

by Kseniia Blokihna

---

# Structure

1. Intruduction
2. Quality of Knowledge Graph

    2.1. Quality Metrics for Knowledge Graph

    2.2. Approaches and Tools for Evaluating Quality of Knowledge Graph
3. A Recommended Framework for Quality Evaluation of Knowledge Graph
4. Related Work
5. Summary

---

# Introduction

**Knowledge graphs**

  - A graph representation of knowledge using entities, edges, and attributes.

  - Entities represent real-world objects; edges represent relationships; attributes define entities.

**Importance of knowledge graph quality**

  - Quality impacts system effectiveness and usability.

---

**Quality criteria**

  - Correctness, comprehensiveness, and freshness

**Limitations of current frameworks**

  - Some criteria may not be necessary for all applications

  - Validation of certain criteria might occur during application development

  - Handling low-quality items is often the responsibility of application developers

---

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

**Examples of metrics:**

- Availability: "Accessibility of RDF dumps"

- Security: "Usage of digital signatures", "Authenticity of the dataset."

- Semantic Accuracy: "No outliers", "No inaccurate values", "No misuse of properties."

- Interoperability: "Compliance with standards", "Usability in multiple systems."

**Challenges in defining metrics**

  - No complete set of metrics for every dimension.

  - Metrics must be adapted for specific domains or applications.

---

## Approaches and tools for evaluating quality of knowledge graph

**Types of evaluation**

  - Manual

  - Automated

**Review by Zaveri**

  - Systematic review of 30 approaches and 12 tools

  - Dimensions like syntactic validity and semantic accuracy received significant attention

  - Dimensions like security and performance were less emphasized

---

## Evaluation approaches

**Test-Driven evaluation**

- Generates test cases using data schema constraints, patterns, and requirements

- Checks queried results against specific quality metrics


**Sampling for accuracy**

- Efficiently evaluates accuracy with strong statistical guarantees

---

# A recommended gramework for quality evaluation of knowledge graph  

**Categories of knowledge graph applications:**

- Semantic search

- Decision making

- Knowledge management

- Data mining

- Prediction

---

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

- **Key quality dimensions for different applications:**

  - **Semantic search:** Syntactic Validity, Semantic Accuracy, Conciseness

  - **Decision making:** Trustworthiness, Accuracy, Relevancy

  - **Prediction:** Accuracy, Timeliness, Consistency

---

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

### Knowledge graph requirements produced from representative applications

![](<Knowledge graph requirements produced from representative applications.png>)

---

### Mapping knowledge graph requirements quality dimensions

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

Combines Zaveri’s framework with theoretical insights from Stvilia

**Focuses on balancing**

  - Comprehensive evaluation with measurable dimensions.

  - Scalability for large knowledge graphs.

---

# Summary and future directions

**Findings**

Syntax and semantics errors significantly impact the quality of knowledge graphs.

**Proposed framework applications**

- Basic quality evaluation for knowledge discovery

- Practical for building knowledge-based applications

**Future work**

Test framework effectiveness on large-scale knowledge graphs
