># Sprint 1 - Linux 
<div align="center"> <img src="https://github.com/bmsousa9/images/assets/111213549/3f32401e-bd7f-41a5-b5b5-d3caa476e4bd" width="px" /> </div>



># Desafio 1 ![Static Badge](https://img.shields.io/badge/STATUS-Resolvido-2e8b57)
Realizar a instalação de um servidor Oracle Linux 8.x em uma virtual box


### Instalar o VirtualBox

O primeiro passo foi baixar uma versão do Oracle VM VirtualBox. Escolhi a versão 6.1 que apesar de ser antiga, recebeu uma atualização recentemente.
```
https://www.virtualbox.org/wiki/Downloads
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/98198d88-d4bc-4088-8389-687218c1ee83"/> </div>


### Baixar o Oracle Linux 8.x

Para iniciar a instalação do Oracle Linux, inseri as credenciais no site da Oracle para fazer o login.
```
https://edelivery.oracle.com/
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/ea95f0ab-8c89-4be7-8189-71e9b225b059"/> </div>

Na tela seguinte, precisei procurar pela imagem que precisava. Inseri `Oracle Linux` e a partir daí, apareceram várias versões dessa imagem. Escolhi `Oracle Linux 8.8` e cliquei em `Continue`.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/060848c2-a3dd-4ce7-9bdd-0a9d923134ef"/> </div>

Logo em seguida, selecionei a versão na caixa de diálogo e escolhi a versão de download para meu sistema `x86 64 bit` e cliquei em `Continue`. A partir daí apareceram outras telas para aceitar as políticas e concordei com tudo.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/7240be14-f653-4398-8517-b05ba5ff79bd"/> </div>

Selecionei a versão `Oracle Linux Release Update 8 for x86 (64bit)`, cliquei em `Download` e aguardei a conclusão do download.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/c6578e58-b13e-4e34-9ef3-80eefac28f0f"/> </div>


### Instalar o Oracle Linux 8.x

O passo seguinte foi a criação de uma VM no VirtualBox. Abri o VirtualBox e cliquei no ícone de `Novo`.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/cb3535a5-d06c-49d8-9c51-03bfadac9a89"/> </div>

Nessa tela, digitei o nome da VM como `Oracle Linux 8.8`, troquei para tipo `Linux` e versão `Oracle (64 bits)`. Nas telas seguintes, é necessário configurar a alocação de memória, o espaço físico e tipo de disco rígido.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/450bed14-1d52-4458-a9b2-6467133a5103"/> </div>

Depois disso, selecionei o item que foi criado a esquerda e acessei `Configurações` ao lado de `Novo`.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/a8af2442-6a3d-4c20-b05d-e19bc2c30d50"/> </div>

O passo seguinte foi selecionar `Armazenamento` e selecionar a imagem do Oracle Linux 8.8, baixada anteriormente.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/cafac35f-071c-411b-944f-7afd01d87716"/> </div>

Com tudo isso definido, finalmente chegou a hora que eu iniciei a instalação do Oracle Linux 8.8 dando um duplo clique na VM. A partir daí apareceu a tela de instalação do SO.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/a884d1fb-7c6e-475d-b7e6-8607fdfd5262"/> </div>

Apertei a tecla `Enter` e logo em seguida instalação se iniciou e ao finalizar, apareceu uma tela de configuração.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/85c0a415-e77a-42b1-945b-d356f7e85651"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/265fc9ef-646f-4651-b0af-5c9725061894"/> </div>

Fui efetuando a configuração das seguintes etapas:
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/de5e392f-dae8-4690-8a63-31d74efa1640"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/60caf115-7508-4e95-9c2c-f0cb9f0dfc5d"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/078658a3-2c55-4351-9ff3-1d7a734fe4f4"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/dcb1eff8-0382-4ba6-9c9f-755622eab33e"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/1646b22d-95f1-4d3d-a293-5bc70eb8f149"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/53b8a297-3d93-4ab2-acf0-889c1888a490"/> </div>

Fiz uma verificação das configurações de instalação, e com todas as configurações devidamentes setadas, cliquei em `Begin Installation` e assim que concluiu, fui em `Reboot System` para reiniciar o sistema.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/08769363-1588-4460-8542-4035dc060018"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/3f5fd7f0-88bf-477a-8927-fbfba51006c1"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/d3997281-a3c3-46b2-8dff-6c6bf560cc57"/> </div>

Logo após a reinicialização, surgiu uma tela para configuração de usuário e em seguida, cliquei em `Finish Installation` para finalizar a instalação.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/e1527a8b-80ae-40f4-9eb5-e6978f44de77"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/78832e0e-6449-4844-a1e9-83c4ffcc204a"/> </div>

