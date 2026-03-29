Aqui está seu conteúdo organizado em formato de **README.md para GitHub**, mantendo **todas as informações iguais**, só estruturadas 👇

---

# 📘 Curso de Git e GitHub - Udemy (Matheus Battisti)

## 📌 Comandos básicos

* `git init` - cria um novo repositório local no diretório atual
* `git clone` - copia o repositório remoto existente para a sua máquina local
* `git status` - mostra o estado do seu diretório de trabalho e da área de staging
* `git add` - adiciona alterações do diretório de trabalho à área de staging
* `git commit` - registra as alterações da área de staging como um novo snapshot no repositório local
* `git push` - envia as alterações locais para o repositório remoto
* `git pull` - baixa os commits mais recentes do repositório remoto e mescla com a branch local
* `git branch` - lista, cria, renomeia ou exclui branches
* `git checkout` - muda para outra branch ou commit
* `git merge` - combina alterações de uma branch em outra
* `git diff` - mostra diferenças entre commits, branches ou arquivos
* `git log` - mostra o histórico de commits

---

## 📂 Clonando um projeto

No bash:

```bash
git clone
cd nome-da-pasta
code .
```

---

## 🆕 Criando repositórios

```bash
git init
git status
```

---

## 🚀 Enviar repositório para o GitHub

```bash
cd "nome da pasta"
git init
git status
git add "nome do arquivo"
git commit -m "nome da mudança"
git status
```

### Criar branch master

```bash
git branch -M master
git remote add origin "URL origem da pasta"
git push -u origin master
```

---

## 🔄 Verificar modificações

```bash
git status
git add .
git commit -a -m "descrever a alteração"
git status
```

Ou para um arquivo específico:

```bash
git commit "nome do arquivo" -m "Descrever alteração"
```

---

## 📤 Enviando código

```bash
git push
```

---

## 📥 Recebendo alterações

```bash
git pull
```

---

## 📥 Clonando repositórios (forma prática)

* Copiar link HTTPS
* Criar nova pasta no VS Code

```bash
git clone . 
```

---

## 🗑️ Removendo arquivos

```bash
git rm nome-do-arquivo
git status
git commit
git push
git pull
```

---

## 📜 Log de alterações

```bash
git log
```

---

## ✏️ Renomeando arquivos

```bash
git mv "nome errado" "nome correto"
```

---

## ↩️ Desfazendo alterações

```bash
git checkout "nome do arquivo"
```

---

## 🚫 Ignorando arquivos (.gitignore)

Criar arquivo `.gitignore` e adicionar nomes dos arquivos que não devem subir.

---

## 🔄 Resetando branch

```bash
git reset --hard origin/master
```

---

# 🌿 Trabalhando com Branches

## Visualizar branches

```bash
git branch
```

## Criar branch

```bash
git branch nome
```

## Deletar branch

```bash
git branch -d nome
```

## Mudar de branch

```bash
git checkout -b nome-da-branch
```

## Unir branches

```bash
git merge nome-da-branch
```

---

# 📦 Stash

## Salvar alterações temporárias

```bash
git stash
```

## Listar stash

```bash
git stash list
```

## Recuperar stash

```bash
git stash nome
```

## Remover stash

```bash
git stash clear
git stash drop nome
```

---

# 🏷️ Tags

## Criar tag

```bash
git tag -a nome -m "mensagem"
```

## Ver tag

```bash
git show nome
```

## Trocar tag

```bash
git checkout nome
```

## Enviar tags

```bash
git push origin nome
git push origin --tags
```

---

# 🔍 Outros comandos úteis

## Buscar branches remotas

```bash
git fetch
```

## Atualizar repositório

```bash
git pull
```

## Exibir detalhes

```bash
git show
```

## Diferença entre branches

```bash
git diff
```

## Log resumido

```bash
git shortlog
```

## Limpeza

```bash
git clean
git gc
```

## Verificar integridade

```bash
git fsck
```

## Histórico completo de ações

```bash
git reflog
```

## Gerar arquivo do repositório

```bash
git archive --format zip --output master_files.zip master
```

---

# 📌 GitHub (Interface)

* **Issues** → criar tarefas e bugs
* **Actions** → automações e deploy
* **Projects** → quadro Kanban
* **Wiki** → documentação extensa
* **Insights** → métricas do projeto

---

# 📝 Markdown (README)

## Títulos

```md
# H1
## H2
### H3
```

## Ênfase

```md
**negrito**
*itálico*
```

## Listas

```md
* item (não ordenada)

1. item (ordenada)
```

## Imagens

```md
![Texto](link)
```

## Links

```md
[Texto](link)
```



