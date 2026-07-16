# orquestrador-open-source
Arquitetura e templates de integração para IA local corporativa.

# Open-Source Legal & Corporate AI Orchestrator

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Sobre o Projeto
Este repositório contém a arquitetura base e os templates de integração para orquestrar modelos de Inteligência Artificial rodando localmente (via **Ollama** e **OpenCode**) com sistemas de CRM e APIs de comunicação (como WhatsApp).

O objetivo deste projeto é fornecer **developer tooling** e frameworks educacionais para modernizar operações de escritórios e empresas não-técnicas, democratizando o acesso a automações complexas com privacidade de dados (essencial no meio jurídico e corporativo).

## Arquitetura Proposta
A solução foi desenhada para operar na seguinte estrutura lógica:
1. **Camada de IA Local:** Modelos open-source orquestrados via Ollama, garantindo que dados sensíveis não trafeguem em nuvens públicas.
2. **Camada de Integração (Middlewares):** Scripts de automação que conectam os outputs da IA com plataformas de CRM (ex: Kommo).
3. **Camada de Comunicação:** Disparo e triagem de mensagens utilizando APIs do WhatsApp.

## Impacto no Ecossistema
A adoção de tecnologias de código aberto muitas vezes esbarra na falta de conhecimento técnico do usuário final em setores tradicionais. Este projeto visa construir a "ponte" que faltava, permitindo que advogados e empresários implementem fluxos de trabalho avançados utilizando dependências de código aberto de forma segura.

## Instalação e Uso (Work in Progress)
*Aviso: Os módulos de integração de APIs estão em fase de refatoração para remoção de dados sensíveis antes da publicação completa.*

1. Certifique-se de ter o [Ollama](https://ollama.com/) instalado localmente.
2. Clone este repositório.
3. Configure as variáveis de ambiente no seu CRM baseando-se no arquivo `.env.example` (em breve).

## Contribuição
Sinta-se à vontade para abrir *Issues* ou enviar *Pull Requests* com melhorias nos fluxos de automação.
