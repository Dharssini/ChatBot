This is done in response to the task given by BusinessOnBot https://www.craft.do/s/XDO8u0QDq0a5az

# A math chatbot
A spacy-powered, wikipedia-scraping Math Chatbot for Telegram

### Audience
High school and Senior high school students.

### Topic Inclusions
Basic arithmetic, Algebra, Geometry and Trigonometry.

### Features

* **Search**: Looks up mathematicians and math concepts
* **Compute**: Calculates arithmetic and trigonometric problems
* **Play**: Tests your skills by asking you math problems

### Tools
* Python
* Spacy
* Wikipedia
* BeautifulSoup
* Requests
* Telegram
* Jupyter Notebook

### Recommendations
* Saving of information to a database for multiple user sessions
* Search 
  * Include additional keywords for search
  * Make bot more conversational
* Compute
  * Integrate additional mathematical functions for increased capability (Calculus, Matrix computations, Algebraic Functions, Finance, etc.)
  * Support math word problems
* Review
  * Include concept and word problems 
* Include a function that automatically exits the chatbot after it exceed a specific idle time.


## How to run 🤖

You can easily run your own instance of the bot.

You can run on any OS (windows/mac/linux). For better reliability, you may deploy to a VPS like Digital Ocean Droplet. You can even run on Android, using the Termux app.

Open your terminal and follow the instructions to run the bot.

> **Note:** Use python 3.8
- Make sure you have `git`, `python` and `pip`.

    ```bash
    # the following commands should not produce error
    git --version
    python --version # 3.8 is recommended
    pip --version
    ```

    > **Note:** In some systems `python` version 3 is availaible as `python3`
- First of all, clone the repository and move into the `run-py-bot` directory.

    ```shell
    git clone https://github.com/aahnik/run-py-bot.git && cd run-py-bot
    ```

- Create a python virtual enviroment and activate it.

    ```bash
    python -m venv .venv # create
    source .venv/bin/activate # activate (unix)
    # the command to activate virtual environment is different for Windows, google search
    ```

- Install the requirements.

    ```bash
    pip install -r requirements.txt
    ```

- Set `API_TOKEN` environment variable. Write the following into a file named `.env`.

    ```bash
    API_TOKEN=1234fsjksjfls23r4
    # use your own real token
    ```

- Run the `start.py`, and you are good to go.

    ```shell
    python start.py
    ```
