# TUR2SQL: A Cross-Domain Turkish Dataset For Text-to-SQL

## Results

If you submit papers on TUR2SQL, please let us know so we can merge your results into the results table.

### Execution Accuracy (EX) and Logical Form Accuracy (LFA) of LLMs on the TUR2SQL development set

| Model | Logical Form Accuracy (LFA) | Execution Accuracy (EX) |
| :---:        | :---:         |
| SQLNet | 42.92 | 44.49 |
| ChatGPT | 93.61 | 98.79 |
| T5 (With Schema Context) [1] | 98.24 | 98.24 |
| T5 (Without Schema Context) [1] | 05.83 | 05.83 |
| SQLCoder (With Schema Context) [1] | 96.21 | 96.21 |
| SQLCoder (Without Schema Context) [1] | 97.13 | 97.13 |

### Execution Accuracy (EX) and Logical Form Accuracy (LFA) of LLMs on the TUR2SQL test set

| Model | Logical Form Accuracy (LFA) | Execution Accuracy (EX) |
| :---:        | :---:         |
| SQLNet | 39.03 | 40.19 |
| ChatGPT | 86.72 | 98.38 |
| T5 (With Schema Context) [1] | 98.38 | 98.38 |
| T5 (Without Schema Context) [1] | 05.18 | 05.18 |
| SQLCoder (With Schema Context) [1] | 97.04 | 97.04 |
| SQLCoder (Without Schema Context) [1] | 96.48 | 96.48 |

### References
[1] Demirkıran, Ferhat et al. "Enhancing Text-to-SQL Conversion in Turkish: An Analysis of LLMs with Schema Context." 2024 9th International Conference on Computer Science and Engineering (UBMK). IEEE, 2024.

---

TUR2SQL dataset consists of 10,809 pairs of natural language statements and their corresponding SQL queries. The generation of TUR2SQL is detailed in our UBMK-2023 [paper](https://ieeexplore.ieee.org/abstract/document/10286686):

	@inproceedings{tur2sql,
	    title     	= {TUR2SQL: A Cross-Domain Turkish Dataset For Text-to-SQL},
	    author    	= {Kanburoğlu, Ali Buğra and Tek, F. Boray},
	    booktitle   = {2023 8th International Conference on Computer Science and Engineering (UBMK)},
	    year      	= {2023},
	    pages       = {206-211},
	    doi         = {10.1109/UBMK59864.2023.10286686}
	} 
