# Seaborn_Scatter_Plot_Visualization

This visualization explores how **tips change with the total bill amount** using Seaborn’s built-in **tips** dataset. It also compares patterns across **time of day** (Lunch/Dinner) and **gender** using color and marker styles.

---

## Goal
Understand the relationship between:
- `total_bill` (x-axis) and `tip` (y-axis),
and see how it varies by:
- `time` (color grouping)
- `sex` (marker style)

---

## Dataset
- **Dataset:** `tips` (loaded using `sns.load_dataset("tips")`)
- Common columns used here:
  - `total_bill`: total bill amount
  - `tip`: tip given
  - `time`: Lunch or Dinner
  - `sex`: Male or Female

---

## Visualization Details
- **Plot type:** Scatter plot  
- **Encoding used:**
  - `hue="time"` → different colors for Lunch vs Dinner
  - `style="sex"` → different marker shapes for Male vs Female
- **Figure size:** `8 × 5` for better readability

---

## Seaborn Styling (Aesthetic Functions)
- `sns.set_style("whitegrid")`  
  Adds a light grid background to make points easier to read.
- `sns.set_palette("coolwarm")`  
  Applies a consistent color palette for category separation.
- `sns.set_context("talk")`  
  Increases text size (titles/labels) so the plot looks clearer in presentations.

---

## Output
- A titled plot: **"Customized Seaborn Scatter Plot with Aesthetic Functions"**
- Clear visual comparison of tipping behavior across:
  - total bill size
  - Lunch vs Dinner
  - Male vs Female

## Developer
Grishma C.D
