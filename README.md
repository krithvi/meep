# meep
The purpose of this project is to build a Sentiment Analysis system that uses machine learning to flag negative comments. The dataset contains statements, IDs and corresponding labels to indicate if it's positive or negative. The model is built using logistic regression, Support Vector Machine (SVM) and Random Forest Algorithm and as an optimisation on the existing project done on Naive Bayes Algorithm. The libraries to be used in the project include sklearn and pandas.

# Justification
Among the models used, Random Forest exhibits the highest accuracy(0.993). It is due to the following reasons: 
1. They are based on trees, so scaling of the variables doesn't matter. Any monotonic transformation of a single variable is implicitly captured by a tree.
2. They use the random subspace method and bagging to prevent overfitting.
3. If they are done well, you can have a random forest that deals with missing data easily.
4. Automated feature selection is built in.

# Base Paper link: 
https://www.researchgate.net/profile/Rui_Zhao61/publication/310768726_Automatic_Detection_of_Cyberbullying_on_Social_Networks_based_on_Bullying_Features/links/5c6cbd1392851c1c9dee9d9d/Automatic-Detection-of-Cyberbullying-on-Social-Networks-based-on-Bullying-Features.pdf

Automatic Detection of Cyberbullying on Social Networks based on Bullying Features - Rui Zhao, Anna Zhuo, Kezhi Mao

- Enhanced Bag of words concatenates BoW features, latent semantic features and bullying features together
- Linear SVM is adopted to detect bullying messages
