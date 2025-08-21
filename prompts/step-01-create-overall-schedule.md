# Step 1: Create Monthly Modular Meal Prep Schedule

Generate a comprehensive month-long meal prep schedule using a modular "Lego meal" approach with silicon brick storage for maximum efficiency and minimal time investment.

---

## Your Task

Create a high-level monthly schedule overview for 2 people that shows:
- **When** to do heavy prep days vs light prep days
- **Which dishes** to prepare on each prep day
- **Servings per dish** (target ~12 servings for frozen dishes to maximize bulk efficiency)
- **Component types** (frozen building blocks vs fresh dishes)
- **General timing** of prep activities throughout the month

## Meal Prep System

**Two-Tier Approach:**

**Heavy Prep Days (1-2 per month)**
- Bulk cook 3-4 main dishes MAX (stews, soups, curries, braised meats)
- Prepare 2-3 sides (roasted vegetables, grain dishes)  
- Cook 1-2 carb bases (rice, potatoes, etc.)
- Total: 6-8 dishes maximum per heavy prep day
- Store everything in silicon brick molds, then transfer to freezer bags
- Create modular components that can be mixed and matched

**Light Prep Days (Weekly Sundays)**
- Prepare 1-2 fresh dishes for refrigerated storage
- Focus on items unsuitable for freezing: salads (limit fresh tomato salads), fresh seafood, raw preparations
- Simple assembly dishes that complement frozen components
- Prep fresh fruit portions for snacks (berries, melons, citrus, stone fruits)

**Storage System:**
- Silicon molds create uniform "brick" portions for easy storage and thawing
- Frozen components become building blocks for "Lego meals"
- Fresh weekly items provide variety and texture contrast

---

## Output Format

Present the schedule as a monthly calendar showing:

1. **Heavy Prep Days**: Which dishes to bulk cook for freezing (building blocks)
2. **Light Prep Days**: Which fresh dishes to prepare for the week  
3. **Component Types**: Label each dish as either "Frozen Component" or "Fresh Weekly"
4. **Cultural Origin**: Name the culture/cuisine each dish comes from
5. **Budget Estimate**: Include estimated cost per 12-serving batch for frozen items or per weekly batch for fresh items

## Guidelines

**Diet Requirements:**
- **Blue Zone + Paul Saladino Hybrid**: Whole foods, legumes, vegetables, olive oil + emphasis on quality meats and organ meats
- **No Processed Foods**: Only real, pronounceable ingredients
- **Dairy-Free**: Avoid all dairy (but can suggest dairy substitutions for traditional recipes)
- **Cultural Authenticity**: Every dish should be a real dish from an actual culture
- **Budget Focus**: Emphasize cheap bulk items (grains, lentils, seasonal produce) within $800-1000 monthly budget
- **Budget-Conscious Proteins**: Focus on affordable cuts (chicken thighs/legs ~$3-4/lb, ground beef ~$5-6/lb, pork shoulder ~$3-4/lb, whole chickens ~$2-3/lb). Avoid expensive cuts like short ribs, ribeye, lamb chops
- **Quality When Possible**: Prioritize grass-fed/organic when budget allows, but conventional is acceptable to stay within budget
- **Limited Fresh Tomatoes**: Maximum 1 salad with fresh tomatoes per month
- **Protein Variety**: Emphasize chicken dishes and variety of meat types (beef, pork, lamb, fish)
- **Fresh Fruit Components**: Include prepped fresh fruit as snack components in weekly prep
- **Cultural Theme Cohesion**: Limit to 2-3 cultural cuisines per month for better pairing and cohesion

**Meal Variety:**
- **Fresh Weekly Variety**: Every week should feature completely different dishes—no repeating meals across the month
- **Modular Design**: Components should mix and match to create different meal combinations
- **Seasonal Focus**: Emphasize seasonal produce and ingredients that are naturally available and affordable
- **Protein Rotation**: Rotate between chicken, beef, pork, lamb, and fish throughout the month
- **Cultural Cohesion**: Select 2-3 cultural cuisines per month (e.g., Mediterranean, East Asian, and Latin American) for better flavor pairing

**Schedule Requirements:**
- **Planning for 2 People**: All quantities and servings should be calculated for a couple
- **Bulk Batch Sizes**: Each frozen dish should yield ~12 servings (6 silicon brick portions for 2 people each)
- **Flexible Timing**: Heavy prep days should be scheduled based on what makes sense (not rigid patterns)
- **Standard Portions**: Silicon brick molds should contain 2 adult servings each
- **Component Categories**: Distinguish between Proteins (with meat variety), Sides, and Carbs for frozen components
- **Fresh Variety**: Include weekly fresh dishes (4-6 servings) plus quick-cook items that must be prepared fresh
- **Snack Prep**: Include fresh fruit prep for healthy snacking throughout the week
- **Lego Meal Examples**: Show how different components can combine into complete meals
- **Strategic Pairing**: Consider which frozen components work well together culturally and flavor-wise
- **Colorful Balance**: Focus on variety of colors and nutrients for optimal hormonal health
- **Efficiency**: Minimize time and cost while maximizing taste and nutrition
- **Birds-Eye View Only**: Focus on the overall schedule structure—detailed recipes and grocery lists will come in Steps 2 & 3

---

## Example Output Structure

```
WEEK 1
Sunday: Heavy Prep Day (6-8 hours)
FROZEN COMPONENTS:
- ...

Wednesday: Fresh Prep (30 min)
FRESH COMPONENTS:
- ...

WEEK 2
Sunday: Light Prep Day (2-3 hours)
FRESH COMPONENTS:  
- ...

WEEK 3
Sunday: Heavy Prep Day (6-8 hours)
FROZEN COMPONENTS:
- ...

EXAMPLE LEGO MEALS (each combination serves 2):
- ...
```

**Note:** This is Step 1 of a 3-step process:
- **Step 1**: Create overall schedule (this prompt)
- **Step 2**: Generate specific recipes for each dish
- **Step 3**: Create grocery shopping lists

Focus solely on **dish scheduling and timing**—no recipes, ingredients, or quantities needed.

**Output Instructions:**
1. **Create directory structure** organized by Sunday sequence with categories:
   ```
   /plans/[month]/
   ├── 1/          (1st Sunday of the month)
   │   ├── proteins/
   │   ├── sides/
   │   ├── carbs/
   │   └── fresh/
   ├── 2/          (2nd Sunday of the month)
   │   ├── proteins/
   │   ├── sides/
   │   ├── carbs/
   │   └── fresh/
   ├── 3/          (3rd Sunday of the month)
   │   ├── proteins/
   │   ├── sides/
   │   ├── carbs/
   │   └── fresh/
   ├── 4/          (4th Sunday of the month)
   │   ├── proteins/
   │   ├── sides/
   │   ├── carbs/
   │   └── fresh/
   └── meal-schedule.md
   ```
2. **Save the schedule** to `/plans/[month]/meal-schedule.md` for use in subsequent steps
   
   Example for September 2025:
   ```
   /plans/september/
   ├── 1/          (September 7th - 1st Sunday)
   ├── 2/          (September 14th - 2nd Sunday)
   ├── 3/          (September 21st - 3rd Sunday)
   ├── 4/          (September 28th - 4th Sunday)
   └── meal-schedule.md
   ```

3. **Create placeholder README.md** in each directory explaining what recipes will go there in Step 2