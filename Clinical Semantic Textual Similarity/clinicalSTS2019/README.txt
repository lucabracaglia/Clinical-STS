This package contains the training data for the Clinical Semantic Textual Similarity
(ClinicalSTS) shared task. The dataset has the following tab-separated format:

  * One STS pair per line.
  * Each line contains the following fields: STS Sent1[tab]STS Sent2[tab]Similarity Score


Example:

Insulin NPH Human [NOVOLIN N] 100 unit/mL suspension subcutaneous as directed by prescriber.	 Insulin NPH Human [NOVOLIN N] 100 unit/mL suspension 63-76 units subcutaneous as directed by prescriber.	3.5 

-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*
Note: Similarity score is a continuous value on a scale from 0 to 5, with 0 indicating that the medical semantics
 of the sentences are completely independent and 5 signifying semantic equivalence.  
correlation-noconfidence.pl is an evaluate tool for computing Pearson correlation coefficient.
-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*-*

