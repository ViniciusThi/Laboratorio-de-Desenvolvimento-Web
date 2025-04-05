# Git e GitHub - Conceitos Fundamentais

## 1. Diferença entre Git e GitHub

Git é um sistema de controle de versão distribuído que permite rastrear mudanças no código-fonte durante o desenvolvimento de software. É uma ferramenta que roda localmente no seu computador.

GitHub é uma plataforma web que hospeda repositórios Git. Ela fornece uma interface gráfica para o Git e recursos adicionais como colaboração, gerenciamento de projetos e hospedagem de código.

Eles se complementam porque:
- Git gerencia as versões localmente
- GitHub permite compartilhar e colaborar com outros desenvolvedores
- Juntos formam um ecossistema completo de versionamento

## 2. Principais características do GitHub

- **Colaboração**: Permite trabalhar em equipe de forma eficiente
- **Pull Requests**: Facilita a revisão de código
- **Issues**: Gerenciamento de tarefas e bugs
- **Actions**: Automação de processos
- **Wikis**: Documentação do projeto
- **Segurança**: Controle de acesso e proteção de código

## 3. GitHub Pages

GitHub Pages é um serviço de hospedagem estática que permite publicar sites diretamente do seu repositório GitHub.

Vantagens:
- Hospedagem gratuita
- Integração direta com seu repositório
- Suporte a domínios personalizados
- HTTPS automático
- Fácil atualização através do Git

## 4. Repositórios Públicos vs Privados

**Repositórios Públicos:**
- Visíveis para todos
- Qualquer pessoa pode clonar e contribuir
- Ideais para projetos open-source

**Repositórios Privados:**
- Visíveis apenas para você e colaboradores
- Maior controle de acesso
- Ideais para projetos comerciais ou pessoais

## 5. Comando "git remote"

O comando "git remote" é usado para gerenciar conexões com repositórios remotos. É utilizado quando você precisa:
- Adicionar um novo repositório remoto
- Verificar repositórios remotos configurados
- Remover conexões com repositórios remotos
- Alterar URLs de repositórios remotos
- Gerenciar múltiplos repositórios remotos

## 6. Diferença entre "git status" e "git log"

**git status:**
- Mostra o estado atual do seu repositório
- Exibe arquivos modificados, adicionados ou removidos
- Indica quais arquivos estão prontos para commit
- Útil para verificar mudanças antes de fazer commit

**git log:**
- Mostra o histórico de commits
- Exibe informações como autor, data e mensagem de cada commit
- Permite ver a evolução do projeto ao longo do tempo
- Útil para entender quem fez quais alterações e quando

## 7. Propósito de "git add", "git commit" e "git push"

**git add:**
- Adiciona arquivos à área de staging
- Parâmetros comuns:
  - `git add .` (adiciona todos os arquivos)
  - `git add nome_arquivo` (adiciona arquivo específico)

**git commit:**
- Cria um ponto de salvamento das mudanças
- Parâmetros comuns:
  - `git commit -m "mensagem"` (cria commit com mensagem)
  - `git commit -a` (commit de todos os arquivos modificados)

**git push:**
- Envia commits para o repositório remoto
- Parâmetros comuns:
  - `git push origin main` (envia para a branch main)
  - `git push -u origin branch` (configura upstream)

## 8. Diferença entre "git push" e "git pull"

**git push:**
- Envia suas alterações locais para o repositório remoto
- Atualiza o repositório remoto com seus commits

**git pull:**
- Baixa e mescla alterações do repositório remoto
- Combina `git fetch` (baixa alterações) e `git merge` (mescla alterações)
- Mantém seu repositório local atualizado

## 9. Ramificações (Branches)

Branches são linhas independentes de desenvolvimento que permitem:
- Trabalhar em diferentes funcionalidades simultaneamente
- Isolar mudanças experimentais
- Manter o código principal (main/master) estável
- Facilitar o trabalho em equipe
- Gerenciar diferentes versões do software

## 10. Outras Plataformas de Hospedagem

**GitLab:**
- Similar ao GitHub
- Oferece CI/CD integrado
- Permite hospedagem self-hosted
- Foco em DevOps

**Bitbucket:**
- Integração com ferramentas Atlassian
- Bom para equipes pequenas
- Suporte a Mercurial além do Git
- Foco em empresas

**Azure DevOps:**
- Integração com ecossistema Microsoft
- Ferramentas de gerenciamento de projeto
- CI/CD robusto
- Ideal para projetos empresariais

**Comparação com GitHub:**
- GitHub tem maior comunidade
- GitHub Pages é único
- GitHub tem mais integrações
- Outras plataformas podem ter recursos específicos para DevOps 