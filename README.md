# Gerenciamento de Defeitos (Bugs)
---
## 1. Objetivo da atividade
- **Aprender** a configurar um projeto de rastreamento de defeitos no Jira Cloud.  
- **Praticar** testes exploratórios e a documentação de bugs usando workflow padrão do Jira.  
- **Aplicar** conceitos de ciclo de vida de defeitos em um ambiente real.  

## 2. Pré-requisitos técnicos
| Item | Descrição |
|------|-----------|
| E-mail institucional | Necessário para criar/validar a conta Atlassian. |
| Plano **Free** do Jira | Gratuito para ≤ 10 usuários, 2 GB de armazenamento. |
| Navegador atualizado | Chrome, Edge ou Firefox. |

## 3. Formação dos grupos
| Papel | Responsabilidade |
|-------|------------------|
| **Líder de Projeto** | Cria o site Jira, convida colegas. |
| **Testers** | Executam testes no mini-site <https://claudionunes.github.io/qs>. |
| **Scrum-bug-master** | Prioriza severidade/urgência, move issues no board. |
| **Documentador(a)** | Exporta relatórios e consolida entrega final. |

**Cada elemento do grupo pode exercer multiplos papéis caso necessário.**


## 4. Passo a passo no Jira

### 4.1 Criar conta Atlassian
1. Acesse [site oficial do Jira](https://www.atlassian.com/br/software/jira)
2. Clique uma conta no Jira.
3. Complete a verificação e avance para a criação do site.  

### 4.2 Criar o site (*tenant*) Jira Cloud
1. Defina um endereço único (ex.: `grupo-qs2025.atlassian.net`).  
2. Confirme o uso do plano **Free** (até 10 usuários).  

### 4.3 Criar o projeto com o template “Controle de bugs”
1. Acesse **Projects → Create project**.  
2. Selecione **Bug tracking** e clique em **Use template**.  
3. Opte por **Team-managed** para simplicidade.  

### 4.4 Configuração inicial
| Ação | Caminho |
|------|---------|
| Convidar colegas | **Project settings → Access → Invite users**. |
| Adicionar campos (opcional) | **Project settings → Issue types → Bug → Add field**. |
| Ajustar workflow (opcional) | **Project settings → Workflows** (status *To Do → In Progress → Done*). |

## 5. Testar o mini-site e registrar defeitos

### 5.1 Estratégia de teste exploratório
- Navegue por todas as páginas, variando navegadores e resoluções.  
- Tente entradas inválidas e observe mensagens de erro.  
- Documente cada passo antes de abrir o bug.  

### 5.2 Checklist de registro de bug
| Campo | Conteúdo mínimo |
|-------|-----------------|
| **Título** | Resuma o problema em até 10 palavras. |
| **Descrição** | Passos para reproduzir, resultado obtido/esperado e evidências (print). |
| **Severidade / Prioridade** | Use as opções padrão do template. |
| **Ambiente** | Navegador, SO, data/hora. |

## 6. Gestão e triagem dos defeitos
1. Realize uma “triagem de defeitos” rápida para revisar severidade e prioridade.  
2. Mova os cards no board conforme o progresso (*To Do → In Progress → Done*).  
3. Use filtros como `status != Done` e dashboards de gráficos nativos do Jira.  

## 7. Entregáveis do grupo
| Artefato | Como gerar |
|----------|-----------|
| Exportação de bugs (.csv/.xlsx) | **Filters → Export**. |
| Screenshot do board | Ferramenta de captura de tela do SO. |
| Acesso de leitura ao professor | Convidar como usuário *Viewer*. |

## 8. Recursos de apoio
- Guia de início rápido do Jira.  
- Página do template *Bug tracking*.  
- Comunidade Atlassian (dúvidas sobre o template).  
- Tutorial passo a passo de criação de conta (vídeo).  
- Artigos sobre boas práticas de bug report.  
