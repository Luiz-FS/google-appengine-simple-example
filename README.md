# Aplicação simples usando google appengine
Tutorial para criar uma simples aplicação web usando google appengine

## Configurando o ambiente de desenvolvimento

* Entre no site [https://console.cloud.google.com](https://console.cloud.google.com), cadastre-se e siga o tutorial do próprio site para criar um novo projeto.
* Faça o download do sdk apropriado para o seu sistema neste link [https://cloud.google.com/sdk/docs](https://cloud.google.com/sdk/docs)
* Abra o terminal e execute os seguintes comandos:
```shell
cd [diretório onde o sdk foi salvo]
tar -zvxf [nome do .tar.gz baixado]
cd google-cloud-sdk…
mv google-cloud-sdk ~/
cd
./google-cloud-sdk/install.sh (siga as dicas que o instalador dará)
bash
gcloud init (Siga as dicas que serão dadas pelo inicializador)  
```
