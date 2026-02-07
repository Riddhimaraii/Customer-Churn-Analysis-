\documentclass[12pt,a4paper]{article}

\usepackage[margin=1in]{geometry}
\usepackage{setspace}
\usepackage{titlesec}
\usepackage{hyperref}

\setstretch{1.15}

\titleformat{\section}{\large\bfseries}{}{0em}{}
\titleformat{\subsection}{\normalsize\bfseries}{}{0em}{}

\begin{document}

\begin{center}
    \textbf{\LARGE Customer Churn Analysis} \\[0.3cm]
    \textbf{Riddhima Rai} \\ 
    Data Science Project \\[0.2cm]
    GitHub Repository: \url{https://github.com/Riddhimaraii/Customer-Churn-Analysis}
\end{center}

\vspace{0.5cm}

\section{Abstract}

Customer churn is a critical business metric that represents the rate at which customers stop using a company's products or services. This project focuses on performing exploratory data analysis (EDA), predictive modeling, and interpretation of the churn dataset to identify patterns, key influencing factors, and opportunities for retention. The analysis leverages Python and machine learning techniques to generate actionable insights.

\section{Introduction}

In competitive industries such as telecommunications, retaining customers is more cost-effective than acquiring new ones. Predicting customer churn helps businesses proactively address issues that lead to attrition. This project analyzes customer data to understand churn behavior, extract important features, and build predictive models to support strategic decision-making.

\section{Dataset Description}

The dataset used in this project contains customer profile information and usage metrics. Key attributes include:

\begin{itemize}
    \item Customer ID
    \item Demographic information (e.g., age, gender)
    \item Service usage patterns (e.g., tenure, data usage)
    \item Billing information
    \item Churn indicator (target label)
\end{itemize}

This dataset enables both descriptive and predictive analysis related to customer churn.

\section{Tools and Technologies}

The following tools were used to perform the analysis:

\begin{itemize}
    \item Python programming language
    \item Jupyter Notebook for exploration and development
    \item NumPy for numerical computing
    \item Pandas for data manipulation
    \item Matplotlib and Seaborn for visualization
    \item Scikit-learn for machine learning modeling
\end{itemize}

These tools facilitated data preprocessing, visualization, model training, and evaluation.

\section{Methodology}

The analytical workflow followed in this project includes:

\begin{enumerate}
    \item Data loading and inspection
    \item Data cleaning and preprocessing
    \item Feature scaling and transformation
    \item Exploratory data analysis to understand trends and correlations
    \item Training and evaluation of predictive models
    \item Interpretation of results and insights
\end{enumerate}

\section{Exploratory Data Analysis}

Exploratory Data Analysis (EDA) helped identify patterns and relationships in the data. Key observations include:

\begin{itemize}
    \item Distribution of churn across demographics
    \item Correlation between tenure and churn
    \item Differences in service usage between churned and retained customers
    \item Visual trends in billing and usage behaviors
\end{itemize}

Visualizations such as histograms, box plots, and correlation matrices supported these insights.

\section{Modeling and Evaluation}

The project tested multiple machine learning models to predict customer churn. Models included:

\begin{itemize}
    \item Logistic Regression
    \item Random Forest Classifier
    \item Support Vector Machine
    \item Gradient Boosting Models
\end{itemize}

Model performance was evaluated using standard metrics:

\begin{itemize}
    \item Accuracy
    \item Precision
    \item Recall
    \item F1-score
    \item ROC-AUC
\end{itemize}

The best-performing model was selected based on evaluation metrics and cross-validation results.

\section{Results}

The predictive models achieved competitive performance in identifying likely churners. Several feature variables such as tenure, contract type, and monthly charges were identified as significant predictors of customer churn.

\section{Conclusion}

This project demonstrates the application of data science and machine learning techniques to customer churn prediction. The analysis uncovers meaningful insights that can guide targeted retention strategies and business decisions. Predictive modeling enhanced the understanding of churn risk factors.

\section{Future Work}

Possible enhancements to this project include:

\begin{itemize}
    \item Incorporating additional feature engineering techniques
    \item Using advanced models such as XGBoost or neural networks
    \item Deploying the prediction model through a web application
    \item Building interactive dashboards for real-time monitoring
\end{itemize}

\section{References}

\begin{itemize}
    \item Customer churn dataset
    \item Python and Scikit-learn documentation
    \item Data visualization library references
\end{itemize}

\end{document}
