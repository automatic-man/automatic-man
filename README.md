# Automatic-Man
Automatic Man.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What would you do, Automatic-Man?" \
  | uvx automatic-man \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install automatic-man
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
automatic-man -a multilogue.txt
```
Or:
```bash
automatic-man multilogue.txt > response.txt
```
Or:
```bash
automatic-man -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import automatic_man
```
