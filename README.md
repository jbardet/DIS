# DIS - Distributed Information Systems

This repository contains the course materials and exercises for the **Distributed Information Systems (DIS)** course at EPFL.

## Course Overview

The DIS course covers fundamental concepts and practical applications in distributed information systems, including data processing, information retrieval, and distributed computing technologies.

## Repository Structure

```
DIS/
├── week 1/
│   ├── Prerequisites.md     # Software setup and installation guide
│   ├── DIS_intro.ipynb     # Introduction to DIS concepts
│   └── taxi_log.txt        # GPS taxi trajectory data
├── week 3/
│   ├── Probabilistic_Retrieval.ipynb  # Probabilistic retrieval models
│   └── Relevance_Feedback.ipynb       # Relevance feedback algorithms
├── week 4/
│   ├── Inverted_Files.ipynb           # Inverted index construction
│   ├── Distributed_Information_Retrieval.ipynb  # Fagin's algorithm
│   └── epfldocs.txt                   # EPFL documents dataset
├── week 5/
│   └── ca-GrQc.txt         # Collaboration network graph data
├── week 6/
│   ├── Link_Based_Indexing.ipynb     # PageRank and HITS algorithms
│   └── ca-GrQc.txt                   # Graph dataset for link analysis
├── week 9/
│   └── Recommender_Systems - Questions.ipynb  # Collaborative filtering
├── week 11/
│   └── Semantic_Web.ipynb             # Knowledge graphs and reasoning
├── week 12/
│   └── Entity_and_Information_Extraction.ipynb  # NER and relation extraction
└── week 13/
    └── Taxonomy_Induction.ipynb       # Automatic taxonomy construction
```

## Prerequisites

Before starting the exercises, make sure you have the required software installed. See [`week 1/Prerequisites.md`](week%201/Prerequisites.md) for detailed setup instructions.

### Required Software
- **Python 3.x**
- **Git** for version control
- **Anaconda** or **Miniconda** for package management
- **Jupyter Notebook** for interactive development

### Required Python Libraries
```bash
conda install -y scipy pandas numpy networkx nltk matplotlib jupyter scikit-learn
```

### Additional Libraries
```bash
# For recommender systems
conda install -c conda-forge scikit-surprise

# For NLP tasks
python -m nltk.downloader stopwords punkt
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd DIS
   ```

2. **Set up the environment:**
   ```bash
   conda create -n dis python=3.8 scipy pandas numpy networkx nltk matplotlib jupyter scikit-learn
   conda activate dis
   ```

3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Course Content

The course covers core concepts in distributed information systems through practical implementations and real-world datasets.

### Weekly Topics

- **Week 1**: Introduction to DIS concepts, data representation, and homomorphisms
- **Week 3**: Probabilistic retrieval models and relevance feedback mechanisms
- **Week 4**: Inverted file construction, distributed information retrieval (Fagin's algorithm)
- **Week 5**: Network analysis and graph algorithms
- **Week 6**: Link-based ranking algorithms (PageRank, HITS)
- **Week 9**: Recommender systems and collaborative filtering
- **Week 11**: Semantic web technologies and knowledge graphs
- **Week 12**: Named entity recognition and information extraction
- **Week 13**: Automatic taxonomy induction from text

### Key Technologies Covered

- **Information Retrieval**: Boolean models, vector space models, probabilistic models
- **Text Processing**: Tokenization, stemming, TF-IDF using NLTK
- **Graph Analysis**: PageRank, HITS, network analysis using NetworkX
- **Machine Learning**: Classification, clustering, collaborative filtering
- **MapReduce**: Distributed processing for inverted index construction
- **Semantic Technologies**: RDF, knowledge graphs, reasoning
- **NLP**: Named entity recognition, relation extraction

### Datasets Used

- **EPFL Documents** (`epfldocs.txt`): Social media posts and documents for text analysis
- **Taxi GPS Data** (`taxi_log.txt`): GPS trajectory data for spatial analysis
- **Collaboration Network** (`ca-GrQc.txt`): Academic collaboration graph from arXiv
- **Movie Ratings**: For recommender systems exercises

## Exercise Structure

Each exercise builds upon previous concepts with hands-on implementations:

1. **Theoretical Foundation**: Understanding core algorithms and models
2. **Implementation**: Building systems from scratch using Python
3. **Analysis**: Working with real datasets to validate concepts
4. **Evaluation**: Measuring system performance and effectiveness

## Technologies Used

- **Python Ecosystem**: NumPy, Pandas, Scikit-learn for data science
- **Jupyter Notebooks**: Interactive development and experimentation
- **NLTK**: Natural language processing and text analysis
- **NetworkX**: Graph analysis and network algorithms
- **Matplotlib**: Data visualization and result plotting
- **Scikit-surprise**: Recommender systems framework

## Support

For questions about the course content or technical issues, refer to the course instructors or teaching assistants at EPFL.

---

*This repository is part of the Distributed Information Systems course at École Polytechnique Fédérale de Lausanne (EPFL).*