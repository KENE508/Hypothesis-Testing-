# Hypothesis-Testing-
## Chi2 Test
 * STEP 1 - Make the set of hypothesis you will be working with 

* STEP 2 - Create your contingency table

* STEP 3 - Get your chi2, P, dof and expected table

* STEP 4 - Check if your P value is less than or greater than alpha

  ## Codes
* STEP 1: - Null (H₀): and Alternative (H₁):

* STEP 2: contingency_table = pd.crosstab(df["column_1"], df["column_2"])

* STEP 3: chi2, p, dof, expected = chi2_contingency(con_table)

* STEP 4: alpha = 0.05
if p < alpha:
else:
