# MIS312 Assignment 7 — Problem Decomposition

**Book Alignment:** Chapter 7  
**Primary Goal:** Break problems into steps and helper functions before coding  
**Environment:** JupyterLab + VS Code (`.ipynb`)  
**Submission:** OneNote Artifact (PDF)

---

## Learning Objectives
- Define inputs/outputs
- Write a step plan (pseudocode)
- Identify leaf vs complex functions

---

## Student Tasks

### Task 1 — Leaf function check (short answers)
Decide whether each is likely a leaf function and why:
- Find the largest number in a list
- Check whether a list contains a value
- Process customer orders (inventory/taxes/summaries)
- Generate student report cards

### Task 2 — Decompose a discount system
Write a plan for a “discount calculator” that:
- Takes original price and discount percent
- Outputs final price
- Handles bad input (negative discount)

Include:
- Inputs
- Outputs
- Steps
- Two helper functions you would write

### Task 3 — AI review (required)
Ask:
> “Here is my decomposition plan. What step is missing or unclear?”

Revise once.

---

## VS Code Exercise — Decomposition as a Script Skeleton

### Task 4 — Convert your plan into a `.py` skeleton (VS Code)
1. In VS Code, create: `C:\Users\<StarID>\MIS312\assignment07\discount_plan.py`
2. Write a **script skeleton** that matches your decomposition plan:
   - Function stubs with `pass`
   - Clear docstrings describing inputs/outputs
   - A small `main()` section at the bottom that shows intended usage

Example skeleton:
```python
def validate_inputs(price, discount_percent):
    'Return True if inputs are valid, otherwise False.'
    pass

def apply_discount(price, discount_percent):
    'Return final price after discount.'
    pass

def main():
    # Example intended usage (not finished yet)
    price = 100
    discount = 10
    # TODO: validate, then apply discount, then print result
    pass

if __name__ == "__main__":
    main()
```

### Task 5 — Run the skeleton
Run:
```powershell
python discount_plan.py
```

### Task 6 — AI review (required)
Ask:
> “Here is my function skeleton and docstrings. What is one improvement to make the plan clearer or more complete?”

Revise the skeleton once.

### Add to OneNote Artifact
- Screenshot of the `.py` file in VS Code
- Screenshot of running the file (even if it prints nothing yet)
- AI prompt + what you changed


## OneNote Artifact Requirements
- Leaf answers
- Plan (before + after)
- AI prompt + summary
- Reflection: Why does decomposition reduce debugging later?
