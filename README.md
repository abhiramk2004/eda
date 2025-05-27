
Used .describe() and .info() to get basic distribution metrics.
Checked for missing values and planned imputation strategies.
Histograms and KDE plots for Age, Fare, Pclass, etc.
Boxplots to detect outliers in numeric features.
Countplots for categorical variables like Sex, Embarked, Survived.
Correlation matrix and pairplot for numeric features.
Survival rate visualizations across:
  - Gender
  - Class
  - Age groups
  - Embarked port
  - Family size
  - Cabin availability

FamilySize = SibSp + Parch.
IsAlone = 1 if no family members onboard.
Extracted Title from Name column.
Created age bins for easier interpretation.
Females had much higher survival rates (~74%) vs males (~19%).
1st class had highest survival (~63%), 3rd class the lowest (~24%).
Children (<10) and adults (30–40) had higher survival.
Higher fare correlated with survival (often linked with Pclass).
Passengers from Cherbourg (C) had higher survival.
Small family groups (1–3) survived more than solo or large groups.
Non-null Cabin values imply higher survival (likely higher class).
Solo travelers had lower survival chances.
