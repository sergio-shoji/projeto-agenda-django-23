Iniciar o projeto Django
...

python3 -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
...

Configure o git
...

git config --global user.name 'sergioshoji'
git config --global user.email 'sskominami2@gmail.com'
git config --global init.defaultBranch main
# Configure o gitignore
git init
git add .
git commit -m 'Mensagem'
git remote add origin CHAVE-SSH
