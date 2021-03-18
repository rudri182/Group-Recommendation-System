# Group-Recommendation-System 

#### Dataset:

Dataset consists of five columns like *Age*, *Gender*, *Movies*, *Hobbies*, *Music*. The values are entered randomly using numpy's random function. 

*Age* : It has ages of people between 20 to 30.

*Gender* : It has values like 0(F) and 1(M).

*Movies*, *Hobbies*, *Music* : It has values between 1 to 10. It signifies the interest and how a persin will rate oneself to spend the leisure time.

Before applying any algorithm, the data is scaled using _StandardScaler()_. After normalizing the data, K-Means clustering algorithm is applied. To decide how many clusters to be formed, *elbow* method is used. Atlast, visualization of cluster is done. 

Feel free to create issues and pull requests 🎉
