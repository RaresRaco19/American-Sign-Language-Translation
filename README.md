# American-Sign-Language-Translation
Pentru a rula fisierele IPYNB pentru traducerea limbajului semnelor veti avea nevoie de google colab sau jupyter notebook
# Setul de date
Pentru a putea rula fiserele, avem nevoie sa descarcam setul de date Google ASL
de pe link-ul https://www.kaggle.com/competitions/asl-fingerspelling
Acesta trebuie stocat in google drive la locatia /MyDrive/Database
# Descarcarea fisierelor
Se va clona repository-ul si mai apoi fisierele se vor icarca in Google colab sau jupyter notebook
# Cerinte suplimentare
Trebuie sa ne asiguram ca pe google drive mai exista spatiu pentru salvarea folderulu "tdfs"
Pentru ca acesta fisierele sa ruleze in conditi optime recomand folosirea abonamentului colab pro+

# Utilizarea 
Se va rula prima data fisierul TFRecords.ipynb
O data ce vom avea salvat folderul tfds
Vom putea rula si cel de al doilea fisier
Este foarte sa ne asiguram ca toate casetele sa fie rulate in ordine,
Pentru a modifica hiperparamentri modelului se va modifica creerea instantei acestuia
# Utilizarea generate
Pentru a utiliza functia generate vom avea nevoie sa compilam modelulu cu parametrul run_eagerly=True
