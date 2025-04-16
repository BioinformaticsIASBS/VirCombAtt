# Attention-Based Solution for Synergistic Virus Combination Therapy
## by Shayan Majidifar, Mohsen Hooshmand

# **Data**
All necessary data for training attention-based models are stored in the "Data" folder. The dataset contains:
* **“drug_dictionary.txt” contains the drugs’ names and their corresponding DrugBank IDs.**
* **“virus_dictionary.txt” contains the viruses’ names and their corresponding NCBI IDs.**
* **“All_Virus_fasta_CT.fasta” contains the viruses’ sequences in FASTA format.**
* **“Drugs_info.csv” is a table in which each row drug name, its corresponding DrugBank ID, its SMILES, and generated Tanimoto similarities with all drugs in the dataset.**
* **“Xindex.npy” is a Python binary data file that contains all Cartesian products of drug×drug× virus (including positive and negative combinations.)**
* **“Y.npy” contains the corresponding label of each combination in Xindex.npy.**
* **“Xindex_ratio3.txt” is a txt data file that contains drugs and virus combination with ratio equals with 3.**
* **“Y_ratio3.txt” contains the corresponding label of each combination in Xindex_ratio3.txt.**
* **“Xindex_ratio5.txt” is a txt data file that contains drugs and virus combination with ratio equals with 5.**
* **“Y_ratio5.txt” contains the corresponding label of each combination in Xindex_ratio5.txt.**
* **“Xindex_ratio10.txt” is a txt data file that contains drugs and virus combination with ratio equals with 10.**
* **“Y_ratio10.txt” contains the corresponding label of each combination in Xindex_ratio10.txt.**
* **“Xindex_ratio100.txt” is a txt data file that contains drugs and virus combination with ratio equals with 100.**
* **“Y_ratio100.txt” contains the corresponding label of each combination in Xindex_ratio100.txt.**
* **“Similarity_Matrix_Drugs.txt” contains the drug’s Tanimato similarities and is arranged in drug_dict file order.** 
* **“Similarity_Matrix_Viruses.txt” contains virus sequence alignment score and is arranged in the order of the virus_dict file.**
* **“small_mulecule_drug_similarity.xlsx” contains the drug’s, ID, Smile, and Tanimato similarities and is arranged in drug_dict file order.** 
* **“virus_similarity_matrix_CT.xlsx” contains virus sequence alignment score in xlsx format and it is arranged in the order of the virus_dict file.**
# **Train Attention-based(VCTatDot and VCTatMLP) models**
In our experiments, we utilized Python 3.9.4. 
To run the VCTatDot model, open the VCTatDot.ipynb file, which is in Jupyter Notebook format, and execute each cell in sequence. 
Similarly, to run the VCTatMLP model, open the VCTatMLP.ipynb file, also in Jupyter Notebook format, and execute each cell in sequence.

