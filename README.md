This project investigated the determinants of apartment rental prices using advanced data mining and big data analytics techniques. The analysis was conducted on a structured rental dataset, with the objective of building predictive models, designing an efficient data management architecture, and addressing scalability and privacy challenges relevant to real-world applications.

The first phase focused on exploratory data analysis and statistical testing. Independent sample t-tests and ANOVA were applied to identify significant differences in rental prices across key categorical variables such as construction type, utilities, balcony availability, and amenities. These statistical insights guided feature engineering and informed the predictive modelling process.

For the modelling phase, three approaches were compared: Multiple Linear Regression (MLR) as a baseline, Random Forest Regression, and XGBoost Regression as advanced ensemble methods. Each model was trained and validated using k-fold cross-validation, with performance evaluated against metrics such as RMSE, MAE, and R². The impact of location was further examined by incorporating geospatial features (latitude and longitude) to test whether address was a significant predictor of price.

The second phase of the project addressed data storage and scalability. A relational database in 3NF was designed and represented using a UML-standard ER diagram, supporting efficient storage of rental listings, features, and temporal data. Beyond relational design, scalable processing frameworks were explored, comparing Hadoop-based batch systems with real-time Spark streaming approaches. A hybrid architecture was proposed to balance cost efficiency with low-latency performance.

Finally, ethical and legal aspects were evaluated, focusing on data privacy, consent, and anonymisation in a customer-facing application context.

Overall, the project provided both technical and practical insights into predictive analytics for housing markets, while also demonstrating the importance of scalable architectures and responsible data governance.
