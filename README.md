# ADF

## Copying Selected File 
-coping a file only if the name starts with 'Fact'.\
<img width="1652" height="746" alt="image" src="https://github.com/user-attachments/assets/63594fc3-bc8d-4e59-bee0-7cacf07d84e6" />

-Get meta data return all the contents of the folder in the array format.\
  include arguments ChildItems in the field lists.\
-for each loop runs based on the total number of files in the folder .\
  @activity('Metadata').output.childItems
-if the file name starts with 'fact' perform the copy data.\
  @startswith(item().name,'Fact')
  <img width="1792" height="1038" alt="image" src="https://github.com/user-attachments/assets/87ded731-846e-4e72-8a47-da066c6ca834" />
  <img width="1792" height="1038" alt="image" src="https://github.com/user-attachments/assets/c5300495-6c40-4393-b759-de7b69378cd1" />

- Tranformations

   <img width="2622" height="900" alt="image" src="https://github.com/user-attachments/assets/6df06004-8beb-4db8-9835-0884d222c13b" />

