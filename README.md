># Sprint 1 - Linux 
<div align="center"> <img src="https://github.com/bmsousa9/images/assets/111213549/3f32401e-bd7f-41a5-b5b5-d3caa476e4bd" width="px" /> </div>



># Desafio 1 ![Static Badge](https://img.shields.io/badge/STATUS-Resolvido-2e8b57)
Realizar a instalação de um servidor Oracle Linux 8.x em uma virtual box


### Instalar o VirtualBox

O primeiro passo foi baixar uma versão do Oracle VM VirtualBox. Escolhi a versão 6.1 que apesar de ser antiga, recebeu um atualização recentemente.
```
https://www.virtualbox.org/wiki/Downloads
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/98198d88-d4bc-4088-8389-687218c1ee83"/> </div>


### Baixar o Oracle Linux 8.x

Para iniciar a instalação do Oracle Linux, inserir as credenciais no site da Oracle para fazer o login.
```
https://edelivery.oracle.com/
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/ea95f0ab-8c89-4be7-8189-71e9b225b059"/> </div>

Na tela seguinte, precisei procurar pela imagem que precisava. Inseri `Oracle Linux` e a partir daí, apareceram várias versões dessa imagem. Escolhi `Oracle Linux 8.8` e cliquei em `Continue`.
<div align="center"> <img src=""/> </div>

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
+ `ipv4.adresses 192.168.0.50/24`define o endereço IP para 192.168.0.50 com máscara de sub-rede de 24, ou seja, 255.255.255.0
+ `ipv4.gateway 192.168.0.1` define o gateway padrão como 192.168.0.1
+ `ipv4.dns "8.8.8.8 8.8.4.4"`define que servidores DNS que são os públicos do Google
+ `ipv4.method manual` define que as configurações não são automáticas por DHCP

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


Para criar uma outra VM com outro IP fixo, voltei ao VirtalBox, criei um snapshot da VM01, em seguida desliguei a VM01 e clonei essa máquina apenas alterando o nome dela para VM02.
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

Liguei novamente a VM01 no VirtualBox e fiz o ping para VM02.
```
ping @192.168.0.51
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/e822835d-b46c-49e1-8633-42709dbdaf13"/> </div>

Fiz o ping no caminho inverso, agora da VM02 para VM01.
```
ping 192.168.0.50
```
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/e822835d-b46c-49e1-8633-42709dbdaf13"/> </div>

### Configurar o NFS nas VM01 e VM02

ENTRA
```
ENTRA
```
<div align="center"> <img src=""/> </div>

># Desafio 3 ![Static Badge](https://img.shields.io/badge/STATUS-Em_Desenvolvimento-FFC000)
Na VM01 - Instalar o Mariadb, na VM02 - Instalar o Wordpress, no NFS salvar os estaticos do wordpress.

<div align="center"> <img src=""/> </div>

Agora, vamos à <a href="https://github.com/bmsousa9/CompassUOL-Semana-02" target="_blank" rel="noopener noreferrer"> Sprint 2</a>.
