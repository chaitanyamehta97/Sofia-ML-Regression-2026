## Approaches Evaluated

1. **Simple Linear Regression**
2. **L1 Regularization (Lasso)**
3. **L2 Regularization (Ridge)**
4. **Feature Engineering**
      -- Drop features which are not contributing to help us predict the target [Helped]
      -- Combined strongly correlated features [Did not help]

---

## Results

**Simple Linear Regression** yielded the best performance:

* **Public Leaderboard:** `0.57131`
* **Private Leaderboard:** `0.54011`

---

## Some Learnings

* **Outlier Removal:** Filtering out outliers led to severe overfitting—producing high training accuracy but poor generalization on the test set.
