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
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/ba588211-8018-48fd-896a-9f9e0e33b384"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/d3007a12-5ebe-404b-8329-6ce1e07749ff"/> </div>
<div align="center"> <img src="https://github.com/bmsousa9/CompassUOL-Semana-01/assets/111213549/041d4bc3-2dbb-4d43-8c8d-217cd9ecdfa7"/> </div>



># Desafio 3 ![Static Badge](https://img.shields.io/badge/STATUS-Em_Desenvolvimento-FFC000)
Na VM01 - Instalar o Mariadb, na VM02 - Instalar o Wordpress, no NFS salvar os estaticos do wordpress.


Agora, vamos à <a href="https://github.com/bmsousa9/CompassUOL-Semana-02" target="_blank" rel="noopener noreferrer"> Sprint 2</a>.
