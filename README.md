# Book-Recommendation-System-

### Overview
This project is a powerful and scalable recommendation system designed to suggest books to users based on their preferences and past interactions. It employs a combination of advanced techniques, including collaborative filtering, content-based filtering, and hybrid approaches, to deliver highly accurate and personalized book recommendations. The system also incorporates Bloom Filter and Locality-Sensitive Hashing (LSH) to optimize performance and handle large-scale datasets efficiently.

### Features
<span style="font-size:24px;">•</span> **Collaborative Filtering**: Recommends books based on the ratings and preferences of similar users, enhancing personalization.

<span style="font-size:24px;">•</span> **Content-Based Filtering**: Suggests books by analyzing metadata, such as genres, authors, and descriptions, ensuring relevance to user interests.

<span style="font-size:24px;">•</span> **Hybrid Recommendation Model**: Combines collaborative and content-based methods to provide more accurate and diverse recommendations.

<span style="font-size:24px;">•</span> **Efficient Lookup and Filtering**:

**Bloom Filter**: Ensures efficient filtering, minimizing unnecessary computations during recommendation generation.

**Locality-Sensitive Hashing (LSH)**: Groups similar books based on metadata, enabling faster retrieval and enhanced scalability.

### Technologies Used
<span style="font-size:24px;">•</span> **Python**: Core language used for implementing system logic and data processing.

<span style="font-size:24px;">•</span> **Pandas & NumPy**: Libraries for data manipulation and analysis...

<span style="font-size:24px;">•</span> Surprise Library: Advanced library for collaborative filtering and recommendation algorithms.

### Usage
**Dataset Preparation**: Ensure the dataset includes user ratings and book metadata (e.g., title, author, genres).

**Model Training**: Train recommendation models on the dataset using the provided scripts.

**Efficient Filtering**: Use the Bloom Filter to reduce redundant computations during recommendation generation.

**Similarity Grouping**: Leverage LSH to group similar books and enhance the recommendation process.

**Generating Recommendations**: Run the script to generate recommendations for users or books.

### Dataset link 
The dataset used for this project is available on Kaggle: [Books Dataset](https://www.kaggle.com/datasets/saurabhbagchi/books-dataset).
