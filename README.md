## Configuração Inicial

```bash
git init  # Inicializa um novo repositório Git local.
```

```bash
git remote add origin <url>  # Conecta seu repositório local a um repositório remoto.
```

## Trabalhando com Alterações

```bash
git status  # Verifica o estado atual do seu repositório.
```

```bash
git add <local-do-arquivo>  # Adiciona as mudanças atuais do arquivo indicado ao índice para commit.
```

```bash
git add .  # Adiciona todas as mudanças atuais ao índice para commit.
```

```bash
git diff  # Mostra as diferenças entre arquivos não rastreados e o índice.
```

```bash
git commit -m "<mensagem>"  # Registra as mudanças no repositório com uma mensagem de commit.
```

```bash
git reset --hard HEAD  # Reverte o diretório de trabalho e o índice para o estado do último commit.
```

## Ramificação e Fusão

```bash
git branch <nome-da-branch>  # Cria uma nova branch.
```

```bash
git branch -M main  # Renomeia a branch atual para "main".
```

```bash
git branch  # Lista todas as branches locais.
```

```bash
git switch <nome-da-branch>  # Muda para a branch especificada.
```

```bash
git merge <nome-da-branch>  # Funde a branch especificada na branch atual.
```

```bash
git branch -D <nome-da-branch>  # Exclui a branch especificada.
```

```bash
git cherry-pick <id-do-commit>  # Aplica as alterações de um commit específico na branch atual.
```

## Colaboração

```bash
git push -u origin main  # Envia os commits locais para o repositório remoto (main) pela primeira vez.
```

```bash
git pull  # Puxa e mescla alterações do repositório remoto para o repositório local.
```

## Logs e Histórico

```bash
git log  # Mostra o histórico de commits.
```

```bash
git log --oneline  # Mostra o histórico de commits em uma linha por commit.
```

```bash
git log --graph  # Mostra o histórico de commits em formato gráfico.
```

## Tags

```bash
git tag <nome-da-tag>  # Cria uma tag leve na versão atual.
```

```bash
git tag -a <nome-da-tag> -m "<mensagem>"  # Cria uma tag anotada com uma mensagem associada.
```

```bash
git tag -d <nome-da-tag>  # Exclui a tag especificada localmente.
```

```bash
git push origin --tags  # Envia todas as tags locais para o repositório remoto.
```