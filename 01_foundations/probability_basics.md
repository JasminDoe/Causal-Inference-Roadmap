# Probability Basics

## Overview
Probability theory provides the mathematical foundation for statistical reasoning and causal inference. It describes uncertainty and enables reasoning about random phenomena.

---

## Fundamental Concepts

### Probability Basis
Probability describes uncertainty and reasoning about random phenomena.

### Sample Space
The **sample space** is the set of all possible outcomes of a random experiment.

**Example:**
- Rolling a die:  
  Ω = {1, 2, 3, 4, 5, 6}

### Event
An **event** is a subset of the sample space.

**Example:**
- Rolling a 2: {2}

### Event Space
The **event space** is the collection of all possible events defined on a sample space.

---

## Types of Events

### Disjoint (Mutually Exclusive) Events
Disjoint events have no outcomes in common and cannot occur simultaneously.

**Example:**
- Rolling a 1 vs. rolling a 5.

### Independent Events
Two events are independent if the occurrence of one does not affect the probability of the other.

\[
P(A \cap B) = P(A) \cdot P(B)
\]

\[
P(A \mid B) = P(A)
\]

### Associated (Dependent) Events
Dependent events occur when the outcome of one event affects the probability of another.

### Conditionally Independent Events
Two events \( A \) and \( B \) are conditionally independent given a third variable \( C \).

\[
P(A \cap B \mid C) = P(A \mid C) \cdot P(B \mid C)
\]

**Example:**
Truck driving and cancer are independent after accounting for smoking.

### Exhaustive Events
Exhaustive events collectively cover the entire sample space.

### Empty Set
The **empty set** contains no possible outcomes. Its probability is zero.

**Example:**
Rolling a die and obtaining neither 1 nor 6.

\[
P(\emptyset) = 0
\]

---

## Probability Function

A **probability function**, denoted by \( P(\cdot) \), assigns probabilities to events and satisfies the following axioms:

### Axiom 1: Non-Negativity
\[
P(A) \geq 0
\]

### Axiom 2: Normalization
\[
P(\Omega) = 1
\]

### Axiom 3: Additivity
For disjoint events \( A \) and \( B \):

\[
P(A \cup B) = P(A) + P(B)
\]

---

## Set Operations

### Intersection (Joint Event)
The intersection of two events represents outcomes common to both.

\[
A \cap B
\]

\[
P(A \cap B)
\]

### Union
The probability that at least one of two events occurs is:

- **For disjoint events:**
\[
P(A \cup B) = P(A) + P(B)
\]

- **For non-disjoint events:**
\[
P(A \cup B) = P(A) + P(B) - P(A \cap B)
\]

---

## Law of Total Probability

If events \( B_1, B_2, \ldots, B_n \) are mutually exclusive and exhaustive, then:

\[
P(A) = \sum_{i=1}^{n} P(A \mid B_i) P(B_i)
\]

---

## Types of Probabilities

### Marginal Probability
The probability of a single event regardless of other variables.

\[
P(A)
\]

### Conditional Probability
The probability of event \( A \) given that event \( B \) has occurred.

\[
P(A \mid B) = \frac{P(A \cap B)}{P(B)}
\]

### Joint Probability
The probability that two events occur simultaneously.

\[
P(A \cap B)
\]

---

## Factorization and Chain Rule

The multiplication rule extends conditional probability to multiple events.

For two events:

\[
P(A, B) = P(A \mid B) P(B)
\]

For three or more events:

\[
P(A, B, C) = P(A \mid B, C) P(B \mid C) P(C)
\]

More generally:

\[
P(X_1, X_2, \ldots, X_n) =
\prod_{i=1}^{n} P\left(X_i \mid X_1, \ldots, X_{i-1}\right)
\]

---

## Relevance to Causal Inference

Probability theory forms the backbone of causal inference. It underpins:

- Counterfactual reasoning
- Statistical estimation
- Exchangeability and confounding
- Identification of causal effects
- Directed acyclic graphs (DAGs)
- Bayesian and frequentist inference
