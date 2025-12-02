# ProFridge: Commonsense Inventory Management

A Prolog-based fridge inventory management system that uses commonsense reasoning to manage food items efficiently. Tracks food quantities, expiration dates, and priorities, and provides recommendations for restocking, grocery planning, and recipes.

## Features

- **Inventory Tracking**: Maintain food items with quantity and expiration.
- **Priority Management**: Items assigned as `high`, `medium`, or `low` priority.
- **Restocking Alerts**: Suggest items to restock based on priority and quantity.
- **Expiration Alerts**: Identify items expiring soon and add to grocery list.
- **Smart Usage**: Suggest which items to use first based on freshness.
- **Recipe Suggestions**: Recommend recipes based on available items, priority, and expiration.
  - Examples: Egg Sandwich, Roasted Broccoli

## Example Queries
```prolog
?- needs_restock(Item).
?- expiring_soon(Item).
?- add_to_grocery_list(Item).
?- recipe_smart_suggestion(egg_sandwich).
```

## Usage

1. Install SWI-Prolog or any Prolog interpreter.
2. Load `profridge.pl`:
```prolog
?- [profridge].
```
3. Run queries to get restocking alerts, grocery suggestions, or recipe ideas.

## Repo Structure
```
profridge-commonsense-inventory-management/
├── profridge.pl        # Prolog code with facts and rules
└── README.md           # Project documentation
```

## Notes

- This is a basic project; implemented based on what was learned from prior workshops.
- Developed independently for Hack Reason 2025 using the skills gained in the workshops.
