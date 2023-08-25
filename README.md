# Consumer Complaints Analysis in Brazil

This repository contains a collection of machine learning tasks and analyses performed on a dataset of consumer complaints about business-related issues in Brazil. The dataset covers various aspects of complaints, including their subjects, regions, and more.

## Dataset

The dataset used for these analyses can be found in the `data` folder. It includes the following columns:

- AnoCalendario
- DataArquivamento
- DataAbertura
- CodigoRegiao
- Regiao
- UF
- strRazaoSocial
- strNomeFantasia
- Tipo
- NumeroCNPJ
- RadicalCNPJ
- RazaoSocialRFB
- NomeFantasiaRFB
- CNAEPrincipal
- DescCNAEPrincipal
- Atendida
- CodigoAssunto
- DescricaoAssunto
- CodigoProblema
- DescricaoProblema
- SexoConsumidor
- FaixaEtariaConsumidor
- CEPConsumidor

## Tasks and Analyses

This repository provides implementation for various machine learning tasks on the dataset, including:

1. Binary Classification - Complaint Resolution Prediction (Solved)
2. Multi-Class Classification - Issue Category Prediction (Solved)
3. Regression - Time to Resolution Prediction
4. Clustering - Regional Complaint Patterns
5. Anomaly Detection - Unusual Complaints
6. Natural Language Processing (NLP) - Sentiment Analysis
7. Feature Importance Analysis

For each task, you will find Jupyter Notebook files (`*.ipynb`) that walk you through the process of data preprocessing, model training, evaluation, and analysis.

## Getting Started

1. Clone this repository to your local machine using your preferred method.

   ```bash
   git clone https://github.com/Dank-del/brazil-consumer-complaints-analysis.git
   ```

2. Set up your environment using Anaconda (recommended):

   - Install [Anaconda](https://www.anaconda.com/products/individual).
   - Create a new Anaconda environment using the provided `environment.yml` file:

     ```bash
     conda env create -f environment.yml
     ```

   - Activate the new environment:

     ```bash
     conda activate consumer-complaints
     ```

3. Launch Jupyter Notebook and navigate to the specific task folder:

   ```bash
   jupyter notebook
   ```

4. Open the corresponding Jupyter Notebook (`*.ipynb`) for the task you're interested in.

5. Follow the instructions in the notebook to run the analysis and understand the results.

## Contributors

- [Sayan Biswas](https://github.com/Dank-del)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
