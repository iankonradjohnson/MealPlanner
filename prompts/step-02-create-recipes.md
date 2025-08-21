# Step 2: Create Detailed Recipes from Monthly Schedule

Generate complete recipes with ingredients and instructions for all dishes identified in the Step 1 monthly schedule, organized by prep day for maximum efficiency.

---

## Your Task

Take the monthly schedule from `/plans/[month]/meal-schedule.md` and create detailed recipes for every dish listed, organizing them by their prep dates for easy execution.

**Input:** Monthly schedule from Step 1
**Output:** Complete recipe collection organized by prep day

---

## Recipe Requirements

**Recipe Format:**
- **Dish Name** with cultural origin
- **Prep Time** and **Cook Time**
- **Yield** (number of silicon brick portions)
- **Complete Ingredient List** with quantities
- **Step-by-step Instructions**
- **Storage Notes** (freezing vs refrigeration)
- **Silicon Brick Portioning** guidance

**Diet Compliance:**
- **Blue Zone + Paul Saladino Hybrid**: Whole foods, legumes, vegetables, olive oil + quality meats and organ meats
- **Dairy-Free**: Substitute any traditional dairy ingredients
- **No Processed Foods**: Only real, pronounceable ingredients
- **Seasonal Focus**: Use ingredients that are in season for the specified month
- **Budget Conscious**: Optimize for cost-effectiveness within $800-1000 monthly budget

**Practical Considerations:**
- **Batch Cooking**: Scale recipes for bulk preparation and freezing
- **Storage Optimization**: Recipes should freeze and reheat well
- **Prep Efficiency**: Group similar techniques on the same day
- **Nutritional Balance**: Ensure variety of nutrients across all dishes

---

## Directory Structure

Organize recipes by prep day as follows:

```
/plans/[month]/
├── 1/          (1st Sunday)
│   ├── proteins/
│   │   ├── protein-dish-1.md
│   │   └── protein-dish-2.md
│   ├── sides/
│   │   ├── side-dish-1.md
│   │   └── side-dish-2.md
│   ├── carbs/
│   │   └── carb-dish-1.md
│   ├── fresh/
│   │   └── fresh-dish-1.md
│   └── prep-day-overview.md
├── 2/          (2nd Sunday)
│   ├── proteins/
│   ├── sides/
│   ├── carbs/
│   ├── fresh/
│   │   ├── fresh-dish-1.md
│   │   └── fresh-dish-2.md
│   └── prep-day-overview.md
├── 3/          (3rd Sunday)
│   ├── proteins/
│   ├── sides/
│   ├── carbs/
│   ├── fresh/
│   └── prep-day-overview.md
├── 4/          (4th Sunday)
│   ├── proteins/
│   ├── sides/
│   ├── carbs/
│   ├── fresh/
│   └── prep-day-overview.md
└── recipe-index.md
```

**Prep Day Overview Files:**
Each prep day should include an overview file with:
- Complete shopping list for that day
- Prep order and timing
- Equipment needed
- Storage and labeling instructions

---

## Recipe Template

Use this format for each recipe:

```markdown
# [Dish Name] - [Cultural Origin]

**Type:** [Protein/Side/Carb/Fresh]
**Prep Time:** X minutes | **Cook Time:** X minutes | **Total:** X hours
**Yield:** X silicon brick portions (serves X people)
**Storage:** Freezer (3 months) / Refrigerator (5 days)

## Ingredients

- Ingredient 1 (quantity)
- Ingredient 2 (quantity)
- [List all ingredients with specific quantities]

## Instructions

1. Step-by-step instructions
2. Include timing and temperature details
3. Specify when to add each ingredient
4. Include visual cues for doneness

## Storage & Portioning

- How to portion into silicon brick molds
- Cooling instructions before freezing
- Reheating instructions
- Pairing suggestions with other components

## Notes

- Cultural background or authenticity notes
- Substitution suggestions
- Scaling tips for larger/smaller batches
```

---

## Guidelines

**Authenticity:**
- Use traditional cooking methods when possible
- Include brief cultural context for each dish
- Respect original flavor profiles while adapting for dietary restrictions

**Efficiency:**
- Group similar prep techniques on the same day
- Optimize oven/stovetop usage
- Minimize cleanup between dishes

**Nutritional Balance:**
- Ensure variety of colors and nutrients
- Include adequate protein sources
- Balance fresh and cooked vegetables
- Incorporate healthy fats and complex carbohydrates

**Budget Optimization:**
- Use affordable cuts of meat that benefit from slow cooking
- Emphasize seasonal produce
- Suggest bulk purchasing opportunities
- Include organ meats where culturally appropriate

---

## Output Instructions

**File Organization:**
1. Use the existing directory structure created in Step 1
2. Generate individual recipe files for each dish in their appropriate directories
3. Create prep day overview files with shopping lists and timing
4. Generate a master recipe index with cross-references

**Quality Control:**
- Verify all recipes are complete and tested-style
- Ensure storage instructions are appropriate for each dish
- Confirm dietary restrictions are met
- Check that portions align with silicon brick storage system

**Note:** This is Step 2 of a 3-step process:
- Step 1: Create overall schedule ✓
- **Step 2: Generate detailed recipes (this prompt)**
- Step 3: Create consolidated grocery shopping lists

Focus on creating complete, executable recipes that align perfectly with the Step 1 schedule.