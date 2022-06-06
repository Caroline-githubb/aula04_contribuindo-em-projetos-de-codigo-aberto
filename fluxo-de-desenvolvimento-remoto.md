# 3. Fluxo de desenvolvimento remoto


## 3.1. Criar uma cópia do repositório localmente
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

## 3.2. Definir qual o endereço do repositório remoto receberá o código-fonte do repositório local
git add .\
git commit -m "first commit"\
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY 

## 3.3. Enviar o código-fonte do repositório local para o repositório remoto
git branch -M main\
git push -u origin main\
git push 

## 3.4. Verificar e baixar ajustes no código-fonte do repositório remoto para o repositório local
git pull

