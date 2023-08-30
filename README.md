
# Título do projeto

<!-- 
Detalhes sobre o projeto e seu objetivo:
O que a solução faz?
Quem usa a solução?
Como acesso a aplicação?
Descrição técnica do objetivo do código
Links para conteúdos técnicos adicionais
Link para materiais relacionados ao negócio, como o Modelo de negócio, Personas, Modelo de domínio, Épicos e História
 -->

<!-- 
- Para visualizar a aplicação acesse o  
- 
-->

------
**Navegue pela documentação:**
| [Arquitetura e stack]() | [Instalação e Como usar](Aulas_Professor) |
| :---------------------: | :---------------------------------------: |
-------


<!--
Um parágrafo da descrição do projeto vai aqui
 https://guia.dev/pt/pillars/software-architecture/technical-documentation.html 
 -->



## 📋 Arquitetura e stack

Este projeto faz parte de um conjunto de aplicações estruturadas em uma arquitetura de microserviços, e  em uma arquitetura **Featured Sliced** com a seguinte organização de pastas:
<!-- 
- Breve descrição sobre a arquitetura utilizada.
- Quando a arquitetura segue um padrão ou estilo conceitual, não é necessário detalhar o conceito, basta citar o padrão ou estilo criando um link para um conteúdo confiável que detalhe o mesmo.
- Caso a documentação de arquitetura esteja em um arquivo próprio, citá-lo no README com um link para o mesmo.
- Fazer uso de desenhos para representar a arquitetura. Esta prática está detalhada no tema Desenhos técnicos no guia.
- Citar a linguagem e frameworks utilizados, informando no máximo a sua versão major. Isso porque normalmente o detalhe das versões está no arquivo de configuração da ferramenta de dependências utilizada, logo não é necessário ter informações duplicadas.
- Informar as dependências do projeto, sejam as de outros serviços, projetos ou bibliotecas. Para caso de bibliotecas, o ideal é apenas citar ou fazer um link ao arquivo de configuração.
 -->

<!-- 
Esta aplicação faz parte de ..... em uma arquitetura de micro-frontends .....

Detalhes de stack e integrações:
- Uso do framework X
- Estado utilizando Y
- Integra a API xyz usada para ....
- Bibliotecas usadas pelo projeto e seus objetivos:
  - biblioteca 1 - gerar drag em drop

 -->


#### ⚡ Tech Stack

- Código feito em Typescript
- Testes utilizando Vitest



## 📦 Instalação e Como usar


#### Instalação

Para executar os scripts é necessário configurar as variáveis de ambiente:
• DATABASE_URL: com endereço completo de conexão com banco de dados Postres.
• EVENT_BUS_URL: com endereço completo de conexão com o barramento de eventos, o Kafka.

Os scripts de execução estão implementados utilizando o Npm e o Vite, para instalar execute:

```bash
npm install # Instala todas as dependências do projeto
```


#### Como usar

```bash
npm run dev # Executa o projeto localmente
```


## ⚙️ Orientações para desenvolvimento

A cada funcionalidade desenvolvida deve ser criada uma nova branch seguindo o seguinte formato:
**feat/***{desc}* -> Para novas funcionalidades
**fix/***{desc}* -> para ajustes e correções de bugs

A partir da branch deve ser aberto um Merge Request com detalhes sobre a funcionalidade desenvolvida.

Utilize [SemVer](https://semver.org/) para controle de versão e definição das tags geradas. Para as versões disponíveis, observe as [tags neste repositório]().

As alterações devem conter testes de unidade e passar em todos os testes.

