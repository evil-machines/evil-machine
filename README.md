# Evil-Machine
A machine that knows the evil.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: What is evil about it, machine?" \
  | uvx evil-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install evil-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
evil-machine -a multilogue.txt
```
Or:
```bash
evil-machine multilogue.txt > response.txt
```
Or:
```bash
evil-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import evil_machine
```
