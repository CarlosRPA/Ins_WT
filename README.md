```bash
sudo apt-get update && sudo apt-get dist-upgrade -y
```
LIMPEZA DE PACOTES OBSOLETOS

```bash
sudo apt-get autoremove -y && sudo apt-get autoclean && sudo apt-get clean
```

RENICIAR VPS

```bash
sudo reboot
```


FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && sudo git clone https://github.com/CarlosRPA/Ins_WT.git && sudo chmod -R 777 Ins_WT && cd Ins_WT && sudo ./install_primaria
```

ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:
```bash
cd ./Ins_WT && sudo ./install_instancia
```

