# Hypothesis-Testing-in-Healthcare-Drug-Safety
Pharmaceutical drugs have become an essential part of our health. They need to be safe with little or no adverse effects. This project's tasks is to create reports on drugs to determine if the adverse reactions of a hypothetical drug are significant.

A pharmaceutical company GlobalXYZ has just completed a randomized controlled drug trial. To promote transparency and reproducibility of the drug's outcome, they (GlobalXYZ) have presented the dataset to your organization, a non-profit that focuses primarily on drug safety. The dataset provided contained five adverse effects, demographic data, vital signs, etc. Your organization is primarily interested in the drug's adverse reactions. It wants to know if the adverse reactions, if any, are of significant proportions. It has asked you to explore and answer some questions from the data.

The dataset drug_safety.csv was obtained from the Vanderbilt University Department of Biostatistics. It contained five adverse effects: headache, abdominal pain, dyspepsia, upper respiratory infection, chronic obstructive airway disease (COAD), demographic data, vital signs, lab measures, etc. The ratio of drug observations to placebo observations is 2 to 1.



# The columns in the modified dataset are:

sex	(The gender of the individual)
age	(The age of the individual)
week	(The week of the drug testing)
trx	(The treatment (Drug) and control (Placebo) groups)
wbc	(The count of white blood cells)
rbc	(The count of red blood cells)
adverse_effects	(The presence of at least a single adverse effect)
num_effects	(The number of adverse effects experienced by a single individual)


# For this project, the goals are to

1. Determine if the proportion of adverse effects differs significantly between the Drug and Placebo groups, saving the p-value as a variable called two_sample_p_value.

2. Find out if the number of adverse effects is independent of the treatment and control groups, saving as a variable called num_effects_p_value containing a p-value.

3. Examine if there is a significant difference between the ages of the Drug and Placebo groups, storing the p-value of your test in a variable called age_group_effects_p_value



