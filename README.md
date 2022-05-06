## Motivation & Context

### Need for XAI

### What to explain

### Global vs. Local Explanation

### Overview on XAI approaches in general

- Model Explanation
    - Surrogate Models
        - SKE methods
- Outcome Explanation
    - Feature Importance
        - LIME
        - SHAP
    - Agnostic Explanator
- Model Inspection
    - Sensitivity Analysis
    - Partial Dependence
    - Activation Maximization
    - Tree Visualization
- Transparent Box Design

## Background

### Interpretation vs. Explanation



### Symbolic Knowledge Extraction as Explanation

#### Definition of SKE

#### Taxonomy of SKE methods

#### Examples of methods and their classification

## PSyKE -- A Platform for Symbolic Knowledge Extraction

### Overall Design

### API Design

### Functioning

- classification problems
- regression problems

### Usage Examples

- Iris (classification)
- Combined Cycle Power Plant (regression)

## Discussion

### Notable Remarks

- commitment to a particular output shape / expressiveness
    - to preserve both human- and machine-interpretability
    - other syntaxes may exist
- discretization of the input space
- discretization of the output space
- features should have semantics per se
- further refinements may be applied to rules
- rules constitute global explanations

### Current Limitations

- tabular data as input => doesn't really work with images
- high dimensional datasets => very large, poorly readable rules
- highly variable input spaces => many rules => poor readability

## Future research activities

- Target images or highly dimensional data in general
- Target reinforcement learning (when based on NN)
- Target unsupervised learning
- Design and prototype your own extraction algorithm
