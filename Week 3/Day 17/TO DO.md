# ✅ Day 17 – PCA: Dimensionality Without Compromise

---

## 📘 Concepts to Learn
- [ ] What is **PCA (Principal Component Analysis)?**
  - [ ] Why do we reduce dimensions?
  - [ ] How PCA finds new "axes" (principal components)
  - [ ] Variance & projection concepts
- [ ] Understand:
  - [ ] `explained_variance_ratio_`
  - [ ] When to use PCA
  - [ ] Trade-off between simplicity & accuracy

---

## ⚙️ Hands-On Practice
- [ ] Load a dataset with multiple numeric features (suggest: Iris or Digits)
- [ ] Standardize data using `StandardScaler`
- [ ] Apply `PCA(n_components=2)` from `sklearn.decomposition`
- [ ] Plot PCA-transformed data (2D scatter)
- [ ] Color by original class labels (for visual clarity)

---

## 📊 Evaluate Reduction
- [ ] Use `.explained_variance_ratio_` to see how much info was retained
- [ ] Try different `n_components` values (2, 3, all)
- [ ] Compare model performance before vs after PCA

---

## 📺 Quick Boosters
- [ ] [PCA Intuition & Visual](https://www.youtube.com/watch?v=FgakZw6K1QQ)
- [ ] [PCA with sklearn](https://www.youtube.com/watch?v=Lsue2gEM9D0)

---

## 📓 Reflection Prompts
- What did PCA help you *see* that wasn’t visible before?
- How would you explain PCA to a friend using images?
- How do you feel about throwing away data dimensions?

---

## 🌱 Bonus Goals (Optional)
- [ ] Try 3D PCA with `matplotlib` 3D scatter
- [ ] Chain PCA + KMeans and visualize clusters in reduced space
- [ ] Try PCA on a real-world dataset with 20+ features

---


