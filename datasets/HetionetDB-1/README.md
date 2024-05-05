# Description

To Hetionet. add the type of relation `CaC` between two Compounds (Drugs), indicating that these two drugs should not be used together.

The `CaC` data was extracted from TDC-DDI DrugBank dataset, focusing on Drug-drug interactions that related to the severity of side effects. The types of interactions include:

31. 'The risk or severity of hypertension can be increased when #Drug2 is combined with #Drug1.'
32. 'The risk or severity of adverse effects can be increased when #Drug1 is combined with #Drug2.'
33. 'The risk or severity of heart failure can be increased when #Drug2 is combined with #Drug1.'
34. 'The risk or severity of hypotension can be increased when #Drug1 is combined with #Drug2.'
35. 'The risk or severity of bleeding can be increased when #Drug1 is combined with #Drug2.'
36. 'The risk of a hypersensitivity reaction to #Drug2 is increased when it is combined with #Drug1.'

The model was tested on TDC-DDI TWOSIDES dataset.
