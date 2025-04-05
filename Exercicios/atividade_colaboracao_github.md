# Guia de Colaboração no GitHub - Atividade Prática

## Passo 1: Criar o Repositório Original

### 1.1 Acessar o GitHub
1. Abra seu navegador
2. Acesse [github.com](https://github.com)
3. Faça login na sua conta
   - Se não tiver conta, clique em "Sign up" e crie uma

### 1.2 Criar Novo Repositório
1. Clique no botão "+" no canto superior direito
2. Selecione "New repository"
3. No campo "Repository name", digite: `aula-git-seunome`
4. Em "Description", adicione uma breve descrição
5. Selecione "Public"
6. Marque a opção "Add a README file"
7. Clique em "Create repository"

### 1.3 Editar o README.md
1. No repositório criado, clique no arquivo `README.md`
2. Clique no ícone de lápis (Edit this file)
3. Adicione uma descrição do projeto
4. Clique em "Commit changes"

### 1.4 Compartilhar o Link
1. Copie a URL do seu repositório da barra de endereços
2. Compartilhe com seu colega

## Passo 2: Colaboração (Para o Colega)

### 2.1 Fazer Fork do Repositório
1. Acesse o link compartilhado
2. Clique no botão "Fork" no canto superior direito
3. Aguarde a criação da cópia em sua conta

### 2.2 Clonar o Repositório
1. Abra o terminal/prompt de comando
2. Navegue até a pasta desejada:
   ```bash
   cd caminho/para/sua/pasta
   ```
3. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/aula-git-seunome.git
   ```
4. Entre na pasta do projeto:
   ```bash
   cd aula-git-seunome
   ```

### 2.3 Criar Nova Branch
1. Crie e mude para uma nova branch:
   ```bash
   git checkout -b melhoria-readme
   ```

### 2.4 Fazer Alterações
1. Abra o arquivo README.md em seu editor
2. Faça as alterações desejadas
3. Salve o arquivo

### 2.5 Commit e Push
1. Adicione as alterações:
   ```bash
   git add README.md
   ```
2. Faça o commit:
   ```bash
   git commit -m "Melhoria no README"
   ```
3. Envie para o GitHub:
   ```bash
   git push origin melhoria-readme
   ```

### 2.6 Criar Pull Request
1. Acesse seu repositório forkado no GitHub
2. Clique em "Pull requests"
3. Clique em "New pull request"
4. Selecione:
   - Base repository: repositório original do colega
   - Base: main
   - Head repository: seu fork
   - Compare: melhoria-readme
5. Clique em "Create pull request"
6. Adicione um título e descrição
7. Clique em "Create pull request"

## Passo 3: Revisão (Para o Dono Original)

### 3.1 Revisar Pull Request
1. Acesse seu repositório original
2. Clique na aba "Pull requests"
3. Clique no PR criado pelo colega
4. Revise as alterações

### 3.2 Aprovar e Mesclar
1. Se tudo estiver correto, clique em "Merge pull request"
2. Confirme a mesclagem
3. Opcionalmente, delete a branch após a mesclagem

## Dicas Importantes:
- Sempre mantenha seu repositório local atualizado
- Use mensagens de commit descritivas
- Revise cuidadosamente as alterações antes de mesclar
- Mantenha uma boa comunicação com seu colega durante o processo 