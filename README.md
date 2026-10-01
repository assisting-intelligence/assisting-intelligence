# Assisting-Intelligence
A Machine that thinks.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Are language models seeking the Truth, machine?" \
  | uvx assisting-intelligence \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install assisting-intelligence
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
assisting-intelligence -a multilogue.txt
```
Or:
```bash
assisting-intelligence multilogue.txt > response.txt
```
Or:
```bash
assisting-intelligence -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import assisting_intelligence
```
