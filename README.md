# EPM Recommendation System

This repository is an ongoing project focused on building a recommendation system. The system currently implements content-based filtering, collaborative filtering, and deep learning-based approaches, and reinforcement learning in the future. The project aims to provide accurate and personalized recommendations based on user preferences and behavior. It leverages content attributes and user profiles to generate recommendations. Additionally, it plans to analyze user interactions, such as ratings and purchases, to identify patterns and enhance the recommendation process.

To improve recommendation accuracy, the project will explore hybrid filtering techniques that combine content-based and collaborative filtering methods. Furthermore, deep learning-based approaches will be investigated to capture complex user-item relationships and deliver highly personalized recommendations. The project also aims to leverage reinforcement learning algorithms to continually optimize the recommendation system based on user feedback.

## Instalation
1. Create environment in your project.
2. Install requirements.txt
```bash
pip3 install -r requirements.txt
```

## Usage
1. Run RecBole script, you can change the model, config, and dataset.
```python
python run_recbole.py --model=NeuMF --dataset=ml-1m --config_files=config/neumf.yaml
```