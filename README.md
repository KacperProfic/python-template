PYTHON TEMPLATE 

## Jak zacząć nowy projekt?

```bash
git clone https://github.com/KacperProfic/python-cli-template.git moj-nowy-projekt
cd moj-nowy-projekt
rm -rf .git                  # usuń historię template'a
git init && git add . && git commit -m "Initial commit"
# zmień nazwę w README, pyproject.toml itd.

python -m venv .venv
source .venv/bin/activate
python src/app/main.py


git init
git add .
git commit -m "Initial clean Python template"
git branch -M main
git remote add origin https://github.com/KacperProfic/python-cli-template.git
git push -u origin main

gh repo create nazwa-projektu --source=. --public --push