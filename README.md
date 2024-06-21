# langgraph_demo


## Instructions to run this demo notebook
1. Create an environment
```
conda create -y --name=langgraph_demo python=3.9
conda activate langgraph_demo
pip install -r requirements.txt
```
2. Create your api keys
- Create `OPENAI_API_KEY` and `TAVILY_API_KEY` in the corresponding websites.
- Save your key into `.env` file
```
OPENAI_API_KEY=your_openai_key
TAVILY_API_KEY=your_tavily_key
```
3. You might need to pay for gpt-turbo-3.5 if you're over the api limit.