# Radar Cidadão GV
Radar Cidadão GV é uma plataforma colaborativa que permite aos cidadãos registrar problemas urbanos em um mapa. Com apoio de IA, os relatos são classificados e priorizados, ajudando a identificar os principais desafios da Grande Vitória e orientar decisões no atendimento público.

## Assistente Inteligente para Identificação e Priorização de Problemas Urbanos
**Disciplina:** Projeto Integrador IV — Aplicações de Inteligência Artificial e Testes de Software
**Instituição:** FAESA | Curso: Ciência da Computação
**Professor(a):** Howard Cruz Roatti (howard.cruz@faesa.br)

Comunidade Foco: Município da Grande Vitória - ES
ODS Vinculados: ODS 9 (Indústria, Inovação e Infraestrutura) e ODS 11 (Cidades e Comunidades Sustentáveis)

**Equipe:** 
- Felipe Rodrigues Barzilai
- Gabriel Rodrigo Lapa Rocha
- Ricardo da Silva Junior
- Hevellyn Monteiro Medeiros
- Wagner dos Santos Cristo


## Sobre o Projeto
O Radar Cidadão GV é uma plataforma web projetada para mapear, classificar e priorizar problemas urbanos no município da Grande Vitória - ES. A aplicação utiliza Inteligência Artificial (LLMs via API do GroqCloud) para transformar relatos informais dos cidadãos (ex.: "calçada quebrada impedindo a passagem de cadeirantes") em dados estruturados contendo categoria, nível de impacto, resumo executivo e prioridade sugerida.

Além disso, a plataforma disponibiliza exportação de relatórios em planilha Excel/CSV e endpoints de API para permitir o acesso estruturado aos dados por parte da Prefeitura e associações comunitárias.


## Stack Tecnológica Consolidada
Backend: Java com Spring Boot 3 (API REST, Spring Data JPA e suporte a Apache POI para exportação de dados)
Hospedagem Backend: Render (Web Service - Free Tier)
Frontend: Angular + TypeScript + Leaflet.js (Mapas interativos com OpenStreetMap)
Hospedagem Frontend: Vercel (Free Tier)
Banco de Dados & Autenticação: PostgreSQL hospedado no Supabase (Free Tier)
Componente de IA: API do GroqCloud (Modelo Llama 3)
Acesso para Órgãos Públicos: Endpoints REST / Exportação nativa em Excel (.xlsx) / CSV

## Checklist de Entregas(C1, C2 e C3):
### C1 — Planejamento e Escopo (Prazo: 18/09/2026)
- [x] Definição da área temática, comunidade foco e ODS 
- [x] Mapeamento do problema urbano, justificativa e natureza extensionista
- [x] Definição da arquitetura técnica 
- [x] Definição dos indicadores de impacto

### C2 — Protótipo Funcional (Prazo: 30/10/2026)
- [ ] Interface frontend com mapa interativo (Leaflet/OpenStreetMap)
- [ ] Backend Spring Boot integrado à API do Groq (Llama 3) para extração de JSON
- [ ] Primeiros testes automatizados do backend e rotas críticas
- [ ] Primeiro teste/eval do componente de IA com dataset de validação
- [ ] Vídeo de demonstração do protótipo publicado no YouTube

### C3 — MVP Completo e Deploy (Prazo: 04/12/2026)
- [ ] Aplicação web MVP completa e funcional
- [ ] Dashboard de indicadores e exportação de dados para a gestão pública (Excel/CSV)
- [ ] Deploy completo na nuvem em ambiente gratuito (Render + Vercel + Supabase)
- [ ] Cobertura de testes automatizados e relatório final da eval da IA
- [ ] Análise de impacto extensionista e documentação completa
- [ ] Vídeo final de apresentação no YouTube


## Registro de Engenharia de Prompt (Diretriz do Edital)

Conforme as exigências do edital da disciplina, todo o processo de engenharia de software e documentação desenvolvido com auxílio de ferramentas de IA é registrado na tabela abaixo:

| Data | Tarefa / Artefato | Prompt Utilizado / Descrição da Atividade | Ferramenta Utilizada |
| :--- | :--- | :--- | :--- |
| 08/09/2026 | Análise e Definição da Stack | "Analisar compatibilidade de Java/Spring, Angular, Supabase, Vercel e Groq para o projeto" | Gemini Notebook |
| 17/09/2026 | Estruturação do Checklist e Engenharia de Prompt | "Elaborar escopo do C1 ao C3 e formatar o Registro de Engenharia de Prompt para Markdown" | Gemini Notebook |
