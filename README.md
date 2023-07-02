iniciar o projeto django

python -m venv venv
./venv/scripts/active
pip install django
django-admin startproject project .

Configurar o git

git config --global user.name 'seu nome'
git config --global user.email 'seuemail@email.com'
git config --global init.defaultBranch main
git init

git add .
git commit -m 'Mensagem'

git remote add origin git@github.com:Antoni-4322/agenda.git