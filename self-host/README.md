# N8N Self Hosting (Local)

## Windows

### Via Docker Desktop

1. Acessar Aba de Imagens e pesquisar pela imagem oficial e fazer pull
```
image: n8nio/n8n
```
2. 

### Via Node JS

1. Baixar Node.JS
<a href="nodejs.org/en/download">nodejs.org/en/download</a>

2. Windows CMD (Verificar se o Node foi instalado)
```
node --version
```
3. Instalar N8N (globalmente)
```
npm install n8n -g
```
4. Executar N8N
```
n8n
```
5. Acessar url Endpoint localhost (Porta Padrão 5678)
```
http://localhost:5678
```
6. Setup e configuração de conta N8N local (padrão)

⚠ *Necessário manter o CMD aberto enquanto o N8N estiver rodando*

## Linux

### Via Docker Compose

baixar arquivo docker-compose.yml
<a href="https://github.com/cerqueiralex/n8n/blob/main/self-host/docker-compose.yml"> https://github.com/cerqueiralex/n8n/blob/main/self-host/docker-compose.yml </a>

