# Arquitetura de redes
## Internet (Inter = entre | net = redes)

É classificada como uma GAN (Global Area Network)

Cada rede que faz parte da infra é chamada de sistema autônomo (SA ou AS)

Uma rede tem redundância, caso algum caminho esteja indisponível, é possível ir por outro caminho

### Redes Públicas

Qualquer pessoa tem acesso

VPNs são utilizadas via rede pública

### Redes Privadas

Acesso restrito

### Roteamento

O ato da internet correr de rede em rede

### VoIP

Voz sobre IP, telefonia via rede

### Spiders e Crawlers (Aranhas e rastejadores)

Varrem a web para indexar e localizar cabos

### Internet é diferente de web

Web é um serviço conexão de páginas em hypertexto (usadas em navegador)

## Intranet e Extranet

### Intranet

Rede privada com funcionamento similar ao da internet.
Não está conectada necessáriamente na internet.
Geralmente utilizadas internamente em empresas

### Extranet

Acesso remoto a uma rede privada

Na acessar a intranet nós precisamos estar fisicamente na empresa, já com a extranet isso é possível.

#### Opções

Acessar por login e senha via página pública

VPN - Virtual Private Network
Conecta a máquina na empresa via conexão criptografada.


## DeepWeb e DarkWeb

### DeepWeb

Parte da Web que não indexada por mecanismos de busca
(Google não encontra caso pesquise).

Para acessar os sites, você precisa saber o endereço do site.

Os sites podem não ser encontrados por falta de tags por ser novo ou por conter conteúdos ilegais ou impróprios

Para indexar, basta ir nas configurações dos buscadores e adicionar a URL do site e suas palavras chaves.

É possível configurar as tags de páginas para que elas apareçam ou não nos mecanismos de busca.

Para denunciar, basta acionar o ministério público.

#### Robots.txt

Arquivo onde é configurado quais páginas serão ou não indexados pelos mecanismos de busca.

### DarkWeb 🏴‍☠️

Conteúdo ilegal

Parte da DeepWeb que necessita de mecanismos especiais e sistemas próprios de anonimato e criptografia para acesso.

FBI E PF possuem métodos para descobrir os infratores

## Computação centralizada e serviço de terminal

Remete a um Mainframe (PC de grande porte) que processa as informações principais, e terminais burros, que apenas visualizam e enviam as informações para o mainframe.

Serviço de terminal é quando você envia e recebe informações de um mainframe via terminal, a conexão pode ser feita via Telnet ou SSH

### Telnet
Serviço de terminal - Não tem criptografia

### SSH
Serviço de terminal - Tem criptografia

## Computação distribuída

Diferente da centralizada, os dispositivos conseguem fazer o próprio processamento.

### Cliente-Servidor

#### Classificação de Hardware

Máquina Cliente - pc, note, celular

Máquina Servidora - Hardware mais parrudo e preparado para manter processos e serviços funcionando.

#### Classificação de Software

Se resume a aplicações cliente e servidor

##### Aplicação servidora Web
Ex: Apache HTTP, nginx, lls, Banco de dados

##### Aplicação cliente Web 
ex: Chrome, firefox, Edge

##### Tipos de servidores

Arquivos, Banco de dados, Impressão

#### Classificação de rede local (Cliente-Servidor)

Pelo login e senha, o usuário pode acessar arquivos, sites, impressoras de acordo com a permissão do administrador.

Rede de autenticação e serviço de diretório.

##### Serviço de diretório

Indica as permissões de acesso a rede.

### Classificação de Rede Ponta a ponta (P2P)

Tipo de rede mais usual no mercado - SOHO (Small Office / Home Office)

##### SOHO

É possível transformar sua própria máquina em um pequeno servidor para compartilhar arquivos, sem a necessidade de uma instalação complexa de servidores.

Redes P2P não tem servidor de autenticação nem serviço de diretório, senhas são configuradas individualmente nas máquinas.

##### Ponto a Ponto

Redes de compartilhamento de arquivo na internet.
Ex: Torrent, eMule

Compartilhamento de arquivos espalhados pela internet sem burocracia

##### Diferença entre SOHO e Ponto a ponto

A rede ponto a ponto, a partir do momento em que você baixa um bloco de arquivo, sua máquina começa a compartilhar este como se fosse um servidor, a rede SOHO é uma rede doméstica sem monitoramento para compartilhamento entre os usuários

### Computação em núvem

Infra de hardware e software de rede onde não importa onde está a máquina física.

#### Nuvem privada

Serviços de infra mantidos em rede privada, pertence a empresas e fica nas dependências da empresa.

#### Nuvem Pública

Serviços de infra são mantidos por empresa externa.

#### Tipos de computação em núvem

##### SaaS (Software as a service)

Ao invés de instalar um software na máquina, você acessa ele ou armazenamento na núvem.

Exemplos: Office 365, OneDrive, Google Drive, iCloud

##### PaaS (Platform as a service)

Núvem para desenvolvedores de software, ao invés de ter uma plataforma para desenvolver na máquina, é possível acessar na núvem.

Exemplos: Windows Azure, Google App Engine.

##### IaaS (Infrastructure as a Service)

Concede toda uma infraestrutura de um datacenter pela núvem.

Exemplos: Microsoft Azure, Google Cloud, AWS.

## Computação cooperativa (paralelismo)

Ao invés de utilizar um servidor parrudo, utiliza várias unidades de processamento.

### Computação em Cluster

Monta vários computadores, conecta eles entre si com um software para processar dados.

Estão no mesmo local

### Computação em grade

Parecido com cluster, porém as máquinas estão em vários lugares.

Exemplos: Folding@Home (Busca cura para doenças), 
Seti@Home (Busca vida fora da terra).

Instala o cliente no desk, e quando ele estiver ocioso, ele baixa e processa blocos de dados e envia os dados ao servidor


