# Breast Cancer Dataset 

I have worked on an independent project to explore various Machine Learning algorithms on breast cancer datasets from the UCI Machine Learning Repository to classify whether a set of readings from clinical reports are positive for breast cancer or not. 

**Background:**

Breast cancer is the most common cancer among women in the world. It account for 25% of all cancer cases, and affected over 2.1 Million people in 2015. It starts when cells in the breast begin to grow out of control. These cells usually form a tumor that can often be seen on an X-ray or felt as a lump.

Early diagnosis significantly increases the chances of surviver. The key challenges against it's detection is how to classify tumors into malignant(Cancer) or benign(not cancer). A tumor is considered malignant (Cancer) if the cells can grow into surrounding tissues or spread to distant areas of the body. A benign tumor does not invade nearby tissue or spread to other parts of the body the way cancer can. But benign tumors can be serious if they press on vital structures such as blood vessel or nerves.

Machine Learning technique can dramatically improve the level of diagnosis in breast cancer. Research shows that experience physicians can detect cancer by 79% accuracy, while 91%(up to 97%) accuracy can be achieved using Machine Learning techniques.

**Aim**

In this study, my task is to classify tumors into malignant (cancer) or benign using features obtained from several cell images. I use radius mean as the dependant variable.

**Methodology**


I train test split at 0.25 and 0.75, and use cross validation and k-fold cross validation.

I use the following Machine Learning models: Logistic Regression, k Nearest Neighbours, Support Vector Machines, Decision Trees, Neural Networks

**Attribute Information:**

ID number Diagnosis (M = malignant, B = benign) Ten real-valued features are computed for each cell nucleus:

Radius (mean of distances from center to points on the perimeter) 
Texture (standard deviation of gray-scale values) 
Perimeter Area Smoothness (local variation in radius lengths) 
Compactness (perimeter^2 / area - 1.0) 
Concavity (severity of concave portions of the contour) 
Concave points (number of concave portions of the contour) 
Symmetry Fractal dimension ("coastline approximation" - 1)
