Iniciar o projeto Django
...

python3 -m venv venv
. venv/bin/activate
pip install django
django-admin startproject project .
python3 manage.py startapp contact
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
# Entrar no github, criar novo repositorio e copiar a chave HTTPS
git remote rm origin
git remote addorigin CHAVE-HTTPS
ssh-keygen -f ~/.ssh/sergioshoji_rsa -t rsa -b 4096
cat ~/.ssh/sergioshoji_rsa.pub
# Copiar a chave enorme gerada.
# Entrar no github, settings, ssh-keys, gerar nova chave ssh-key, colar a chave enorme e criar chave SSH.
No github copiar a CHAVE-SSH
git remote rm origin
git remote add origin CHAVE-SSH
git push origin main -u


// isto foi adicionado pelo windows