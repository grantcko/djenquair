# Enquair

[enquair.herokuapp.com](https://enquair.herokuapp.com/)

This is a web application built with Django that collects votes on my favorite things. The application asks users a series of questions about my favorite things, such as my favorite color, food, animal, etc. Users can select their answers from pre-defined options, submit their responses, and view other peoples answers.

## Installation

To run this application on your local machine, you'll need to have the following installed:

- Python (at least 3.11.2)
- Django (at least 4.1.7)

First, clone the repository:

`git clone git@github.com:grantcko/djenquair.git`

Install the required packages:

`pip install -r requirements.txt`

Finally, start the development server:

`python manage.py runserver`

The application should now be running at http://localhost:8000.

## Usage

When you first visit the application, you will be presented with a list of questions. Each question will have a set of pre-defined answer options to choose from. Once you have selected an answer for each question, you can submit your responses.

After submitting your responses, you will see a summary of the results, including a chart that displays the percentage of votes for each answer option.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/my-new-feature`)
3. Make your changes and commit them (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature/my-new-feature`)
5. Create a new pull request

## Credits

This application was created by Grant Hall.
Based on [Django official basics tutorial](https://docs.djangoproject.com/en/4.1/intro/)
