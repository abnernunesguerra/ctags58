ctags5.8 for windows
=

##    Como Definir Path no Windows:

####    Windows 8
1.    Arraste o ponteiro do Mouse até o canto inferior Direito da tela
2.    Clique no ícone Pesquisar e digite Painel de Controle
3.    Clique em -> Painel de Controle -> Sistema -> Avançado
4.    Clique em Variáveis de Ambiente, em Variáveis do Sistema, localize PATH e clique nele.
5.    Na janelas Editar, modifique PATH adicionando a localização do diretório 
onde esta o ctags.exe exemplo: (se o caminho é: C:\ctags58\ctags.exe 
coloque apenas C:\ctags58 "sem barra no final"). 
Caso você não tenha o item PATH, será possível optar por 
adicionar uma nova variável e adicionar PATH com o caminho do diretório 
onde esta o catgs.exe   como o valor.
6.    Feche a janela.
7.    Reabra a janela o GVim e no seu projeto de teste execute o comando :!ctags -R .



####    Windows 7
1.    Selecione Computador no menu Iniciar
2.    Escolha Propriedades do Sistema no menu de contexto
3.    Clique na guia Definições avançadas do sistema > Avançado
4.    Clique em Variáveis de Ambiente, em Variáveis do Sistema, localize PATH e clique nele.
5.    Na janelas Editar, modifique PATH adicionando a localização do diretório 
onde esta o ctags.exe exemplo: (se o caminho é: C:\ctags58\ctags.exe 
coloque apenas C:\ctags58 "sem barra no final"). 
6.    Caso você não tenha o item PATH, será possível optar por adicionar 
uma nova variável e adicionar PATH com o caminho do diretório onde esta 
o catgs.exe   como o valor.
7.    Reabra a janela o GVim e no seu projeto de teste execute o comando :!ctags -R .