O próximo passo é fazer login com o usuário criado, que no meu caso foi Bruno Sousa. Em seguida, pequenos ajustes foram necessários, como a possível adição de contas (não o fiz), para utilizar o Oracle Linux 8.8.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/ca062d84-7400-4921-b5ce-9710fcec2cda"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/4dd64d38-9b82-4a51-85e8-c4dcbf166fa2"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/2d5cd44b-58ac-42f6-8ed8-bed3bb408bd5"/> </div>

A partir desse ponto, o sistema já está instalado e pronto para ser utilizado. O próximo passo é o Desafio 2.



># Desafio 2 ![Static Badge](https://img.shields.io/badge/STATUS-Resolvido-2e8b57)
Reinstalar a VM sem interface gráfica, instalar uma nova VM, configurar IP fixo nos dois servidores, criar um NFS do servidor 1 para o servidor 2. 



### Instalar o Oracle Linux 8.8, sem interface gráfica

Refiz todos os passos anteriores para criar uma nova VM, porém dessa vez sem interface gráfica. 
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/f3a3684b-e0de-417f-b6df-6be26cd78181"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/ba588211-8018-48fd-896a-9f9e0e33b384"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/d3007a12-5ebe-404b-8329-6ce1e07749ff"/> </div>

Também alterei na aba `Configuração`, em `Rede`, fiz a alteração de `NAT`para `Placa em modo Bridge` e cliquei em `OK`.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/32ae39f4-f56a-421c-b710-397a21641879"/> </div>

### Configurar o IP fixo na Máquina Virtual

Para iniciar a configuração do IP fixo, é importante digitar `root` em localhost e em seguida digitar a senha configurada na instalação do Oracle Linux 8.8.
```
root
[senha configurada na instalação]
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/b9e1ca16-6104-4416-bba2-770b650a9390"/> </div>

Para alterar algumas configurações, utilizei `nmcli` que é uma ferramenta para controlar o NetworkManager, que é usado para gerenciar conexões de rede. Com isso consegui alterar  a interface de rede `enp0s3`.
```
nmcli con mod enp0s3 ipv4.adresses 192.168.0.50/24
nmcli con mod enp0s3 ipv4.gateway 192.168.0.1
nmcli con mod enp0s3 ipv4.dns "8.8.8.8 8.8.4.4"
nmcli con mod enp0s3 ipv4.method manual
```
+ `ipv4.adresses 192.168.0.50/24`define o endereço IP para 192.168.0.50 com máscara de sub-rede de 24, ou seja, 255.255.255.0 ;
+ `ipv4.gateway 192.168.0.1` define o gateway padrão como 192.168.0.1 ;
+ `ipv4.dns "8.8.8.8 8.8.4.4"`define que servidores DNS que são os públicos do Google;
+ `ipv4.method manual` define que as configurações não são automáticas por DHCP.

<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/36a76dbf-8711-46ef-b564-6cbcd02326af"/> </div>

Ao fazer essas configurações, estabeleci conexão de rede para interface `enp0s3` .
```
nmcli con up enp0s3
```
Com isso, abri o editor `nano` para estabelecer uma última alteração.
```
nano /etc/sysconfig/network-scripts/ifcfg-enp0s3
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/af2187b7-0261-4843-9fcc-0902beb8187f"/> </div>

Com a alteração de parâmetro, indica que o endereço IP é definido manualmente e permanecerá inalterado a menos que seja manualmente modificado, ou seja, é empregado nos arquivos de configuração de rede do Linux para estabelecer a forma como um endereço IP é obtido para uma interface de rede, que nesse caso é manual e não DHCP.
```
BOOTPROTO=static
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/f06b0edf-7434-4453-a883-62fafd0da19d"/> </div>

Agora ficou pronta a configuração de IP fixo na VM01 e reiniciei o `NetworkManager` para que as modificações sejam aplicadas e, logo em seguida, usei um `ifconfig` para visualizar o que havia acontecido.
```
systemctl restart NetworkManager
ifconfig
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/b7680ff9-64fb-4e53-8ecc-e40d2934c7ea"/> </div>


### Configurar o IP fixo na outra Máquina Virtual


Para criar uma outra VM com outro IP fixo, voltei ao VirtualBox, criei um snapshot da VM01, em seguida desliguei a VM01 e clonei essa máquina apenas alterando o nome dela para VM02.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/add845fa-5ea7-47f5-8708-99eff96567b8"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/68a21a0a-d146-4c50-bd71-cd1e5ae13e0a"/> </div>

