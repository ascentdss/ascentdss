<div align="center">
  <img src="./assets/clay-header.svg" alt="BROE — desenvolvimento web, sistemas, infraestrutura Linux e Minecraft" width="100%" />
  <p><strong>BROE</strong> · Desenvolvimento de software, produtos digitais e projetos de Minecraft</p>
  <p>
    <a href="#sobre">Sobre</a> ·
    <a href="#web">Web</a> ·
    <a href="#backend">Backend</a> ·
    <a href="#vps">VPS e deploy</a> ·
    <a href="#fluxos">Fluxos de cliente</a> ·
    <a href="#minecraft">Minecraft</a> ·
    <a href="#projetos">Projetos</a> ·
    <a href="#ferramentas">Ferramentas</a>
  </p>
</div>

---

<a id="sobre"></a>
## 01 · Sobre

Sou conhecido como **BROE**. Trabalho no desenvolvimento de aplicações web, sistemas de gestão, ferramentas para desktop e projetos relacionados a servidores de Minecraft. Também faço configuração de ambientes Linux, implantação de aplicações, integração com bancos de dados e ajustes no funcionamento de sistemas.

Meus projetos envolvem tanto a parte visível para o usuário quanto o funcionamento por trás dela: **interface, regras de negócio, APIs, armazenamento de dados, infraestrutura e operação**.

Neste perfil organizo as áreas com as quais trabalho e alguns projetos em desenvolvimento. Nem todos os repositórios são públicos.

<a id="web"></a>
## 02 · Desenvolvimento web e interfaces

| Área | Atividades |
| --- | --- |
| **Front-end** | Estruturação de páginas, componentes, formulários, menus, modais, dashboards e painéis administrativos. |
| **Responsividade** | Adaptação de interfaces para computador, tablet e celular; ajustes de navegação, proporção e espaçamento. |
| **UI / UX** | Organização de informações, hierarquia visual, contraste, estados de botões, feedback de ações e redução de etapas desnecessárias. |
| **Identidade visual** | Temas escuros e claros, claymorphism, ícones, cartões, tipografia, animações discretas e componentes reutilizáveis. |
| **Interações** | Carrinhos, seleção de variantes, filtros, pesquisa, campos com sugestões, diálogos de confirmação e validações. |
| **Experiência mobile** | Layout compacto, menus adequados ao toque, barras de rolagem personalizadas e atenção ao desempenho. |

**Tecnologias com as quais trabalho:** HTML, CSS, JavaScript e aplicações web integradas ao Node.js.

<a id="backend"></a>
## 03 · Backend, APIs e banco de dados

| Área | Atividades |
| --- | --- |
| **Backend com Node.js** | Organização de serviços, rotas, endpoints e lógica de aplicação. |
| **APIs** | Troca de dados entre front-end e servidor, validação de requisições, respostas de erro e integrações. |
| **Autenticação e acesso** | Estrutura de contas, sessões e permissões para diferentes tipos de usuário. |
| **MySQL** | Modelagem de tabelas, relações, consultas, atualização de registros e persistência de dados. |
| **Migrações de banco** | Evolução de esquemas e cuidado com compatibilidade entre versões. |
| **Regras de negócio** | Estados de pedidos, pagamentos, estoque, cálculos de custos, precificação e controle operacional. |
| **Diagnóstico** | Investigação de erros HTTP, falhas de endpoints, logs do servidor e problemas relacionados a consultas SQL. |

Também trabalho com a separação entre o que deve ser validado no **cliente** e o que precisa ser confirmado pelo **servidor**, principalmente em operações que alteram dados ou movimentam pedidos e pagamentos.

<a id="vps"></a>
## 04 · VPS, Linux e hospedagem

Configuro e administro ambientes utilizados para aplicações web e servidores de jogos, principalmente com **Ubuntu Linux**.

| Área | Atividades |
| --- | --- |
| **VPS** | Preparação de ambiente, instalação de dependências, estrutura de arquivos e organização de serviços. |
| **Acesso remoto** | Conexões com SSH, transferência com SCP e operações via terminal. |
| **Linux** | Comandos de administração, usuários, grupos, proprietários de arquivos e permissões. |
| **Serviços** | Criação, inicialização, reinicialização e acompanhamento de processos com `systemd`. |
| **Hospedagem web** | Publicação de aplicações Node.js, configuração de ambiente e conexão com MySQL. |
| **Servidor Minecraft** | Organização de instância dedicada, mods, mundo, permissões e acompanhamento de execução. |
| **Logs e manutenção** | Leitura de mensagens do sistema, análise de falhas de inicialização e correções de configuração. |
| **Versionamento e deploy** | Uso de Git/GitHub, publicação de novas versões e validação após a implantação. |

