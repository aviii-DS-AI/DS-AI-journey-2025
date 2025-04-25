# ✅ Day 18 – GridSearchCV & Hyperparameter Tuning 🔧

---

## 🔍 Theory & Intuition (30–40%)
- [ ] What are hyperparameters vs. parameters?
- [ ] Why can't we just guess best values?
- [ ] Why use GridSearchCV? Any alternatives?
- [ ] What does `cv=5` mean?
- [ ] How is it different from random search?

---

## 🛠️ Code Tasks (Main Practice)
### Logistic Regression Tuning
- [ ] Use GridSearchCV to tune:
  - `penalty`: ['l1', 'l2']
  - `C`: [0.01, 0.1, 1, 10, 100]
  - `solver`: ['liblinear']
- [ ] Use `scoring='accuracy'` and `cv=5`
- [ ] Print:
  - Best parameters
  - Best score
  - Confusion matrix on test set

### Decision Tree Tuning
- [ ] GridSearch for:
  - `max_depth`, `min_samples_split`, `criterion`
- [ ] Compare performance before/after tuning

### Random Forest Tuning (BONUS)
- [ ] Try small grid search:
  - `n_estimators`, `max_depth`, `max_features`
- [ ] Use classification report to evaluate improvement

---

## 🧠 Reflection Markdown (`Tuning_Summary.md`)
- [ ] What did tuning improve the most?
- [ ] How much better was GridSearch compared to default?
- [ ] Where did GridSearch take *too long*?
- [ ] How would you explain GridSearchCV to your younger sibling?






