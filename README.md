# Fraude_Bancario
Proyecto Fraude Bancario de tarjetas de crédito y débito
El DataSet fue suministrado por Kaggle
En este proyecto se utiliaron 3 modelos:
  -XGBOOST
  -RandomForest
  -Regresión Logitica
  
 El proyecto consiste en clasificar los datos fraudulentos representados como 1 y los datos no fraudulentos representados como 0.
 Los datos Fraudulentos representan un 0,17% del DataSet total, por tanto es necesario balancear los datos. Para balancear los 
 datos se utilizaron los métodos de Penalización para Regresión Logistica, Oversampling para Random Forest y Ensambling Method 
 para XGBOOST. 
 
 Para las pruebas se utilizó colab.research.google.com/
 El DataSet estuvo cargado en Google Drive y se lo llamó desde Colab utilizando la librería
  -from google.colab import drive
  -drive.mount("/content/drive")
  -ftc = pd.read_csv("drive/My Drive/Fraude Bancario/creditcard.csv")
