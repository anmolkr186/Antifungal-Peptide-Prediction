# Antifungal-Peptide-Prediction

For this assignment, we applied the SVM prediction model using the five-fold cross
validation method. We carried out this prediction on various input parameters applied on
the amino acid sequences which are listed as follows:
* Amino Acid Composition
* Dipeptide Composition
* Tripeptide Composition
* Hydrophobicity
We found out that our best score is 0.92717 using the Tripeptide Composition of amino
acid sequences.
## Execution Information
<p> We implemented our code on the Google Colab Platform. We have submitted the .ipynb
file for the same. Follow the following steps to execute the code: </p>
1. Open colab.research.google.com
2. Open the final_tripeptide_svm.ipynb which is included in the submission.
3. After this, upload the train.csv and test.csv in the root directory of the notebook. These files are required by the program to read the IDs, sequences and labels.
4. Run the program from Runtime > Run all or using the shortcut Ctrl + F9.
5. The final output file named tripeptide_svm_pred.csv is generated in the root directory of the notebook.

## Co-Contributors
* Tejas Dubhir
* Rakshit Singh
