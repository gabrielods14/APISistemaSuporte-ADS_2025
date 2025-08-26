# 📌 Sistema de Suporte com Serviços de IA

## 🎯 Descrição do Projeto

O projeto visa desenvolver um sistema integrado de suporte técnico para uma empresa de médio porte. O objetivo é substituir o atual processo de recebimento de chamados por e-mail, permitindo o registro centralizado das solicitações. A inteligência artificial (IA) será usada para sugerir soluções de forma automática ou encaminhar os chamados ao técnico adequado, com base nas intruções fornecidas pelo time de desenvolvimento.

---

## 📋 Backlog do Produto


---

## Sprints dos requisitos do sistema:

A sprint backlog foi feita levanto os seguintes requisitos em consideração, MVP e prioridade. Usamos a metodologia de MVP para listar os requisitos minimos para ter um produto funcionando. Basedado nisso também levamos em consideração a importancia de cada requisito, dado como alta: Prioridade máxima. Média: Muito importante, porém menos urgente. Baixa: Requisito que pode ser feito mais para o final, levando em consideração funções que podem ser fetias após o sistema pronto. Abaixo terá um link para um arquivo PNG, onde tem uma tabela feita em Execel ilustrando está descrição.

- [Tabela sprint Backlog](https://github.com/gabrielods14/APISistemaSuporte-ADS_2025/blob/main/docs/Img/Sprintbacklog.jpg)
---

## Arquivo Astah com os diagramas:

- [Arquivo Astah](https://github.com/gabrielods14/APISistemaSuporte-ADS_2025/blob/main/docs/Diagramas%20UML/Diagramas%20ASTAH.astaL)
---

## ✅ Definition of Ready (DoR)


## ✅ Definition of Done (DoD)


---

## 📆 Cronograma de Sprints


| **REQUISITO**                                         | **TAREFA**                                                       | **SPRINT** | **PRIORIDADE** |
| ----------------------------------------------------- | ---------------------------------------------------------------- | ---------- | -------------- |
| Ter acesso admin                                      | Criar modelo de usuário com papel/admin                          | Sprint 1   | Alta           | 
|                                                       | Implementar autenticação e login                                 | Sprint 1   | Alta           |
|                                                       | Criar verificação de acesso somente para admins                  | Sprint 1   | Alta           |
|                                                       | Criar interface de login                                         | Sprint 1   | Alta           |
| Cadastrar usuário                                     | Criar tela de cadastro de usuário                                | Sprint 1   | Alta           |
|                                                       | Validar dados e salvar no banco                                  | Sprint 1   | Alta           |
|                                                       | Testar criação e listagem de usuários                            | Sprint 1   | Alta           |
| Cadastrar empresas                                    | Criar modelo de empresa e relacionar com usuário                 | Sprint 1   | Alta           |
|                                                       | Criar tela e API de cadastro de empresa                          | Sprint 1   | Alta           |
| Visualizar empresas                                   | Criar tela de listagem de empresas                               | Sprint 1   | Alta           |
|                                                       | Implementar filtros e seleção                                    | Sprint 1   | Alta           |
| Cadastrar instruções                                  | Criar tela de cadastro de instruções                             | Sprint 2   | Média          |
|                                                       | Validar e salvar instruções por empresa                          | Sprint 2   | Média          |
| Vincular o e-mail que será usado                      | Criar campo de e-mail de resposta por empresa                    | Sprint 2   | Média          |
|                                                       | Configurar e testar integração com MailKit (envio e recebimento) | Sprint 2   | Média          |
| IA deve responder automaticamente                     | Criar serviço da IA que processa e envia resposta                | Sprint 2   | Média          |
|                                                       | Integrar IA com sistema de e-mail (ex: MailKit)                  | Sprint 2   | Média          |
| IA deve classificar mensagens automaticamente         | Criar serviço/classificador por palavra-chave ou NLP             | Sprint 2   | Média          |
|                                                       | Relacionar categorias com instruções salvas                      | Sprint 2   | Média          |
| Caso a IA não responda, mandar para equipe de suporte | Detectar falha na IA e encaminhar mensagem para suporte humano   | Sprint 3   | Baixa          |
|                                                       | Notificar ou registrar esse redirecionamento                     | Sprint 3   | Baixa          |
| Histórico de conversa                                 | Criar tabela de logs de mensagens                                | Sprint 3   | Baixa          |
|                                                       | Criar tela de histórico com filtros e paginação                  | Sprint 3   | Baixa          |

---

## 🛠️ Tecnologias Utilizadas
- *Linguagens*: Python, HTML, CSS e JavaScript
- *Framework*: Kivy, ReactJS e ReactNative
- *Banco de Dados*: SQLServer
- *Ferramentas*: GitHub, Trello, Figma

---

## 📖 Manual de Instalação

### 🔹 Backend
```bash
# Clonar o repositório
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd backend

# Criar e ativar ambiente virtual (exemplo Python)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instalar dependências
pip install -r requirements.txt

# Executar
python app.py
```

---

## 💪 Integrantes

- [Lucas de Oliveira Silva](https://github.com/Kript0-Web) (Scrum Master)
- [Samuel Jhonata de Lima](https://github.com/SamuJL) (PO)
- [Gabriel Oliveira dos Santos](https://github.com/gabrielods14) (Dev)
- [João Gabriel Goulart Silva](https://github.com/Goulart06) (Dev)
- [Thiago Almeida Ribeiro](https://github.com/Thiagoalmeida74) (Dev)
- {Gabriel Silva Guimarães} (Dev)

---

