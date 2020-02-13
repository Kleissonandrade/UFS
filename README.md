# Power BI

  O Power BI é um serviço de análise de negócios da Microsoft com objetivo de fornecer uma interface interativa de business intelligence com layout simples e de fácil manipulação para seus usuários.

## Instalação

  O Power BI é uma ferramenta fornecida pela Microsoft e somente pode ser instalada na plataforma Windows. Podendo ser baixada através do link:  
  https://powerbi.microsoft.com/pt-br/downloads/
  
  ![download](/imagens/download.png)
  
  Após download da aplicação, execute como administrador e siga os passos a seguir:
  
  ### Passo 1

  Click em Avançar
  
  ![install-1](/imagens/install-1.png)

  ### Passo 2
    Click em Instalar

  ![install-2](/imagens/install-2.png)

  ### Passo 3
  Click em Avançar

  ![install-3](/imagens/install-3.png)
  ### Passo 4
  Marque a opção Aceito termos do Contrato de Licença e click em Avançar.

  ![install-4](/imagens/install-4.png)
  ### Passo 5
  Aguarde o término da instalação

  ![install-5](/imagens/install-5.png)
  ### Passo 6
  Pronto, o PowerBI foi instalado. Em seguida click em concluir e a aplicação sera inicializada.
  ![install-6](/imagens/install-6.png)


## Usando PowerBI

### Primeiros passos
  Ao executar a aplicação do PowerBI, ira aparecer a seguinte tela inicial:
   ![install-6](/imagens/home.png)

  Posteriormente faça o registro gratuito na plataforma.
   ![install-6](/imagens/register.png)
  
  Após ser registrado,você deve fazer login na mesma:
   ![install-6](/imagens/login.png)


### Conectando ao Banco de dados
Click na aba Arquivo da barra de tarefas e selecione a opção Obter Dados. Em seguida irá carregar a tela abaixo:

![conecta-1](/imagens/obter-dados-1.png)

Selecione a fonte de dados que deseja utilizar e click em conectar. (Nesse caso foi usado o Postgre)


![conecta-2](/imagens/obter-dados-2.png)
Após selecionar o banco. Irá solicitar que seja informado o endereço do servidor (Banco de dados) e o nome do banco. Preencha esses campos e click em "OK".

![conecta-3](/imagens/obter-dados-3.png)

Em seguida será solicitado o usuário e senha configurados em seu SGBD. Informe estes dados e click em conectar.

![conecta-4](/imagens/obter-dados-4.png)


### Carregando dados
Após ter feito a conexão com o banco de dados irá mostrar uma tela onde seram listadas todas as tabelas da base de dados escolhida como segue na ilustração abaixo:

![carrega-1](/imagens/obter-dados-5.png)

Selecione as tabelas que deseja carregar para o seu BI e click em Carregar.

![carrega-2](/imagens/obter-dados-7.png)

Após concluir o processo de carga, seram listadas todas as tabelas assim como as colunas pertencentes a estas na paleta "Campos". Como mostra a figura.
![carrega-3](/imagens/obter-dados-8.png)

Agora, toda sua base de dados esta carregada no PowerBI. Tanto suas tabelas quanto os dados persistidos nelas.

### Gerando Gráficos

![gera-1](/imagens/gera-1.png)
![gera-2](/imagens/gera-2.png)
![gera-3](/imagens/gera-3.png)
![gera-4](/imagens/gera-4.png)



### Exportando Gráficos

![exportar-1](/imagens/exportar.png)
![exportar-2](/imagens/pdf-export.png)
