# 🦜🔗  LangChain & ChatGPT


This is a repository for our workshop. You'll find the slides (here)[https://slides.com/maxtharr/langchain-intro].

A lot of the code and some of the slides are from Johanns presentation at CodeTalks: [https://slides.com/johann-peterhartmann/autonome-agenten/].


# Setup

## Step 1: get the source, luke! 

The workshop uses git and docker to make it easier to use on all platforms. 
If You don't use docker for religious reasons you can use a local python virtenv / conda configuration instead. 

```bash
git clone https://github.com/mayflower/codetalks23
cd codetalks23
cp .env.dist .env
```
## Step 2: Get an OpenAI API key

Please ignore this section if you already use openai, and just insert one of your existing keys to the .env file.

Create an account at [platform.openai.com](https://platform.openai.com/signup). Use your e-mail-adress or an existing google or microsoft account. 

Create a new API key at [platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys) and insert it to the .env file.

## Step 3: Get a SerpApi-Key to search the internet

Create an account at [SerpApi](https://serpapi.com/). 
Get the key here: [serpapi.com/manage-api-key](https://serpapi.com/manage-api-key)
Add it to your .env file.


## Step 4: Use docker to start working
```bash
docker run -it --rm -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/minimal-notebook:latest    
# Go! 

The docker output should show you a url that you are able to open.

### Interested in langchain? 

You can get the free german translation of Mark Watsons Book at [hub.mayflower.de/langchain-buch](http://hub.mayflower.de/langchain-buch).