**Ambientes com os quais já trabalhei nos projetos:** VPS Contabo com Ubuntu, Hostinger para aplicações Node.js e MySQL, além de Windows/PowerShell para desenvolvimento e administração remota.

<a id="deploy"></a>
## 05 · Meu fluxo de desenvolvimento e implantação

Trabalho com o ciclo completo de evolução de uma funcionalidade, desde a necessidade inicial até o teste em ambiente de execução.

| Etapa | Como organizo |
| --- | --- |
| **1. Planejamento** | Definição do problema, telas envolvidas, comportamento esperado e regras de funcionamento. |
| **2. Interface** | Criação ou ajuste do layout, campos, estados de interação e versão mobile. |
| **3. Lógica** | Implementação de endpoints, validações, cálculos e integração com o banco. |
| **4. Testes** | Verificação dos caminhos principais, mensagens de erro e comportamento entre cliente e servidor. |
| **5. Versionamento** | Organização de mudanças no Git e publicação no repositório correspondente. |
| **6. Implantação** | Atualização do ambiente de hospedagem ou da VPS e revisão das configurações necessárias. |
| **7. Acompanhamento** | Consulta de logs, correções e novos testes após o deploy. |

Em projetos maiores também separo ferramentas **client-side** de componentes **server-side**, evitando que funções de interface sejam carregadas no servidor dedicado.

<a id="fluxos"></a>
## 06 · Experiência do cliente, vendas e operações

Nos sistemas comerciais, trabalho na organização do caminho que diferentes usuários percorrem: **cliente, gestor e entregador**. Um exemplo é o projeto **Ascent GO**.

**Fluxo do cliente**

1. Visualização do catálogo, categorias, produtos e adicionais.
2. Escolha de quantidades, opções e montagem do carrinho.
3. Preenchimento de endereço, número, complemento e confirmação de localização.
4. Seleção de entrega ou retirada e consulta às taxas aplicáveis.
5. Escolha do pagamento: PIX, débito, crédito e, quando aplicável, dinheiro com troco.
6. Confirmação do pedido e acesso ao acompanhamento do andamento.

**Fluxo do estabelecimento**

1. Recebimento e visualização de pedidos no painel.
2. Conferência de itens, observações, pagamento e tipo de atendimento.
3. Atualização dos estados de preparo, retirada e entrega.
4. Cadastro de produtos, categorias, adicionais e insumos.
5. Cálculo de custo por receita, CMV, preço de venda e margem.
6. Controle operacional e consulta a informações de estoque.

**Fluxo do entregador**

1. Acesso aos pedidos liberados para entrega.
2. Consulta a endereço, informações necessárias e forma de pagamento.
3. Abertura de mapa ou navegação por rota.
4. Atualização do andamento e confirmação da entrega.

**Integrações e experiência:** geolocalização, autocomplete de endereços, mapas e rotas (incluindo uso de Geoapify), links de acompanhamento, mensagens via WhatsApp e estudo de notificações para desktop/mobile.

> **Nota:** o Ascent GO continua em desenvolvimento. Os fluxos acima descrevem áreas do sistema em que trabalho; recursos específicos podem estar em implementação, revisão ou testes.

<a id="minecraft"></a>
## 07 · Minecraft, mods e servidores multiplayer

Desenvolvo sistemas e ferramentas para **Minecraft Java / Fabric 1.20.1**, com atenção à execução em **servidores dedicados**.

| Área | Atividades |
| --- | --- |
| **Mods Fabric** | Desenvolvimento de funcionalidades em Java e integração com o ambiente do Minecraft. |
| **Arquitetura multiplayer** | Separação de lógica do servidor e interface do cliente, sincronização e validação de ações. |
| **RPG e progressão** | Classes, habilidades, profissões, níveis, experiência e sistemas de evolução. |
| **Personagens** | Seleção, dados individuais e controles administrativos para gerenciamento. |
| **Equipamentos** | Categorias de itens, slots, atributos, bônus e restrições por classe. |
| **Economia e NPCs** | Lojas, compra/venda de itens e regras de transação controladas pelo servidor. |
| **Interfaces** | HUDs, inventários personalizados, editores, menus, telas de personagem e painéis de administração. |
| **Modelos e texturas** | Fluxos com Blockbench, arquivos JSON, texturas PNG e projetos BBMODEL. |
| **Operação do servidor** | Mods, configuração, acompanhamento de logs, desempenho e organização de arquivos do mundo. |