Já na VM02, tratei de alterar o IP fixo para `192.168.0.51`.
```
nmcli con mod enp0s3 ipv4.addresses 192.168.0.51/24
nmcli con up enp0s3
systemctl restart NetworkManager
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/983f42f1-9739-4111-9add-799032014d3a"/> </div>

Assim que conclui, fiz uma verificação com `ifconfig` para saber se estava tudo certo.
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/348b9ec3-c6fd-4ddf-b705-5cc18f3acc78"/> </div>

Liguei novamente a VM01 no VirtualBox e fiz o `ping` para VM02.
```
ping @192.168.0.51
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/e822835d-b46c-49e1-8633-42709dbdaf13"/> </div>

Fiz o `ping` no caminho inverso, agora da VM02 para VM01.
```
ping 192.168.0.50
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/be2714a4-a654-49db-bacc-fd043ebf29c3"/> </div>

### Configurar o NFS na VM01

Instalei o pacote de utilitários NFS que contém vários scripts necessários para montar, desmontar, gerenciar e analisar sistemas de arquivos NFS.
```
dnf install nfs-utils -y 
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/2445c1ac-ff0c-4a92-8712-f5ee9d43797e"/> </div>

Criei uma pasta que será compartilhada com a VM02 com comando `mkdir`.
```
mkdir /nfs-share
```
Em seguida, aloquei um espaço de 20 MB nesse diretório para verificar se é possível ter acesso a esse arquivo pela VM02.
```
fallocate -l 20MB /nfs-share/file1
```
Depois disso, `chmod` para alterar as permissões do arquivo, com `-R` para que esse diretório, todos os arquivos e diretórios filhos sejam alterados por `777` que o servidor e cliente podem ler, escrever e executar os arquivos no local `/nfs-share`, ou seja, que define as permissões de toda pasta para ler, gravar e executar para todos.
```
chmod -R 777 /nfs-share
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/62c0ead0-a6a2-40e9-97d0-4414aee854a3"/> </div>

A partir daí, já é possível definir que a pasta que foi criada poderá ser vista pelo cliente NFS através do IP da VM02.
```
echo "/nfs-share 192.168.0.51(rw)" | tee -a /etc/exports > /dev/null
```
+ `echo` define que será escrito no terminal;
+ `/nfs-share` define a pasta que será vista pelo cliente NFS;
+ `192.168.0.51` esse é o IP do cliente NFS, que nessa situação é ds VM02;
+ `(rw)` define que será de escrita e leitura para o IP definido;
+ `|` está recebendo todos os valores escritos até aqui e passa para o seguinte;
+ `tee` faz com que ele pegue as instruções;
+ `-a` essa opção insere, mas não subatitui os valores;
+ `/etc/exports` é o arquivo que se especifica quais diretórios serão compartilhados com os clientes NFS;
+ `/dev/null` mostra que não será escrito no terminal.

Foi preciso usar os comandos a seguir para permitir que o firewall dará a passagem de tráfego de rede para o serviço NFS. Logo em seguida, foi reiniciado e listado.
```
firewall-cmd --permanent --zone=public --add-service=nfs
firewall-cmd --reload
firewall-cmd --list-all
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/5d71d84d-5d19-4305-a531-00e70ca7ccac"/> </div>


Depois de tudo configurado na VM01, pude reiniciar o serviço NFS e manter que ele comece sempre na reinicialização. 
```
systemctl enable --now nfs-server
```
E assim exibir a lista de sistemas de arquivos exportados por um servidor NFS para verificar quais pastas estão sendo compartilhadas pelo serviço.
```
showmount -e
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/527dafdc-3598-45cc-857b-de2126d1bd9f"/> </div>



### Configurar o NFS na VM02


A primeira coisa que fiz foi atualizar o pacote de serviço NFS na VM02.
```
dnf install -y nfs-utils
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/e4624631-7555-4674-ab29-2d200f299b28"/> </div>

Logo em seguida criei uma pasta que será montada na VM02 com comando `mkdir`.
```
mkdir /nfs-mount
```
<div align="center"> <img src="(https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/1d2368f3-4e27-4c5f-8002-2a3b9ebd2fd5"/> </div>


