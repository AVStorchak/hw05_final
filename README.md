# Yatube

Blog for publication of posts with text and images. The funcionality includes registration of new users, commenting, adding to favorites, subscribing to other users.

NOTE. This is an educational project intended for launching locally. No online deployment shall be carried out.

## Getting Started

1. Copy the repository

### Prerequisites

Python 3.

### Installing

1. Open the terminal and run the following commands:
    - pip install virtualenv
    - virtualenv venv
    - source venv/bin/activate
    - pip install -r requirements.txt

2. Create the database dependencies through running:
    - python manage.py makemigrations
    - python manage.py migrate

3. Run python manage.py createsuperuser. Follow the process to create the admin account.

4. Access the administrator page at http://127.0.0.1:1337/admin/, and create the required groups for posts.

5. The blog is ready!

## Running the tests

1. Run python manage.py test in order to perform the included tests, which cover all the main funcionality (located at the "tests" folder)

## Deployment

None

## Built With

Pyhon, Django

## Contributing

None

## Versioning

None

## Authors

* **Andrei Storchak** - *Initial work* - [AVStorchak](https://github.com/AVStorchak/)

## License

None

## Acknowledgments

* Yandex.Praktikum