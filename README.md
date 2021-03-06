# Movie-web
This is a movie-related website like [iMDB](https://www.imdb.com/) [Netflix](https://www.netflix.com/), which includes all kinds of information about films, tv shows, video games, and it also allows users to rate/review/add into watchlist what they want. The website will include a movie recommendation system depending on what you most frequently viewed. There is a trending list(TopK). This website will also provides you data visualization of tremendous amount of movies which analysis the data of movies and user data.

![GitHub last commit](https://img.shields.io/github/last-commit/weilingao/movie-website)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/weilingao/movie-website)
[![weiligao-movie--website compliant](https://img.shields.io/badge/weilingao-movie--website-blue)](https://github.com/weilingao/movie-website)

## Table of Contents
- [Install](#install)
- [Software Architecture Diagram](#software-architecture-diagram)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Contributors](#contributors)
- [Maintainer](#maintainer)
- [License](#license)
## Install
Prior to installation, you should make sure get python3 and virtual environment installed, and activate that virtual environment. If you don't know how to do that, you can reference [this](https://github.com/weilingao/Django_practice/blob/master/README.md)
```bash
git clone https://github.com/weilingao/movie-website.git
python manage.py runserver
```
Then you can start the server at http://127.0.0.1:8000/

Note: steps of making model changes
- Change the model
- Run ```python manage.py makemigrations``` to create migrations for those changes
- Run ```python manage.py migrate``` to apply those changes to the database

## Software Architecture Diagram
- model: data representation, authentication & permissions
- serializer: serialize data as json format - ```ModelSerializer```
- view: api, GET/POST/PUT/DELETE; movie_list/movie_detail; function-based/class-based view
- url: url config working with view
## Testing
## Deployment
## Change Log
### v1.0 (2020/05/18 23:30)
- Initialize the whole project
- Integrate React with Django

## Contributors

## Maintainer
@ [Weilin Gao](https://github.com/weilingao) from University of Southern California
## License
USC © Weilin Gao