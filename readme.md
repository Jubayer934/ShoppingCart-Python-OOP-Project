# 🛒 ShoppingCart — Python OOP Project

A simple shopping cart system built with Python OOP concepts. Developed in a Jupyter Notebook on Google Colab.

---

## Features

- Add / remove items with input validation
- Calculate total and apply **10% discount** if total ≥ 3000
- Display a formatted cart summary
- Combine two carts using the `+` operator (`__add__`)
- Clear the cart

---

## Quick Example

```python
cart1 = ShoppingCart("Jubayer", [1000, 2000])
cart2 = ShoppingCart("Shakib", [3000, 4000])

cart1.display_cart()       # Shows total, discount, final total
combined = cart1 + cart2   # Merges both carts
combined.display_cart()
```

---

## Requirements

- Python 3.x
- Jupyter Notebook or Google Colab

## Run

Upload the `.ipynb` file to [Google Colab](https://colab.research.google.com) or run locally:

```bash
jupyter notebook shopping_cart.ipynb
```