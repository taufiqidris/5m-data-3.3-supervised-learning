# **Self-Study Preparation Guide**

**⏳ Estimated Prep Time:** 45–60 minutes

Welcome to our flipped-classroom session. In our upcoming live workshop, we will focus heavily on hands-on coding and debugging data pipelines. To make that time effective, you need to review the foundational concepts of data preprocessing and metrics beforehand. 

> **Note:** **Task 3** covers the *Bias-Variance Tradeoff*. This specific topic is a critical theoretical concept that **will not be covered during the live lecture**. Please ensure you complete this self-study module thoroughly so you are ready to apply the concepts during future model building.

## ⚡ Your Self-Study Tasks

Please complete the following activities before our session using the provided **`supervised_learning_2_lesson.ipynb`** notebook.

### 📝 Task 1: Data Preprocessing Strategy (20 Minutes)

**Activity:** Read the sections titled **"Preprocessing Categorical Variables"** and **"Preprocessing Numerical Variables"** in the notebook. Focus on the logical difference between techniques rather than memorizing the syntax.

**Guiding Questions:**

* **Categorical Data:** When would you choose Label Encoding (assigning integers) over One-Hot Encoding (binary vectors)? How does the concept of "ordinal" vs. "nominal" data drive this decision?
* **Numerical Scaling:** Review the formulas for Standardization vs. Min-Max Scaling. Why is scaling crucial for algorithms that calculate distance (like KNN or SVM)?
* **Missing Data:** The text discusses Imputation versus Removal. What is the business risk of simply dropping rows with missing data?

### 📝 Task 2: The Art of Evaluation (15 Minutes)

**Activity:** Review the sections on **"Classification Metrics"** and **"Regression Metrics"**. Pay close attention to the "When to Use" subsections for each metric.

**Guiding Questions:**

* **Accuracy Paradox:** Why might Accuracy be a misleading metric if you are detecting a rare event (like fraud or disease)?
* **Precision vs. Recall:** If the cost of a "False Negative" is very high (e.g., missing a diagnosis), which metric should you optimize for?
* **Regression Errors:** How does Mean Squared Error (MSE) treat large errors differently than Mean Absolute Error (MAE)? Which one penalizes outliers more heavily

### 📝 Task 3: Mastering the Bias-Variance Tradeoff (30 Minutes)
> This topic is entirely self-study driven and provides the *architectural intuition* needed for building robust models in the future. Post your questions on Discord for discussion.

**Activity:** 
1.  **Watch:** The instructional video [StatQuest: Bias-Variance Tradeoff](https://www.youtube.com/watch?v=EuBBz3bI-aA) (approx. 6 mins) to get a visual intuition of the concept.
2.  **Read:** The **"Understanding the Bias-Variance Tradeoff"** section at the end of the notebook.
3.  **Analyze:** 
    Examine the "bullseye" diagrams in the notebook illustrating high/low bias and variance.

**Guiding Questions:**

* **Definitions:** How does the notebook define "Bias" (underfitting) versus "Variance" (overfitting)? Which one pays "too much attention to training data"?
* **Visualizing Error:** In the bullseye visualization, what does it look like when a model has **High Variance** but **Low Bias**?
* **Balancing Act:** Why does the text state that decreasing one type of error often increases the other? What techniques (e.g., Cross-validation, Regularization) help find the "sweet spot"?

## 🙌🏻 Active Engagement Strategies

To deepen your retention, try one of the following while you review:

* **The "Cheat Sheet":** Create a quick reference table comparing *Precision* and *Recall*. Write down one real-world business scenario for each where it would be the primary metric.
* **Visual Summary:** Sketch the "Total Error" graph mentioned in the Bias-Variance section. Label the point where you think the "sweet spot" for a model lies.
* **Scenario Matching:** Think of a dataset you currently work with (or want to work with). Based on Task 1, which features would need One-Hot Encoding?

## 📖 Additional Reading Material

* [Scikit-Learn: Preprocessing Data](https://scikit-learn.org/stable/modules/preprocessing.html)
* [Precision and Recall Explained](https://scikit-learn.org/stable/auto_examples/model_selection/plot_precision_recall.html)

### 🙋🏻‍♂️ See you in the session!