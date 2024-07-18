##REQUESITOS 

-UBUNTU 20.04 (OBRIGATORIO)
-VM COM MINIMO: 2CPU 4GB RAM
-VM COM RECOMENDADO: 4CPU 6GB RAM


## CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS ##

FRONTEND_URL: app.seudominio.com
BACKEND_URL:  api.seudominio.com

## CHECAR PROPAGAÇÃO DO DOMÍNIO ##

https://dnschecker.org/

## ATUALIZAR VPS ##

```bash
sudo apt -y update && apt -y upgrade
```
```bash
sudo apt install -y git && git clone https://github.com/BetaCrmTI/instalador.git instalador && sudo chmod -R 777 instalador  && cd instalador  && sudo ./install_betacrm
```

===================================================

login: admin@admin.com
senha: 123456