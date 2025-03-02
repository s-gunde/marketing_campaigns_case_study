# ✨ Project Requirements  

## 📌 Requirement #1: Top 2 Categories  
For each customer, we need to identify the **top 2 categories** based on their past rental history.  

- These **top categories** will drive marketing creative images.  
- Examples include **travel and sci-fi**, as seen in the draft email.  

---

## 📌 Requirement #2: Category Film Recommendations  
The marketing team has requested the **3 most popular films** for each customer's **top 2 categories** _(excluding already viewed films)_.  

### 🔹 Rules:  
- If there are **less than 3 films available**, marketing is fine with recommending **at least 1 film**.  
- Customers with **no film recommendations** for either category **must be flagged** for exclusion from the email campaign _(this is of high importance!)_.  

---

## 📌 Requirement #3 & #4: Individual Customer Insights  

### 📍 Top Category Insights (Requirement #3)  
For the **1st category**, marketing requires:  
- 🎬 **Total number of films watched** in this category.  
- 📊 **Comparison to the average** DVD Rental Co customer.  
- 🏆 **Customer ranking** in the **top X%** for this film category.  

### 📍 Second Category Insights (Requirement #4)  
For the **2nd category**, marketing requires:  
- 🎞️ **Total number of films watched** in this category.  
- 🔢 **Proportion of total films watched** _(rounded to 0 decimal places)_.  

---

## 📌 Requirement #5: Favorite Actor Recommendations  
Along with the **top 2 categories**, marketing has also requested **top actor film recommendations**:  
- **Up to 3 additional films** should be recommended.  
- The **total count of films watched by the top actor** should be included.  

### 🔹 Rules:  
- If multiple actors have the **same film count**, choose the actor in **alphabetical order**.  
  - _(e.g., If a customer has watched 5 Brad Pitt films and 5 George Clooney films, Brad Pitt will be chosen first.)_  
- Any films already recommended in the **top 2 categories** must **not** be included in the actor recommendations.  
- Customers with **no actor recommendations** must be **flagged separately** for exclusion.  

---

## 🎯 Final Notes  
✔️ Ensure all calculations are **accurate**.  
✔️ Follow the specified **rounding rules**.  
✔️ Customers with **no recommendations** should be **properly flagged**.  

🚀 **Let's build a powerful recommendation system!**  