Foi justamente nesse ponto que se tornou possível definir que a pasta que foi criada poderá ser montada pelo cliente NFS através servidor do IP da VM01.
```
echo "192.168.0.50:/nfs-share  /nfs-mount  nfs  rw  0 0" | sudo tee -a /etc/fstab > /dev/null
```
```
mount -a
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/850a1c4e-72f5-4f89-9b1e-236a2c4b2490"/> </div>

Com isso, foi configurado o serviço NFS, resistindo a reinicialização nas VM01 e VM02. Próximo passo é o Desafio 3.



># Desafio 3 ![Static Badge](https://img.shields.io/badge/STATUS-Em_Desenvolvimento-FFC000)
Na VM01 - Instalar o Mariadb, na VM02 - Instalar o Wordpress, no NFS salvar os estaticos do wordpress.



### Instalação e configuração do MariaDB


ENTRA
```
dnf install mariadb-server -y
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/fb62f876-7fc6-4890-bfc8-d0f9a695cd70"/> </div>

ENTRA
```
systemctl start mariadb
systemctl enable mariadb
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/1bdcd051-40e9-460a-b353-25910b7df50"/> </div>

ENTRA
```
mysql_secure_installation
```
<div align="center"> <img src=""/> </div>

ENTRA
```
mysql -u root -p
```
<div align="center"> <img src=""/> </div>

ENTRA
```
CREATE DATABASE wordpress;
```
<div align="center"> <img src=""/> </div>

ENTRA
```
CREATE USER 'wordpress'@'localhost' IDENTIFIED BY 'wordpress_password';
```
<div align="center"> <img src=""/> </div>

ENTRA
```
GRANT ALL PRIVILEGES ON wordpress.* TO 'wordpress'@ 'localhost';
FLUSH PRIVILEGES;
```
<div align="center"> <img src=""/> </div>


### Configuração do NFS na VM01


ENTRA
```
nano /etc/exports
```
<div align="center"> <img src=""/> </div>

ENTRA
```
/var/lib/mysql 192.168.0.51(rw,sync,no_root_squash)
```
<div align="center"> <img src=""/> </div>

ENTRA
```
systemctl restart nfs-server
showmount -e
```
<div align="center"> <img src=""/> </div>



### Configuração do NFS na VM02

Como eu já havia feito o compartilhamento do servidor NFS, foi importante editar o arquivo `/etc/fstab` com editor `nano`. Para isso, eu apaguei a linha `192.168.0.50:/nfs-share  /nfs-mount  nfs  rw  0 0`. Mas antes disso, desmontei `umount` a pasta em questão e em seguida a removi com `rmdir`.

```
umount /nfs-mount
```
```
rmdir /nfs-mount
```
```
nano /etc/fstab
```

O passo seguinte foi a criação da pasta onde foi montado o banco de dados da VM01.
```
mkdir /mnt/mariadb-shared
```

Com a pasta devidamente criada, tinha chegado a hora de estabelecer o cliente NFS na VM02.
```
echo "192.168.0.50:/var/lib/mysql  /mnt/mariadb-shared  nfs  rw  0 0" | sudo tee -a /etc/fstab > /dev/null
```
```
mount -a
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/a6794769-2ca4-4ed9-ac63-7c15781a3f76"/> </div>

Como curiosidade entrei no arquivo `/etc/fstab` como o `nano` mais uma vez, apenas para constatar `192.168.0.50:/var/lib/mysql  /mnt/mariadb-shared  nfs  rw  0 0`.
```
nano /etc/fstab
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/15a9c5f7-3a13-4989-89cc-ee890890795c"/> </div>


### Instalação e configuração do Wordpress


ENTRA
```
dnf install php php-{myqlnd,cli,xml,pdo,gd,xml,mbstring,json} -y
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/2000b13a-ae5a-4a34-8cab-cfc4f229e318"/> </div>

ENTRA
```
dnf install dnf-utils httpd -y
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/2b7e2ef1-13bc-4355-8c20-b972517c20d9"/> </div>

ENTRA
```
systemctl start httpd
systemctl enable httpd
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/9a203f00-dfe2-45cc-90c7-2ffba36ddd68"/> </div>

ENTRA
```
cd /var/www/html
wget https://wordpress.org/latest.tar.gz
tar -xvf latest.tar.gz
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/076bc2af-9d87-41bc-a29f-e5a6b52e5d67"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/b551d66b-4c53-4834-96d3-f549223dc447"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/d30cec04-aa10-4740-9f06-2716b29ae078"/> </div>

ENTRA
```
firewall-cmd --permanent --add-service=http
firewall-cmd --permanent --add-service=https
firewall-cmd --reload
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/78710d95-bc89-4d88-ac3e-d17d26eed85a"/> </div>

ENTRA

`http://192.168.0.51/wordpress`

<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-02/assets/111213549/15178c7b-7c51-444f-baa3-affad1416bfd"/> </div>

Agora, vamos à <a href="https://github.com/bmsousa9/CompassUOL-Semana-02" target="_blank" rel="noopener noreferrer"> Sprint 2</a>.
