
# ice_breaker

A repository for learning LangChain🦜🔗  by building a generative ai application.

This is a web application crawling Linkedin about a person and customizes an ice breaker with them.


![Logo](https://github.com/yulia-kr/ice_breaker/assets/100228348/3f5eecba-6515-4f05-b2fa-68d0ab99bb44)



## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`PYTHONPATH=/{YOUR_PATH_TO_PROJECT}/ice_breaker`

`OPENAI_API_KEY`

`PROXYCURL_API_KEY`

`TAVILY_API_KEY`

## Run Locally

Clone the project

Go to the project directory

```bash
  cd ice_breaker
```

Install dependencies

```bash
  pipenv install
```

Start the flask server

```bash
  pipenv run app.py
```


## Running Tests

To run tests, run the following command

```bash
  pipenv run pytest .
```


