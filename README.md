# estudos-git

# O que é?
Preencher o que é

# Como surgiu?
Preencher como surgiu

# Principais comandos:

#### Inicializa novo repositório
```
git init
```

#### Exibe status do git
```
git status
```

#### Adiciona ao stage (área temporária)
Adiciona todos os arquivos que não estão sendo rastreados

```
git add .
```

Adiciona ao stage conforme nome do arquivo
```
git add nome-do-arquivo.txt
```

Adiciona ao stage todos arquivos com a extensão informada
```
git add *.txt
```

#### Registra as alterações feitas pelo usuário

```
git commit -m "Sua Mensagem"
```

Adiciona ao stage e faz o commit dos arquivos rastreados
```
git commit -am "Sua Mensagem"
```

#### Exibe as mudanças
```
git diff
```

#### Envias as mudanças para o servidor

```
git push
git push <nome-remote> <nome-branch>
git push origin main
```
 

# Referências

[Guia do Git](https://rogerdudler.github.io/git-guide/index.pt_BR.html)