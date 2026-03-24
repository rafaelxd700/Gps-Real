# 👨‍💻 Diário de Atividades - Carlos (SM & Dev)

Este documento descreve detalhadamente as atividades realizadas por mim durante o planejamento do sistema RiscoZero, atuando como Scrum Master e Desenvolvedor.

---

## 🏗️ Gestão e Organização (Scrum Master)

### 01. Definir objetivo geral do sistema
* **Descrição:** Estabeleci a visão macro do projeto, definindo o RiscoZero como uma plataforma de mapeamento colaborativo para aumentar a segurança urbana e ambiental.
* **Objetivo:** Alinhar a expectativa do grupo e o propósito do software.

### 02. Criar estrutura inicial do GitHub
* **Descrição:** Realizei o setup do repositório remoto, configurei as permissões de acesso e criei os arquivos base (`README.md`, `.gitignore`) para o início dos trabalhos.
* **Objetivo:** Garantir um ambiente de versionamento organizado para a equipe.

### 03. Definir estrutura de pastas do projeto
* **Descrição:** Planejei a arquitetura de diretórios do repositório, separando pastas para documentação técnica, diagramas e futuros assets de interface.
* **Objetivo:** Manter a padronização e facilitar a localização de arquivos pelos integrantes.

### 04. Revisar backlog e prioridades
* **Descrição:** Conduzi a reunião de refinamento com o PO para garantir que as 30 tarefas estivessem claras, numeradas e ordenadas por importância para o MVP.
* **Objetivo:** Garantir que o time foque no que é mais crítico primeiro.

### 05. Definir modelo de cadastro de áreas de risco
* **Descrição:** Estruturei os campos necessários para identificar uma zona perigosa: coordenadas geográficas, raio de influência, nível de criticidade e descrição da ameaça.

### 06. Definir estrutura de banco de dados
* **Descrição:** Elaborei o esquema lógico das tabelas (Entidade-Relacionamento), focando nas tabelas de `Usuarios`, `Riscos` e `Logs_de_Atividade`.

### 07. Planejar tela inicial do sistema
* **Descrição:** Desenhei o fluxo da Home Page, priorizando o acesso rápido à geolocalização do usuário e um resumo visual dos alertas próximos.

### 08. Planejar tela de login de administrador
* **Descrição:** Defini os requisitos para a área restrita, incluindo campos de autenticação e tokens de sessão para moderadores do sistema.

### 09. Planejar tela de cadastro de risco
* **Descrição:** Planejei a interface de entrada de dados, prevendo um seletor de mapa para marcar a localização exata e upload de evidências (fotos).

### 10. Planejar funcionalidade de visualização no mapa
* **Descrição:** Estabeleci as regras de renderização dos ícones (pins) no mapa, incluindo o comportamento de agrupamento (clustering) para áreas com muitos registros.

### 11. Planejar sistema de filtro por tipo de risco
* **Descrição:** Desenvolvi a lógica de filtros laterais que permite ao usuário isolar categorias específicas no mapa (ex: ver apenas riscos de criminalidade).

### 12. Planejar visualização de detalhes de uma área
* **Descrição:** Projetei o modal informativo que exibe o histórico completo, fotos e contatos de emergência vinculados a um ponto de risco selecionado.

### 13. Planejar sistema de comentários ou denúncias
* **Descrição:** Planejei a seção interativa onde a comunidade pode confirmar a veracidade de um risco ou informar se a situação já foi normalizada.

