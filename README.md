# Land-Use-Land-Cover-GIS

This project focuses on land-use and land-cover classification using ArcGIS Pro and Google Earth Pro, employing supervised and unsupervised learning techniques. During classification, several challenges were encountered:

Urban areas and barren land exhibited similar spectral signatures, making differentiation difficult.

Dry riverbeds reflected similar signatures to urban areas and barren land, leading to misclassification.

Adjusting urban classification introduced errors in barren land classification due to spectral overlap.

Hilly terrain posed challenges in forest classification, especially in shadowed regions.

To address these issues, additional post-processing techniques were applied, and a new class was introduced after final analysis to improve accuracy and better distinguish between ambiguous land cover types.



#Steps Taken 

1) Image processing in ERDAS and bands ARCGIS

2)one land set includes 36000 km2 aprox Used Google Earth to have better understanding of each pixle wheather , barren land , urban land, vegetative land etc

3) Then did supervised & unsupervised classification on ARCGIS after a lot of pixle corrections
4) Calculate area of land use and Make change detection matrix and time series
5) This allows to predict what type of land is in the given selected area

#Data sets
<img width="793" alt="Screenshot 2025-04-01 at 03 28 54" src="https://github.com/user-attachments/assets/7a6eff47-5167-44d8-b086-e420a9e0dd55" />
<img width="796" alt="Screenshot 2025-04-01 at 03 29 17" src="https://github.com/user-attachments/assets/cc6d23b6-883d-460e-ba37-3bbc160f8cf6" />

After Preprocessing and cleaning for training
![WhatsApp Image 2025-04-01 at 3 30 06 AM](https://github.com/user-attachments/assets/e50b5b98-7447-4e12-8044-5654a06bc763)




