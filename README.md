Multi-modal Knowledge Graph Convolutional Networks for Music Recommender System 
# Emotion based Multimodal Music Recommendation System
Implements a state-of-the-art multimodal music recommendation system using the Multimodal Knowledge Graph Convolutional Network (MKGCN) architecture.

## Features
- **Multimodal Integration**: Utilizes multiple data modalities to capture rich information about songs.
- **Advanced Recommendation Algorithm**: Employs the MKGCN architecture, which combines graph convolutional networks with multimodal embeddings to generate accurate and diverse recommendations.
- **Interactive Interface**: Provides a user-friendly web interface powered by PyQt5, allowing users to input their preferences and receive personalized song recommendations in real-time.

# Sequence to run the files
1. For Multimodal-Knowledge Graph Convolutional Network 
- Download this complete project and open in Visual Studio Code
- Connect to venv3.11 (Use Command: cd path_to_your_directory then venv3.11\Scripts\activate)
- Run Configure_Data.ipynb 
- Utils.ipynb 
- EMKGCN Data Loader.ipynb
- Multimodal_aggregator
- Neighbor_Aggregator
- Modal.ipynb (Make sure here you provide your system file path for (modal_0.tsv, modal_1.tsv....)
- EMKGCN Main (Change the Model Directory Path based on your system file path)

2. Connecting with Spotify API for most updated results
- Training_Spotipy
- Spotipy.ipynb (This is will playlist for 7 specified emotions)
- PyQt5.ipynb (Do use the paths specified from your system files)
Executed!!

### Required packages
The code 1 has been tested running under Python 3.6.5, with the following packages installed (along with their dependencies):
- pytorch == 2.0.0
- numpy == 1.14.5
- sklearn == 0.24.2


