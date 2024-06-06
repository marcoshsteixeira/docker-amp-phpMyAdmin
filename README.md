Esse é um exemplo de docker com PHP, MySql e Apache, ela executa comandos como npm install e composer install de forma automática se os arquivos package.json e/ou composer.json existirem na raiz do projeto. Ele tbm é capaz de executar comando SQL ao iniciar a docker, desde que estejam escritos no arquivo.sql da pasta mysqlconf. Ela também cria de forma automática a pasta com os bancos de dados e a pasta html que é raiz do projeto PHP. Nessa docker foi incluso o phpMyAdmin para casos onde as pessoas não podem usar nenhum tipo de IDE para banco de dados.

# Docker e Docker Compose

```bash
# Criar e levantar os containers
docker-compose up -d

# Parar e remover containers da máquina
docker-compose down
```

# Acesso página pelo navegador
```txt
http://localhost
```

# Acesso ao MySql

**Hostname**
```txt
127.0.0.1
```
**User**
```txt
root
```
**Password**
```txt
root
```

## Acesso ao PhpMyAdmin
```txt
Para ter acesso ao PhpMyAdmin vá em http://localhost:8080.
```