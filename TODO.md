# TODO: Implement Discount Percentage Feature

## Revised Plan v2 (NEW field 'discountPercentage')
**Information Gathered:** Model has 'discount' (keep), add NEW 'discountPercentage' (Number 0-100). Frontend missing input/display.

**Plan:**
1. [ ] Edit backend/models/Item.js - Add discountPercentage: { type: Number, min: 0, max: 100, default: 0 }
2. [ ] Edit frontend/src/components/ItemForm.jsx - Add to initialState/defaults, add number input "Discount Percentage (%)" 0-100.
3. [ ] Edit frontend/src/components/ItemCard.jsx - Add display <p><strong>Discount %:</strong> {item.discountPercentage}%</p> after price.
4. [ ] Test: Run dev servers, add item with discount %, verify form/home/edit.

**Dependent Files:** None.

**Followup:** 
- User approval needed ("no" previously).
- Test command: Check package.json for dev scripts.
- Screenshots.

**Status:** Awaiting approval.

