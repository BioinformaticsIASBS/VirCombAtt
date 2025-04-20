# Attention-Based Solution for Synergistic Virus Combination Therapy
## by Shayan Majidifar, Mohsen Hooshmand

# **Data**
All necessary data for training attention-based models is stored in the "Data" folder. The dataset contains:
* **“drug_dictionary.txt” contains the drugs’ names and their corresponding DrugBank IDs.**
* **“virus_dictionary.txt” contains the viruses’ names and their corresponding NCBI IDs.**
* **“All_Virus_fasta_CT.fasta” contains the viruses’ nucleotide sequences in FASTA format.**
* **“Xindex_ratio3.txt” is a text data file that contains drugs and virus combinations with a  ratio of 3.**
* **“Y_ratio3.txt” contains the corresponding label of each combination in Xindex_ratio3.txt.**
* **“Xindex_ratio5.txt” is a text data file that contains drugs and virus combinations with a ratio of 5.**
* **“Y_ratio5.txt” contains the corresponding label of each combination in Xindex_ratio5.txt.**
* **“Xindex_ratio10.txt” is a text data file that contains drugs and virus combinations with a ratio of 10.**
* **“Y_ratio10.txt” contains the corresponding label of each combination in Xindex_ratio10.txt.**
* **“Xindex_ratio100.txt” is a text data file that contains drug and virus combinations with a ratio of 100.**
* **“Y_ratio100.txt” contains the corresponding label of each combination in Xindex_ratio100.txt.**
* **“Similarity_Matrix_Drugs.txt” contains the drug’s Tanimoto similarities and is arranged in the drugs_dictionary file order.** 
* **“Similarity_Matrix_Viruses.txt” contains virus sequence alignment score and is arranged in the order of the virus_dictionary file.**
* **“small_mulecule_drug_similarity.xlsx” contains the drug’s ID, Smile, and Tanimoto similarities and is arranged in drugs_dictionary file order.** 
* **“virus_similarity_matrix_CT.xlsx” contains virus sequence alignment score in xlsx format, and it is arranged in the order of the virus_dictionary file.**
# **Train Attention-based(VCTatDot and VCTatMLP) models**
In our experiments, we utilized Python 3.9.4. 
To run the VCTatDot model, open the VCTatDot.ipynb file, which is in Jupyter Notebook format, and execute each cell in sequence. 
Similarly, to run the VCTatMLP model, open the VCTatMLP.ipynb file, also in Jupyter Notebook format, and execute each cell in sequence.
Please note that the current Jupyter notebooks are based on a ratio of 100. If you wish to run for a different ratio, you must read data from the corresponding ratio files, such as Xindex_ratio3.txt and Y_ratio3.txt.

