# Step 3: Generate Weekly Grocery Lists from Recipes

Consolidate all ingredients from each week's recipes into comprehensive grocery lists, organized for efficient shopping and budget tracking.

---

## Your Task

Take the detailed recipes from Step 2 (located in `/plans/[month]/[week]/`) and create consolidated grocery lists for each prep day, accounting for all ingredients needed across all dishes being prepared that week.

**Input:** Complete recipes from Step 2 directories
**Output:** Weekly grocery lists with combined quantities and shopping guidance

---

## Grocery List Requirements

**List Format:**
- Organized by store section (Produce, Meat/Seafood, Dairy Alternatives, Pantry, etc.)
- Combined quantities for shared ingredients
- Unit conversions for shopping ease
- Budget estimates per category
- Special sourcing notes (farmers market, specialty stores)

**Shopping Optimization:**
- Combine duplicate ingredients across recipes
- Convert recipe measurements to shopping units
- Account for bulk buying opportunities
- Note items that can be purchased in advance
- Identify items needing fresh purchase

**Budget Tracking:**
- Estimate costs for each category
- Total weekly grocery budget
- Running monthly total
- Note opportunities for cost savings
- Track against $800-1000 monthly target

---

## Directory Structure

Create grocery lists in each week's directory:

```
/plans/[month]/
├── 1/
│   ├── proteins/
│   ├── sides/
│   ├── carbs/
│   ├── fresh/
│   ├── prep-day-overview.md
│   └── grocery-list.md      ← NEW FILE
├── 2/
│   └── grocery-list.md      ← NEW FILE
├── 3/
│   └── grocery-list.md      ← NEW FILE
├── 4/
│   └── grocery-list.md      ← NEW FILE
└── monthly-shopping-summary.md  ← NEW FILE
```

---

## Grocery List Template

Use this format for each weekly grocery list:

```markdown
# Week [X] Grocery List - [Date Range]

**Prep Date:** Sunday, [Date]
**Total Recipes:** X dishes
**Estimated Budget:** $XXX

## Shopping Summary

### By Store Section

#### Produce
- [ ] Item (total quantity needed) - $X.XX estimate
- [ ] Item (total quantity needed) - $X.XX estimate
[Group all produce items together]

#### Meat & Seafood
- [ ] Item (total quantity needed) - $X.XX estimate
[Include specific cuts and quality notes]

#### Pantry Staples
- [ ] Item (total quantity needed) - $X.XX estimate
[Items with longer shelf life]

#### Refrigerated Items
- [ ] Item (total quantity needed) - $X.XX estimate
[Non-dairy alternatives, eggs, etc.]

#### Spices & Seasonings
- [ ] Item (total quantity needed) - $X.XX estimate
[Check existing pantry first]

#### Specialty Items
- [ ] Item (store/source) - $X.XX estimate
[Items requiring special sourcing]

## Recipe Breakdown

### Ingredients by Recipe
Show which ingredients go with which recipes for reference:

**[Recipe Name 1]:**
- Ingredient (quantity)
- Ingredient (quantity)

**[Recipe Name 2]:**
- Ingredient (quantity)
- Ingredient (quantity)

## Shopping Notes

### Bulk Buying Opportunities
- Items worth buying in larger quantities
- Storage considerations

### Farmers Market Items
- Seasonal produce available locally
- Best shopping days/times

### Advance Purchase Items
- Non-perishables that can be bought early
- Items to watch for sales

### Last-Minute Fresh Items
- Items to purchase 1-2 days before prep
- Quality selection tips

## Budget Breakdown

| Category | Estimated Cost |
|----------|---------------|
| Produce | $XX |
| Proteins | $XX |
| Pantry | $XX |
| Other | $XX |
| **Total** | **$XXX** |

**Monthly Running Total:** $XXX / $900 target
```

---

## Consolidation Guidelines

**Quantity Combining:**
- Add up all instances of the same ingredient
- Convert to practical shopping units (e.g., "3.5 cups" → "1 lb")
- Round up slightly for recipe testing/tasting
- Account for ingredient prep waste (peels, trimmings)

**Unit Standardization:**
- Use shopping-friendly measurements
- Include both weight and volume when helpful
- Specify package sizes for efficiency
- Note when bulk bins are appropriate

**Smart Shopping:**
- Group items by store layout
- Note which items freeze well for advance purchase
- Identify crossover ingredients for future weeks
- Suggest substitutions for expensive items

**Quality Specifications:**
- Indicate when quality matters (e.g., "ripe avocados")
- Note specific varieties needed (e.g., "Kalamata olives")
- Include ripeness timing for produce
- Specify meat grades or cuts

---

## Monthly Summary File

Create a consolidated monthly shopping summary:

```markdown
# [Month] Shopping Summary

## Weekly Budgets
- Week 1: $XXX
- Week 2: $XXX
- Week 3: $XXX
- Week 4: $XXX
- **Monthly Total: $XXX**

## Frequently Used Items
Items appearing in multiple weeks (consider bulk buying)

## Seasonal Highlights
Best produce and proteins for this month

## Cost-Saving Strategies
Specific tips based on this month's recipes

## Pantry Inventory Check
Items to verify before shopping each week
```

---

## Output Instructions

**File Generation:**
1. Read all recipes in each week's directories
2. Extract and combine all ingredients
3. Generate organized grocery lists using the template
4. Create monthly summary file
5. Update the recipe index (/plans/[month]/recipe-index.md) to add links to the grocery lists

**Recipe Index Update:**
After creating all grocery lists, update the recipe index to include:
- Links to each week's grocery list next to the prep day overview
- A new "Grocery Lists & Shopping" section at the bottom with:
  - Links to all weekly grocery lists
  - Link to the monthly shopping summary

**Quality Checks:**
- Verify all recipe ingredients are included
- Ensure quantities are properly combined
- Confirm unit conversions are accurate
- Check budget estimates are reasonable

**User-Friendly Features:**
- Checkbox format for shopping convenience
- Clear organization by store section
- Practical quantities for shopping
- Budget tracking against monthly target

**Note:** This is Step 3 of the 3-step process:
- Step 1: Create overall schedule ✓
- Step 2: Generate detailed recipes ✓
- **Step 3: Create consolidated grocery lists (this prompt)**

Focus on creating practical, organized lists that make weekly shopping efficient and budget-conscious.