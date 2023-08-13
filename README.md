# Atividade 1: Criando o ambiente para a execução de uma aplicação containerizada (former: Criando uma conta em uma núvem comercial)

Este autoestudo tem por objetivo verificar se o estudante consegue criar uma aplicação e um container para executá-la. Espera-se que os estudantes possam criar suas imagens e descrever o que foi necessário para realizar seu desenvolvimento. Espera-se ainda que os estudantes possam buscar as informações complementares para o desenvolvimento da aplicação.

## Rodando a aplicação 

Para rodar a aplicação, primeiramente devemos puxar a aplicação que está em um repositório no Docker Hub.
O container que será puxado é do seguinte perfil:

kilmatheus/curriculo-ponderada1

Para executar a aplicação, siga os seguintes passos:

1. Faça o Download da aplicação do Docker Desktop: https://www.docker.com/products/docker-desktop/
2. Inicie a aplicação e faça o cadastro até a tela inicial da aplicação.

3. Com a aplicação rodando, abra o CMD e coloque o seguinte comando:

docker push kilmatheus/curriculo-ponderada1:1.0.0

4. Após puxar, execute o seguinte comando:

docker run -p 8000:8000 b782

Sendo a assim, a aplicação vai rodar e será possível ver no navegador o meu currículo.