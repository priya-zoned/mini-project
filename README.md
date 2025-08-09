# TLSAN
PROJECT OVERVIEW:<br>
Implemented and evaluated TLSAN (Time-aware Long- and Short-term Attention Network), an attention-based deep learning model for next-item recommendation, by replicating a research paper. The project compared TLSAN with 8 other deep learning models (CNN, BiLSTM, SHAN, PACA, ATRank, LSPM, CSAN, BPR-MF) on the Amazon Movies & TV dataset, with TLSAN achieving the highest AUC score of 0.98.

KEY FEATURES:<br>
1.Modeled long- and short-term user preferences using personalized time-aware attention mechanisms.
2.Dual-branch architecture with category-aware and feature-wise attention.
3.Evaluated with AUC, Precision@K, Recall@K, and visualization tools (boxplots, confusion matrices).
4.Dataset size: 8.4M+ interactions from Amazon Movies & TV reviews.

TECH STACK:<br>
1.Python, PyTorch, Pandas, Scikit-learn, Matplotlib, Seaborn
2.Environment: Kaggle

KEY RESULTS:<br>
TLSAN achieved 0.98 AUC,outperforming all baseline models.           
 MODEL  AUC  
 TLSAN 	0.98 <br>
 PACA   0.95    
 LSTM   0.93     
 SHAN   0.86  
 CNN    0.76   

REFERENCE:<br>
TLSAN: Time-aware Long- and Short-term Attention Network for Next Item Recommendation <br>
DOI: 10.1016/j.neucom.2021.02.015


