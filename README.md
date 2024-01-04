# RESUMOS Git e Github by Edvando Simplício

Repositório onde armazeno resumos de Git e Github como uma área de estudos.

## 📚 Documentação
- [Dicumentação Git](https://git-scm.com/docs)
- [Dicumentação GitHub](https://docs.github.com/pt)

## 💻 Resumos das Aulas

| Aulas | Resumos |
| ----- | ------- |
| Aula 01 | [Resumo]() |
| Aula 02 | [Resumo]() |

## Estados GIT
- Untracked: arquivo inrastreável.
- Unmodified: arquivo imodificavél, estável e rastreável.
- Modified: arquivo modificado e não commitado.

## Códigos GIT e suas funcionalidades

```

git init: Inicia o projeto em uma pasta no formato .git

git status: Verifica o estado atual do arquivo e que tipo de status ele permanece.

git add . ou nome do arquivo: Adiciona todas as alterações no modo Staged(preparação) e fica pronto para ser commitado.

git diff / git diff --staged: Visualiza linhas de códigos adicionadas e modificadas.
git commit -m"titulo do commit": Commita todas as alterações feitas nos arquivos da pasta do projeto .git

git log: visualiza todo histórico de commits realizado no projeto .git

git log --oneline

git restore / git restore --staged/git reset: desfaz mudanças do arquivo, basicamente restaura versões anteriores
obs: copie a hash do commit obtido através do comando "git log" e cole junto com o comando atual.

git remote: informações sobre repositório remoto.

git pull: junta alterações/commits da equipe para o seu repositório local.

git push origin -m: Upa todos os commits para o repositório remoto e branch nomeada.

git fetch / git diff: informa histórico de commits da equipe(seus e de outros).

git branch + "titulo da branch": cria-se uma nova branch.

git checkout + "titulo da branch": aponta para a branch indicada e sai da antiga.

git merge + "titulo da branch": junta os commits de uma branch a outra.
obs: utilizar o "git checkout" para selecionar a branch da qual se deseja unificar.

```

## 🔎 Referências
- [Digital Inovation One](https://www.dio.me/)