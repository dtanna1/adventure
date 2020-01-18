# data-science-projects

# TMDB Box office prediction
- The goal is to predict the revenue of a movie using information about the cast, crew, budget, production company, genre etc..
- The dataset is taken from Kaggle - https://www.kaggle.com/c/tmdb-box-office-prediction
- 80% features are in text form, with JSON like format 
  For example: Cast column for 1 record has a value like this :
                [{'cast_id': 4, 'character': 'Lou', 'credit_id': '52fe4ee7c3a36847f82afae7', 'gender': 2, 'id': 52997, 
                'name': 'Rob Corddry', 'order': 0, 'profile_path': '/k2zJL0V1nEZuFT08xUdOd3ucfXz.jpg'}, 
                {'cast_id': 5, 'character': 'Nick', 'credit_id': '52fe4ee7c3a36847f82afaeb', 'gender': 2, 'id': 64342, 
                'name': 'Craig Robinson', 'order': 1, 'profile_path': '/tVaRMkJXOEVhYxtnnFuhqW0Rjzz.jpg'}]
- Feature engineering is done for significant features with less than 30% null values



#
