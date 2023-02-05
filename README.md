# Edoardo_Portfolio
Edoardo Portfolio progect

[Progetto 1: Machine Learning Project](https://github.com/EdoardoCasa/machine_learning_pro/blob/main/lav2.ipynb)
In questo progetto di machine learning creo un modello in grado di prevedere il livello di progressione del diabete

X,y = datasets.load_diabetes(return_X_y=True)

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.33,random_state=0)

reg = linear_model.Lasso(alpha=0.1)

[Progetto 2: Data science Project](https://github.com/EdoardoCasa/data_science_progect/blob/main/progf.ipynb)
In questo progetto cerco di capire i fattori che influenzano maggiormente i voti finali degli studenti

dl["sex"].value_counts()

sns.histplot(dl.age,kde=True, bins=8, discrete=True)

plt.title("distribuzione dell'età")

![](https://github.com/EdoardoCasa/Edoardo_Portfolio/blob/main/immagini/images.png)

theme: Minima
