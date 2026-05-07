# 🚲 BikeToGo

> **Conectando proprietários de pequenos veículos às melhores oficinas e prestadores de serviço locais.**

O **BikeToGo** é uma plataforma digital desenvolvida para facilitar a manutenção de pequenos veículos. O sistema atua como uma ponte entre clientes que precisam de reparos (como ciclistas) e prestadores de serviços, como oficinas de bicicletas e borracharias, otimizando a conexão, o agendamento e a gestão desses serviços.

## 📋 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Arquitetura e Engenharia](#-arquitetura-e-engenharia)
- [Tecnologias e Banco de Dados](#-tecnologias-e-banco-de-dados)
- [Documentação](#-documentação)
- [Autores](#-autores)

## 🎯 Sobre o Projeto

Este projeto nasceu da necessidade de modernizar e centralizar o acesso a serviços de manutenção de veículos de pequeno porte. O BikeToGo vai além de um simples catálogo de oficinas, oferecendo um fluxo sistêmico completo: desde a criação da empresa na plataforma até a conclusão do serviço. Todo o desenvolvimento é fortemente apoiado por boas práticas de arquitetura de software, atributos de qualidade e padrões de projeto.

## ✨ Funcionalidades Principais

* **Gestão de Entidades:** Cadastro de clientes e fluxo completo para a criação de empresas (oficinas e borracharias).
* **Conexão Cliente-Oficina:** Sistema de busca e *match* entre a necessidade de manutenção do cliente e as oficinas mais adequadas disponíveis.
* **Gestão de Serviços:** Acompanhamento do fluxo de atendimento e status das manutenções solicitadas.

## 🏗️ Arquitetura e Engenharia

O desenvolvimento do BikeToGo segue padrões rigorosos para garantir um software manutenível e escalável:

* **Padrões de Projeto (Design Patterns):** Aplicação de padrões de projeto voltados para o domínio da aplicação, com destaque para a implementação do padrão **Observer**, garantindo baixo acoplamento e reatividade no ecossistema de entidades.
* **Modelagem UML:** O sistema foi estruturado e validado através de múltiplos diagramas UML, incluindo diagramas Lógicos, de Classe e de Sequência detalhados.
* **Gestão de Configuração e Versionamento:** Gerenciamento do ciclo de vida do código utilizando **GitFlow**, proporcionando fluxos seguros para o desenvolvimento de novas *features*, *releases* e aplicação de *hotfixes* emergenciais.
* **Gestão de Projeto:** Planejamento estruturado por meio de uma Estrutura Analítica de Projeto (EAP) e um plano de trabalho rigoroso definindo cronogramas e responsabilidades.

## 💻 Tecnologias e Banco de Dados

* **Banco de Dados (PostgreSQL):** Modelagem de dados robusta fundamentada em álgebra relacional, com uso intensivo de scripts SQL, *Stored Procedures* e *Triggers* para garantir a integridade e regras de negócio complexas a nível de banco.
* **Ecossistema de Linguagens:** Arquitetura flexível e aderente para implementações no back-end utilizando linguagens modernas como Java, Go, Python ou C.
* **Análise de Dados e IA:** Suporte à integração de dados e análise estruturada via Excel, explorando ferramentas de mineração de dados como WEKA.

## 📚 Documentação

A documentação do BikeToGo foca na transparência das decisões arquiteturais e na clareza estrutural, alinhada com as normas de qualidade de software (como a ISO/IEC 25010):
* **Modelo C4:** Representação da arquitetura em diferentes níveis de abstração (Contexto, Contêineres, Componentes e Código), modelada como código (Docs as Code) utilizando a ferramenta **Structurizr**.
* **Arc42:** Template adotado para a comunicação eficiente de restrições, decisões e visualização técnica do sistema.

## 👥 Equipe e Autores

* **Davi Augusto Ferreira de Carvalho** - *Engenharia de Software e Desenvolvimento*
* **Leany Silva** - *Colaboração e Projeto Acadêmico*