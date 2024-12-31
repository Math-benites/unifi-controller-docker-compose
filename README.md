<h1 align="center">Unifi Controller - Compose </h1>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado 
[Ubuntu 22.04 LTS ](https://releases.ubuntu.com/jammy/)

[Docker Compose version v2.3.3 igual ou superior]


[Docker Engine Version: 23.0.1 igual ou superior]


[Instale o Docker seguindo este guia](https://github.com/Math-benites/docker-install-script)



### 🎲 ( Rodando Compose )

Criando diretorios
```bash
mkdir -p /opt/app/
```

Acessando diretorio
```bash
cd /opt/app
```

 Fazendo Git do projeto
```bash
git clone https://github.com/Math-benites/unifi-controller-docker-compose.git . 
```

Rodando compose
```bash
docker compose up -d
```

O servidor Unifi Controller (https) inciará na porta:8343 - acesse <http://MYIP:8343/>




