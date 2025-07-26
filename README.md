<h1 align="center"> VisionApp </h1>

<div align="center">

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)
![Static Badge](https://img.shields.io/badge/Flutter-blue?style=for-the-badge&logo=flutter)
![Static Badge](https://img.shields.io/badge/minio-purple?style=for-the-badge&logo=minio&logoColor=white)
![Static Badge](https://img.shields.io/badge/python-gray?style=for-the-badge&logo=python&logoColor=yellow)
![Static Badge](https://img.shields.io/badge/postgresql-blue?style=for-the-badge&logo=postgresql&logoColor=white)
![Static Badge](https://img.shields.io/badge/docker-blue?style=for-the-badge&logo=docker&logoColor=white)
![Static Badge](https://img.shields.io/badge/firebase-red?style=for-the-badge&logo=firebase&logoColor=yellow)




  
</div>

## Sumário

* [Integrantes](#integrantes)
* [Descrição](#descrição)
* [Requisitos](#requisitos)
* [Tecnologias](#tecnologias)
* [Fluxo do Software](#fluxo-do-software)
* [Dificuldades](#dificuldades)
* [Resultados](#resultados)
* [Conclusao](#conclusao)


## Integrantes

- Anderson do Vale - [and3510](https://github.com/and3510) 
- Beatriz Barreto - [whosbea](https://github.com/whosbea)
- Cristovam Paulo - [cristovam10000](https://github.com/cristovam10000)
- Gustavo do Vale - [gustavodovale](https://github.com/gustavodovale)
- Lucas Cesar


## Descrição

Desenvolvimento de um aplicativo de segurança pública que utiliza reconhecimento facial baseado em IA para identificação de indivíduos durante abordagens policiais. O sistema compara a imagem capturada com um banco de dados oficial e exibe informações como nome, CPF e pendências judiciais. Caso haja mandado de prisão ativo, um alerta é enviado ao policial, agilizando a tomada de decisão.

## Requisitos


#### **1. Captura de Imagem**  
- Permitir a captura de imagem em tempo real via câmera do dispositivo móvel.  
- Processar a imagem capturada para extração das características faciais.  

#### **2. Processamento e Reconhecimento Facial**  
- Identificar pontos-chave do rosto para comparação com registros armazenados.  
- Realizar a correspondência entre a imagem capturada e as fotos cadastradas no banco de dados.  

#### **3. Consulta e Validação da Identidade**  
- Consultar o banco de dados e validar a identidade do indivíduo.  
- Recuperar e exibir as seguintes informações em caso de correspondência:  
  - Nome completo  
  - Nome da mãe  
  - CPF  

#### **4. Verificação de Pendências Judiciais**  
- Verificar automaticamente se há registros de busca ou mandados de prisão ativos.  
- Realizar a consulta de forma automática e em tempo real.  

#### **5. Exibição de Resultados**  
- Exibir a confirmação da identidade na interface do usuário.  
- Gerar um alerta para o policial caso haja alguma pendência judicial.  

#### **6. Segurança e Privacidade**  
- Restringir o acesso ao sistema apenas a usuários autorizados.  
- Registrar todas as consultas para fins de auditoria e segurança.  
- Garantir que o armazenamento e processamento das informações sigam normas de proteção de dados.  



## Tecnologias


* **Python**: Linguagem de programação versátil e fácil de aprender, usada para web, ciência de dados, automação e mais.
* **Dart**: Linguagem de programação otimizada para aplicações frontend, principalmente com Flutter.
* **MinIO**: Serviço de armazenamento de objetos compatível com S3, usado para guardar arquivos e dados em nuvem.
* **Flutter**: Framework da Google para desenvolver aplicativos nativos multiplataforma com uma única base de código.
* **Firebase**: Plataforma da Google com serviços para desenvolver apps móveis e web, incluindo banco de dados e autenticação.
* **Docker**: Plataforma para empacotar, distribuir e executar aplicações em containers de forma leve e portátil.
* **PostgreSQL**: Sistema de gerenciamento de banco de dados relacional robusto e open-source com suporte a SQL avançado.


## Fluxo do Software

<div align="center"> 

<p float="left">

<img src="images/fluxo.png" width="600"/>
</p>

</div>

## Dificuldades

- Tempo de Realização e Testes
- Configuraçao da Camera no Aplicativo
- Dificuldade de Diminuir a Ambiguidade em relação a gemeos
- Organizar a arquitetura do aplicativo para otimização

## Resultados


<div align="center"> 

<p float="left">
  <img src="images/buscaCpf.jpeg" width="200"/>
  <img src="images/home.jpeg" width="200"/>
  <img src="images/login.jpeg" width="200"/>
</p>

<p float="left">
  <img src="images/rulesface.jpeg" width="200"/>
  <img src="images/pessoasencontradas.jpeg" width="200"/>
  <img src="images/perfilCriminoso.jpeg" width="200"/>
</p>

<p float="left">
  <img src="images/interface_FastApi.png" width="600" height="300"/>
</p>


</div>



## Conclusao

O VisionApp representa um avanço significativo no apoio às operações de segurança pública, oferecendo uma solução inovadora para a identificação de indivíduos por meio de reconhecimento facial baseado em IA. Nosso compromisso é proporcionar abordagens policiais mais seguras, eficientes e ágeis, garantindo que as autoridades tenham acesso rápido a informações críticas para a tomada de decisão.

Através da integração de tecnologias robustas como Flutter, Python, Firebase, Docker, MinIO e PostgreSQL, construímos um sistema capaz de capturar e processar imagens em tempo real, realizar reconhecimento facial preciso, consultar bancos de dados de forma eficaz e alertar sobre pendências judiciais. Apesar dos desafios enfrentados, como a otimização da arquitetura e a configuração da câmera, a equipe superou as dificuldades para entregar uma ferramenta valiosa.
