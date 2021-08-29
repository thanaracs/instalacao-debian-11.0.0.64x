# instalacao-debian-11.0.0.64x
### Tutorial de instalação do sistema operacional Debian no Virtual Box

ONDE ENCONTRAR
- Pesquisei Debian 11 download
- Primeiro site (oficial da debian) https://www.debian.org/CD/http-ftp/#stable
- Opção: Imagens oficiais de CD/DVD da versão "estável (stable)".
- Versão CD e versão DVD. A versão CD é para quem tem acesso à internet no computador no momento da instalação, os downloads são feitos automaticamente quando online. a versão DVD para quando feita a instalação quando não se tem acesso à internet.
- Selecionei a opção amd64 (Que serve para processadores de 64bit, sendo ele ADM ou INTEL).
- A opção me leva ao link: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/
- seleciono a opção: debian-11.0.0-amd64-netinst.iso e o donwload é iniciado.

-------------------------------------------------------------------------------------

INICIO DA INSTALAÇÃO DENTRO DO VIRTUAL BOX
- Com o virtual box já instalado, eu clico em NOVO, onde abre uma nova janela pedindo informações sobre o sistema operacional no qual deseja instalar.
- Coloquei o nome: Debian-11.0.0-x64 
- Automaticamente o virtual box reconhece o tipo de sistema operacional, sendo Linux e a versão Debian(64bit), porém a primeira vez que tentei só apareceu a opção de 32-bit. Tive que abrir a BIOS do meu computador e habilitar opção de máquinas virtuais.
( Tutorial para poder utilizar a versão 64-bit: https://www.youtube.com/watch?v=w4E1uqwBXDc&ab_channel=WebClick )
- Ao clicar em "OK" passa para a próxima janela onde pede a quantidade de MB para tamanho da memória (RAM). Coloquei a opção de 2048MB e dei próximo.
- Na próxima janela já estava habilitado a opção "Criar um novo disco rígido virtual agora", deixei selecionado e cliquei em "Criar".
- 
- Tipo de arquivo de disco rígido: VDI (VirtualBox Disk Image)
- Armazenamento em disco rígio físico: Dinamicamente alocado
- Localização e tamanho de arquivo: localização já escolhida pelo virtual box
	  tamanho já definido 8,00GB.
-------------------------------------------------------------------------------------

ACRESCENTAR A ISO 
- Abrir configurações do sistema já instalado
- armazenamento
- Dispositivos de armazenamento: criar
- Acrescentar - ir na pasta onde está localizado a ISO, escolher ela e abrir
	selecionar a ISO e "ESCOLHER"
- A mesma aparece e você clica em "OK"
OBS> A MESMA PODE SER INSTALADA JÁ AO INICIAR A MÁQUINA VIRTUAL   

-------------------------------------------------------------------------------------

INICIAR O SISTEMA DEBIAN E CONFIGURAR

- Para instalar sem a interface gráfica cliquei na opção "install"
- Linguagem: Português > Brasil
-	Aguardar carregamento
- Nome da máquina: nomeescolhido (Por padrão já vem debian, deixei esse mesmo)
-	Nome de domínio: (pode ser deixado em branco)
-	Senha do root : 1234
-	Confirmar senha
-	Nome comp´leto para novo usuário>: Thainara Carvalho
-	Nome de usuário para sua conta: thanaracs
-	Senha para novo usuário: 1234
-	Selecione sua localização para horario
-	Particionamento de disco: Assistido - Usar o disco inteiro
-	Selecione o disco a ser particionado: enter
-	Esquema de particonamento: todos os arquivos em uma partilção(para iniciantes)
-	finalizar o particionamento e escrever as mudanças no disco
-	Mostra as mudanças e pergunta se deseja escrever: SIM

- Pergunta se quer ler a mídia: NÃO
- País do espelho do repositório Debian: Brasil
- Espelho do repositío debian - Servidor FTP para realizar o download dos pacotes
- Informações sobre proxy HTTO: deixe em branco

ESCOLHER OS SOFTWARES A SEREM INSTALADOS: 
- Ambiente da parea de trabalho
- Servidor SSH
- Utilitários do sistema padrão
- Instalar o carregador de Inicialização GRUB no seu disco primário? SIM (Pois caso contrário o sistema operacional 	não irá rodar.)
-	Onde deseja instalar: partição no qual está instalado o sistema operacional.

INFORMA QUE A INSTALAÇÃO ESTÁ COMPLETA:  -CONTINUAR-
-------------------------------------------------------------------------------------

INICIALIZAÇÃO DA MÁQUINA
- Inicialização automática caso você não faça escolhha
-	Mostra o usuário e solicita senha
	
