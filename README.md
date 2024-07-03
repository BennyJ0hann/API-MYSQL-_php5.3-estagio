# API
## Visão Geral
Diretorios existentes e o que contém:

projeto 5.3 - API(MYSQL): Programa feito para cadastrar pessoas no banco de dados MYSQL, pesquisar e selecionar para cadastrar personagens de Rick and Morty atravez da API: 
'https://rickandmortyapi.com/'.
E tambem fazer consultas por campos através de select mostrando todos os campos existentes no banco de dados;


## Pré-requisitos

Primeiro, baixe os pacotes da sua distribuição, no exemplo será no ubuntu 22.04

```bash
sudo apt-get update 
```

Em seguida, atualize seus pacotes

```bash
sudo apt-get upgrade
```

Instale pacotes para usar um repositório HTTPS

```bash
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```


Instale o Apache 2

```bash
sudo apt install apache2
```

- Verifique seu servidor web

```bash
sudo systemctl status apache2
```
- Inicie um servidor

```bash
sudo systemctl start apache2
```
- Crie um diretório para seu dominio

```bash
sudo mkdir /var/www/html/your_domain
```
- Use your_domain/Projeto_name/nome_do_projeto.php no navegador

Após isso, clone o projeto para um diretório

```bash
git clone git@github.com:BennyJ0hann/PHP-estagio.git
```


