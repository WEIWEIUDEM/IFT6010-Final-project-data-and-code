# IFT6010-Final-project-data-and-code
Applying further model compression to TinyBERT
Gao Yinghan, Wei Wei, Frederic Boileau

code:
Compression_TinyBERT.ipynb
please use google colab to run the code.

In the code, we use RTE task as a example to fine-tune model. If you want to try other GLUE tasks, 
please change all the "RTE" to the name of other tasks. For example, use "SST-2" replace all "RTE" in the code.
We use five tasks "CoLA", "QNLI", "STS-B", "SST-2" and "RTE" in the submission package since the limitation of computing capability. 


After running the code, there will generate three folder. The "PRUNING" folder will save the TinyBERT model after pruning. The "Quantitation"
folder will save the TinyBERT model after quantitation. Please ignore the "EVAL" folder, there is nothing in it.

We manully fine-tune the model and manully record all the results of pruning and quantitation.
