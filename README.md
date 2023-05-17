

# Getting started

```bash
echo "export PATH=$PATH:$HOME/.local/bin" >> ~/.bashrc
pip install --user pipenv
pipenv install     # For å installere dependencies fra Pipfile

pipenv run ansible-playbook infra.yml
```
