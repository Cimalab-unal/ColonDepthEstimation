# SfSNet - Leveraging a realistic synthetic database to learn Shape-from-Shading for estimating the colon depth in colonoscopy images

Josué Ruano(a), Martín Gómez(b), Eduardo Romero(a), and Antoine Manzanera(c)

(a) Computer Imaging and Medical Applications Laboratory (CIM@LAB), Universidad Nacional de Colombia, 111321, Bogotá, Colombia.<br>
(b) Unidad de Gastroenterología, Hospital Universitario Nacional, 111321, Bogotá, Colombia.<br>
(c) Unité d’Informatique et d’Ingénierie des Systémes (U2IS), ENSTA Paris, Institut Polytechnique de Paris, Palaiseau, 91762, Ile de France, France.

<img src="graphical_abstract.png?raw=True" width="800px" style="margin:0px 0px"/>

This code provides the resulting model from implementation of the work "SfSNet - Leveraging a realistic synthetic database to learn shape-from-Shading for estimating the colon depth in colonoscopy images".

Follow these instructions to run the tests and reproduce the reported results. The full code will be released after publication. 

These scripts are designed to be easily run in a free Google Colab environment. The file also contains the test collections, the synthetic and the real.

	1-  Option 1: Download this repository and upload the complete repository in your Google Drive account.

        Option 2: Fork this repository and open the notebooks in Google colab by accessing in "https://colab.research.google.com/" and selecting the repository and notebook using the tool 'GitHub'.


	2- Open and execute the notebooks "testing_synthetic_database.ipynb" or "testing_real_database.ipynb" in Google Colab.


Notes:
	- If you want to save estimated depth maps, set the variable "params['imgSave']=True", and they will be saved in the folder named "results".




# Synthetic colonoscopy database

At the link below you can request access to the database.

https://forms.gle/USQkvguACcNTeGH26

# Latest work:

We invite you to see our latest work accepted in IEEE International Symposium on Biomedical Imaging (ISBI), where we use SfSNet to estimate the size of polyps. We provide ground-truth size of synthetic polyps and our results.

<img src="polyp_size_pipeline.png?raw=True" width="800px" style="margin:0px 0px"/>

Ruano, J., Bravo, D., Giraldo, D., Gómez, M., González, F. A., Manzanera, A., & Romero, E. (2024, May). __Estimating Polyp Size From a Single Colonoscopy Image Using a Shape-From-Shading Model__. In 2024 IEEE International Symposium on Biomedical Imaging (ISBI). IEEE. [DOI](https://doi.org/10.1109/ISBI56570.2024.10635358)

Repository: [Github](https://github.com/jaruanob/PolypSizeEstimation_SfSNet) 
