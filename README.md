# Movie Recommendation System 🎬

An end-to-end Machine Learning and Natural Language Processing (NLP) project that recommends the top 5 most similar movies based purely on genre and content similarity. This system is optimized to process large-scale datasets efficiently.

## 🚀 Core Project Features
- **Data Preprocessing & Tokenization:** Cleaned and formatted pipe-separated/comma-separated genre strings into lowercase text tags.
- **Exploratory Data Analysis (EDA):** Implemented modern data visualizations using a customized 'magma' color palette to analyze genre distributions.
- **Text Vectorization:** Utilized `CountVectorizer` (Bag of Words model) to transform text-based movie tags into high-dimensional numerical vectors.
- **Mathematical Similarity Engine:** Developed the recommendation core using **Cosine Similarity** to compute exact mathematical distances between movie vectors.

## 🛠️ Tech Stack & Libraries Used
- **Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning & NLP:** Scikit-Learn (`CountVectorizer`, `cosine_similarity`)
- **Data Visualization:** Matplotlib, Seaborn

## 📈 How the Engine Works
1. **Vector Space Mapping:** Every movie's genres are combined into a clean tag and mapped as a vector in a multidimensional space.
2. **Angle Calculation:** When a user queries a movie, the system calculates the cosine of the angle between the queried movie's vector and all other movie vectors.
3. **Sorting & Output:** The system sorts these similarity scores in descending order and extracts the top 5 closest vectors to display as recommendations.

## 📊 Sample Insights
- The system incorporates Exploratory Data Analysis to display frequency distributions, indicating a major dominance of **Drama** and **Comedy** genres within the processed subset.
