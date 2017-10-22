# Projeto para Web

Vou procurar listar neste repositório, uma __checklist__ de ítems a serem cumpridos em um projeto __web__.

Essas métricas se aplicam a projetos simples, com curto prazo de desenvolvimento, mas ajudam a garantir o mínimo de qualidade para um projeto funcional.

É importante que a cada etapa, sejam gerados artefatos a serem armazenados de acordo com algum padrão. Pode ser com a ajuda de algum _software_ ou até mesmo uma _planilha_. A forma com que estes dados serão organizados fica a critério de cada equipe.

## Índice

1. [Briefing](#briefing)
2. [Coleta dos Colaboradores](#coleta-dos-colaboradores)
3. [Formalização](#formalizacao)
4. [Preparação do Ambiente](#preparacao-do-ambinete)
5. [Documentação](#documentacao)
6. [Criação](#criacao)
7. [Desenvolvimento](#desenvolvimento)
8. [Testes](#testes)
9. [Publicação](#publicacao)
10. [Otimização](#otimizacao)
11. [Apresentação ao Cliente](#apresentacao-ao-cliente)
12. [Liberação](#liberacao)
13. [Divulgação](#divulgacao)
14. [Conclusão](#conclusao)

***

A seguir os passos para a criação de um **Projeto Web**:

## 1. Briefing

Esta é a etapa em que se deve entender o negócio do cliente, suas necessidades, e junto com ele identificar:

1. Como é seu negócio? Como é o seu produto? Como será o seu serviço?
2. Qual será o objetivo do _website_?
3. Qual será o público-alvo? Quando possível identificar:
  1. Classe Social;
  2. Sexo;
  3. Faixa-etária;
  4. Limitações Técnicas;
  5. Necessitam de algum tipo de Acessibilidade?

Com estas informações, é hora de definir o escopo do projeto. Neste momento é importante definir quais serão as funcionalidades que o website deverá apresentar.

O Briefing pode gerar um **Documento de Escopo**. Este documento servirá de guia para o desenvolvimento, e é uma garantia por ambas as partes de que o projeto sairá como o combinado.

Um importante artefado que pode ser incluído no **Documento de Escopo** é o **SiteMap**, no qual todas as páginas e ligações entre elas estarão identificadas em um diagrama.

## 2. Coleta dos Colaboradores

É importante saber quais serão as pessoas envolvidas no projeto, por isso é importante catalogar todos os colaboradores que participarão do projeto, armazenando informações como:

1. Nome Completo;
2. RG;
3. CPF;
4. Redes Sociais;
5. Endereço;
6. Telefones;
7. Emails.

Essas informações serão úteis na elaboração do contrato e na comunicação entre os envolvidos.

Além das informações de cada membro da equipe de desenvolvimento, **é imporante coletar os mesmos dados para os contatos responsáveis no cliente**.

## 3. Formalização

Com o **Documento de Escopo** e as informações dos colaboradores, é o momento de formalizar seu projeto. É nesta etapa que um contrato deve ser elaborado e assinado por ambas as partes.

## 4. Preparação do Ambiente

_Antes de trabalhar, temos que arrumar a mesa._

Então nesta etapa seguirão algumas dicas de como organizar seu projeto antes de começar o seu desenvolvimento.

1. **Comunicação** - Defina algum veículo de comunicação entre os colaboradores do projeto e entre o responsável pelo projeto e seu cliente. Isso pode ser feito por Email, Skype, ou alguma ferramenta específica como o Slack;
2. **Repositórios** - Trabalhar com repositórios é indispensável para agilizar e manter a equipe sincronizada, é importante nesta etapa criar, e configurar seus repositórios, além dar permissão para os outros colaboradores;
3. Definir o nome para o **domínio** e registrá-lo ou transferí-lo;
4. Contratar um **plano de hospedagem** que atenda os requisitos técnicos do projeto;
5. Configurar o **servidor** para receber o repositório criado;
6. Se for comércio eletrônico:
  1. Definir as instituições bancárias e formas de pagamento;
  2. Abrir conta, assinar convênios e solicitar serviços de comércio eletrônico;
7. Definir e criar **contas de e-mail**. Isso é muito importante pois impulsiona o cliente por já ter uma conta de e-mail no seu próprio domínio;
8. Definir e criar uma conta de email específica para o site no gmail. Isso é importante para cadastrar Plugins, Serivços e principalmente Analytics;
9. Criar contas em **redes sociais**. É importante que um projeto web tenha seu reflexo nas redes sociais, então, dependendo do que foi acordado, este é o momento para definir os nomes e criar as redes sociais, dentre as mais comuns:
  1. Twitter;
  2. YouTube;
  3. FaceBook;
  4. Instagram;
  5. Google Plus;
10. Criar ou resgatar **conta de monitoramento** (Google Analytics)
11. Caso o site já exista:
  1. Fazer um backup de segurança do site antigo;
  2. Fazer um backup de segurança do banco de dados antigo;
  3. Análise de popularidade (Estatísticas de Acesso, Ranking em Ferramentas de Busca). Isso ajudará a mostrar os resultados em comparações com os resultados a serem obtidos com o novo projeto;

## 5. Documentação

Nesta fase deve-se focar os esforços em projetar o website. Em projetos mais complexos, é nesta etapa em que se deve criar os diagramas de **Entidades e Relacionamentos** e de **Classes**, por exemplo.

Em projetos menores, basta uma reunião com a equipe de Design para transformar as funcionalidades descritas no **Documento de Escopo** em **wireframes**.

## 6. Criação

Esta etapa é focada aos Designers, que desenvolverão o _layout_ do website.

Antes da criação do **wireframe** uma serie de atividades devem ser observadas:

1. Analisar **identidade visual** da empresa, produto ou serviço;
2. Definir **seções e blocos** de informação;
3. Desenhar **mapa do site** e **fluxo de navegação**;
4. Estudar e definir a **paleta de cores**;
5. Estudar e difinir **símbolos e ícones**;
6. Definir **tipografia**;
7. Criação/Adaptação de um **logotipo da empresa**;
8. Definir **efeitos visuais** (recursos multimídia);

Com estas etapas definidas e os **wireframes** prontos, o designer deve iniciar a criação dos arquivos de **Imagem** (PSD).

Via de regra, não é necessário a criação do _layout_ final de todas as páginas do projeto. A criação da página principal e uma página interna agiliza muito o trabalho de todos os envolvidos.

Em projeto mais complexos, pode ser interessante a criação de um documento de **"Guia de Design"**, no qual o _designer_ define as etapas anteriores em um documento textual, que será o guia do desenvolvedor durante todo o desenvolvimento.

Mas é essencial que, pelo menos as telas mais importantes sejam desenvolvidas. Este será o material a ser aprovado pelo cliente antes da próxima etapa.

## 7. Desenvolvimento

Após a aprovação do layout pelo cliente, pode-se iniciar o desenvolvimento propriamente dito.

Quase sempre dividimos uma aplicação web em três partes: _Front-End_, _Back-End_ e _Integração_.

A parte de **Front-End** é responsável por transformar a Imagem do site criada pelo Designer em uma página de base codificada (HTML5/JavaScript/CSS) funcional.

A parte de **Back-End** é responsável por implementar as funcionalidades definidas no **Documento de Escopo**.

A parte de **Integração** é responsável por ligar os as funcionalidades do **Back-End** com o **Front-End**. Normalmente isso pode ser feito através de integrações JavaScript do **Front-End** que consomem a API definida no **Back-End**.

Uma série de passos podem ser seguidos para realizar as três etapas com sucesso:

* Criar estrutura de pastas;
* Baixar, instalar e configurar dependências (_framework_s, _plugins_ e _APIs_);
* Recortar o _layout_ e criar base codificada (HTML5/JavaScript/CSS);
* Criar e organizar _Meta-Informações_ de cada página (_MetaTags_);
* Criar OG (_OpenGraph_) para cada página;
* Criar Schemas (_Schemas.org_) para cada elemento da página;
* Configurar rotas para as páginas (ou .httaccess);
* Configurar ferramenta para minificação de CSS e JS;
* Criar _sitemap.xml_;
* Criar _robots.txt_;
* Criar páginas com conteúdo estático;
* Criar banco de dados;
* Popular banco de dados com valores iniciais ou importação de dados pré-existentes;
* Criar estrutura de Back-End: Criação dos CRUDS;
* Realizar integração Back-End com Front-End;

Ps. A ordem destas tarefas pode ficar a critério de cada equipe.

Todas as funcionalidades devem ser testadas por cada colaborador, até que o sistema chege a um ponto de maturidade no qual precisa de testes mais específicos.

Cada projeto possui uma particularidade de como os testes serão realizados, testes automáticos quase sempre é uma boa opção para projetos maiores, entretanto, para projetos de medio e pequeno porte, o bom e velho teste convencional dá conta do recado. Pois você passará menos tempos testando que escrevendo os casos de teste.

## 8. Testes

Esta é uma fase importante, e que provavelmente será feita algumas vezes.

Alguns detalhes que não podem ser esquecidos:

1. Renderização em diferentes navegadores;
2. Renderização em diferentes versões de navegadores;
3. Navegação da página;
4. Leitura do conteúdo;
5. Desempenho em ambiente de produção;
6. Funcionalidades respondem como o esperado?
7. Qualidade das Imagens;

Além disso é importante utilizar algumas ferramentas de testes automáticos como:

### Teste de responsividade

https://www.google.com/webmasters/tools/mobile-friendly

### Schemas

https://developers.google.com/structured-data/testing-tool/

### Meta Tags

http://www.seocentro.com/tools/search-engines/metatag-analyzer.html

http://analyzer.metatags.org/

### SEO

http://seositecheckup.com/

## 9. Publicação

Depois que os testes foram relizados, é a hora de publicar o projeto.

Claro, que seu cliente já deve ter visto uma previa do website em algum ambiente de desenvolvimento, mas é neste momento que o _presente deverá ser entregue_, então é importante que tudo esteja testado e validado internamente entre a equipe de desenvolvimento antes de ser publicado, para causar uma boa impressão inicial.

E nós sabmos que, quase sempre, quando colocamos em um ambiente de produção, nem tudo ocorre como o esperado. Algum problema com versão da linguagem ou do banco de dados, então é importante refazer todos os testes também no ambiente final.

Um checklist pode ser executado:

1. Validação de Código;
2. Meta-informações;
3. Título das páginas;
4. Integridade de Links;
5. Qualidade de Imagens;
6. Qualidade de Textos;
7. Funcionamento e navegação de formulários;
8.Pontos de acessibilidade.

É importante lembrar que nesta etapa normalmente se utiliza uma _SplashScreen_ com alguma informação de _"Site em Construção"_ até a etapa de liberação do website.

## 10. Otimização

Quando o site é efetivamente publicado, ainda temos que fazer alguns ajutes finos para colocar em ação os scripts de monitoramentos statísticos. Então, agora é a hora de configurar o Analytics do Google.

E é claro que o sitemap.xml tem que ser atualizado, e para isso você pode utilizar alguma programação interna ou ferramentas personalizadas.

## 11. Apresentação ao Cliente

Dependendo da complexidade, essa pode ser a hora para a criação de um **manual de utilização do site**, explicando passo a passo, como navegar no site, e até mesmo detalhes de sua área administrativa.

Além disso, é importante oferecer um treinamento para as pessoas que serão responsáveis alimentar as informações do website.

## 12. Liberação

Esta etapa é apenas a retirada da _SplashScreen_ e a liberação do acesso ao público.

## 13. Divulgação

O site precisa de um empurrão inicial, então alguns pontos podem ser observados:

1. Realizar parcerias ou trocas de banners ou links, entre sites de amigos ou parceiros de negócios;
2. Buscar alternativas de publicidades online, como portais de conteúdo (UOL, TERRA, IG, GLOBO.COM), ou sites de conteúdo direcionado;
3. Buscar alternativas de anúncios pagos em serviços de busca (Links Patrocinados);
4. Realizar o acompanhamento e mensuração dos resultados de seus investimentos em publicidade de divulgação do site.

# 14. Conclusão

Este documento é apenas uma visão pessoal de todo o conhecimento empírico que venho adquirindo ao longo do tempo, e como nunca havia achado um material bacana neste formato, resolvi criar o meu próprio.

Gostou? Gostaria de colaborar?

Entre em contato: diogo@diogocezar.com

Além disso, uma serie de links podem complementar a sua pesquisa.

Estão neste repositório:

https://github.com/diogocezar/dctb-links

Obrigado.