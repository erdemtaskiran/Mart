# MART-Lexical Complexity and Creativity 

# Key Features
Semantic Complexity Analysis

# Baseline Generation: 
Uses the BLIP-2 vision-language model (Salesforce/blip-image-captioning-large) to generate baseline descriptions of artwork
Multilingual Processing: Employs the paraphrase-multilingual-MiniLM-L12-v2 sentence transformer for cross-lingual semantic analysis
Complexity Measurement: Calculates semantic complexity using cosine distance from AI-generated baseline descriptions

# Statistical Analysis

ANOVA Testing: Performs one-way ANOVA to compare semantic complexity across different experimental groups
Post-hoc Analysis: Implements Tukey's HSD test for pairwise group comparisons
Advanced Visualization: Creates comprehensive bar plots with significance indicators and statistical annotations

# Dependencies

PIL (Python Imaging Library)
PyTorch
Transformers (Hugging Face)
Sentence Transformers
SciPy & StatsModels for statistical analysis
Matplotlib & Seaborn for visualization
Pandas & NumPy for data manipulation

# Methodology

Image Processing: Loads and processes artwork images using PIL
Baseline Creation: Generates standardized descriptions using BLIP-2 with token limits
Semantic Embedding: Converts both baseline and participant descriptions into high-dimensional vectors
Complexity Scoring: Measures semantic distance from baseline to quantify creativity/complexity
Statistical Testing: Performs rigorous statistical analysis with multiple comparison corrections
