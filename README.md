# American-Sign-Language-Translation
Pentru a rula fisierele IPYNB pentru traducerea limbajului semnelor veti avea nevoie de google colab sau jupyter notebook
# Setul de date
Pentru a putea rula fiserele, avem nevoie sa descarcam setul de date Google ASL
de pe link-ul https://www.kaggle.com/competitions/asl-fingerspelling
Acesta trebuie stocat in google drive la locatia /MyDrive/Database
# Descarcarea fisierelor
Se va clona repository-ul si mai apoi fisierele se vor incarca in Google colab sau Jupyter Notebook
# Cerinte suplimentare
Trebuie sa ne asiguram ca pe google drive mai exista spatiu pentru salvarea folderulu "tdfs"


# Utilizarea 
Se va rula prima data fisierul TFRecords.ipynb, dupa ce vom avea salvat folderul tfds, o sa putem rula si cel de al doilea fisier.
Este foarte sa ne asiguram ca toate casetele sa fie rulate in ordine.

# Utilizarea generate
Pentru a utiliza functia generate vom avea nevoie sa compilam modelul cu parametrul run_eagerly=True
