# CNBC Trending News Summary

This repo contains code to summarize most trending news from CNBC using [OpenAI API](https://platform.openai.com/docs/overview).

## Setup

1. Clone this repository

2. Create new python3 environment with venv
    ```bash
    $ python3 -m venv env
    $ source env/bin/activate
    ```

3. Install the requirements
   ```bash
   $ pip install -r requirements.txt
   ```

4. Make a copy of the example environment variables file
   ```bash
   $ cp .env.example .env
   ```
6. Add your [OpenAI API key](https://platform.openai.com/docs/overview) and [RapidAPI](https://rapidapi.com/hub) to the newly created `.env` file

    In the CNBC homepage, it only shows 5 trending news. Hence, we need to use [RapidAPI](https://rapidapi.com/apidojo/api/cnbc/playground/apiendpoint_a089df49-b8d4-4e1e-ba8e-e52e26199d51) to get more news (E.g.: 50). It has free package with the 500 requests/month limit.

7. Run the Jupyter Notebook to open .ipynb file

   ```bash
   $ jupyter notebook
   ```

## Google Colab version
[https://colab.research.google.com/drive/1UQ6A9lIh2GfNw61x8txvudRTC5HNF3N8?usp=sharing](https://colab.research.google.com/drive/1UQ6A9lIh2GfNw61x8txvudRTC5HNF3N8?usp=sharing)

## Reference

* [OpenAI API Documents](https://platform.openai.com/docs/overview)
* [CNBC API in RapidAPI](https://beta.openai.com/examples)