No **Ascent Universe**, trabalho especialmente com as classes **Aventureiro, Agricultor e Ferreiro**, seus equipamentos, profissões, desbloqueios e regras de progressão. Os sistemas são desenvolvidos e ajustados gradualmente.

<a id="desktop"></a>
## 08 · Aplicações desktop e ferramentas próprias

- **Launchers para Windows:** interface, configuração, distribuição, fluxo de atualização e preparação de builds.
- **Ferramentas de edição:** painéis para cadastrar, visualizar, organizar e ajustar itens e recursos de projetos.
- **Importação de arquivos:** uso de JSON, PNG e BBMODEL em fluxos de criação de conteúdo.
- **Ferramentas locais:** construção de utilitários que podem funcionar no próprio computador, sem depender de hospedagem.
- **Diagnóstico:** telas de logs, exportação de informações e recursos que ajudam a localizar problemas.
- **Experiência de uso:** organização por abas, pré-visualização, respostas visuais e interfaces que não travem a aplicação.

<a id="projetos"></a>
## 09 · Projetos em desenvolvimento

<img src="./assets/clay-projects.svg" width="100%" alt="Ascent Universe, Ascent GO e Ascent Launcher, em cartões minimalistas claymorphism" />

### Ascent Universe
**Área:** Minecraft / RPG multiplayer / Java / Fabric

Ecossistema de mods e ferramentas para um servidor com classes, progressão, personagens, equipamentos, economia, interfaces e administração. Inclui trabalhos com editores de itens, modelos e texturas.

### Ascent GO
**Área:** Plataforma web / pedidos / entregas / gestão

Sistema de comércio e delivery com foco no atendimento ao cliente e na operação do estabelecimento: catálogo, carrinho, checkout, localização, entregas, pagamentos, estoque e custos.

### Ascent Launcher
**Área:** Aplicação para desktop / distribuição de software

Launcher para organizar o acesso ao ambiente Ascent, com atenção à instalação, apresentação da interface e manutenção de versões.

### Ferramentas e módulos complementares
**Área:** Editores / automação / interface / administração

Trabalho em ferramentas auxiliares para criação de conteúdo, edição de equipamentos e skins, organização de recursos e suporte aos fluxos de desenvolvimento.

<sub>Alguns projetos estão em repositórios privados. As descrições são públicas, mas não representam uma lista de recursos já lançados ou disponíveis para download.</sub>

<a id="ferramentas"></a>
## 10 · Tecnologias, ferramentas e ambientes

| Categoria | Tecnologias e ferramentas |
| --- | --- |
| **Linguagens** | Java, JavaScript, HTML, CSS e SQL |
| **Web e backend** | Node.js, APIs HTTP, integração de sistemas |
| **Banco de dados** | MySQL |
| **Infraestrutura** | Linux, Ubuntu Server, VPS, SSH, SCP, `systemd` |
| **Versionamento** | Git, GitHub |
| **Terminal e edição** | Neovim, LazyVim, LSP, tmux, PowerShell |
| **Minecraft** | Fabric 1.20.1, Fabric API, Gradle, ambiente client/server |
| **Modelagem e recursos** | Blockbench, JSON, PNG, BBMODEL |
| **Mapas e logística** | Geoapify, geocodificação, rotas e localização |
| **Hospedagem** | Hostinger, VPS Linux / Contabo |
| **Organização técnica** | Logs, testes, documentação de mudanças, configuração e deploy |

### O que priorizo nos projetos

- Interfaces organizadas, acessíveis e adaptadas a dispositivos diferentes.
- Bom desempenho, carregamento eficiente e respostas claras ao usuário.
- Separação adequada de responsabilidades entre front-end, servidor e banco.
- Dados consistentes e validação de operações importantes.
- Diagnóstico de erros, testes e manutenção contínua.
- Documentação suficiente para retomar e evoluir um projeto sem perder o contexto.

---

<div align="center">
  <strong>BROE</strong><br/>
  Desenvolvimento web · Sistemas · Infraestrutura · Minecraft<br/><br/>
  <a href="https://github.com/ascentdss?tab=repositories">Repositórios públicos</a> ·
  <a href="https://github.com/ascentdss">Perfil no GitHub</a>
</div>
