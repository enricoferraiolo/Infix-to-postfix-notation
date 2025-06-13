# Infix to Postfix Notation Neural Network

A neural network implementation that translates mathematical expressions from infix notation to postfix notation (Reverse Polish Notation) using a Transformer-based architecture.

## Project Overview

This project implements a neural network that performs the translation of mathematical formulae from traditional **infix notation** - where the operator appears between two operands—to **postfix** (also known as Reverse Polish Notation), where the operator follows the operands. 

### Example

**Infix Expression:** `a + b * c`

Can be interpreted as:
- `(a + b) * c` → **Postfix:** `ab+c*`
- `a + (b * c)` → **Postfix:** `abc*+` 

## Technical Specifications

### Dataset Constraints
- **Identifiers:** Uses 5 identifiers (a, b, c, d, e) 
- **Operators:** 4 binary operators (+, -, *, /)
- **Maximum Depth:** 3 levels for abstract syntax trees
- **Fully Parenthesized:** All binary operations are fully parenthesized (e1 op e2)

### Model Architecture

The project uses a **Transformer-based encoder-decoder architecture** with positional encoding optimized for sequence-to-sequence translatio

## Results
### Test Evaluation
The model achieves perfect performance on evaluation:
- **Score:** 1.0
- **Standard Deviation:** 0.0
