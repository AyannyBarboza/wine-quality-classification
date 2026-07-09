# wine-quality-classification
Projeto de Machine Learning para classificar a qualidade do vinho. 

Este projeto utiliza Machine Learning para classificar vinhos entre **Alta Qualidade** (nota >= 7) e **Baixa/Média Qualidade** (nota < 7) com base em suas características químicas.

Principais Descobertas
*   **Dados Desbalanceados:** O dataset possui **86,09%** de vinhos comuns (Classe 0) e apenas **13,91%** de vinhos excelentes (Classe 1).
*   **Correlação:** O teor alcoólico (`alcohol`) é a variável que mais influencia positivamente na nota final do vinho.

Tecnologias
*   Python (Google Colab)
*   Pandas, NumPy, Matplotlib e Seaborn
*   Scikit-Learn (Machine Learning)

Conclusão: O Random Forest foi o melhor modelo. Ele superou as limitações lineares da Regressão Logística e se adaptou muito melhor aos dados desbalanceados, sendo a ferramenta ideal para apoiar o controle de qualidade na vinícola.

*Ayanny Barboza*  
