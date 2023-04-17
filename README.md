# Jokes generation with OpenAI API

Using OpenAI API to generate jokes from a description. It uses the [Flask](https://flask.palletsprojects.com/en/2.0.x/) web framework. Check out the tutorial or follow the instructions below to get set up.

<img width="863" alt="Screenshot 2023-04-16 at 11 38 06 PM" src="https://user-images.githubusercontent.com/7539968/232404265-a5a1eb5e-309d-4b42-8714-3c17465030ec.png">

Topic: "cats with hats"

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd openai-jokes-app
   ```

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements and upgrade openai

   ```bash
   $ pip install -r requirements.txt
   ```

6. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

7. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file

8. Run the app

   ```bash
   $ flask run -h localhost -p 5001
   ```

You should now be able to access the app at [http://localhost:5001](http://localhost:5001)!
