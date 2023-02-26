## Repositório Local

### Criar novo repositório

```
git init
```

### Verificar estado dos arquivos/diretórios

```
git status
```

### Adicionar arquivo/diretório (staged area)

##### Adicionar um arquivo em específico

```
git add meu_arquivo.txt
```

##### Adicionar um diretório em específico

```
git add meu_diretorio
```

##### Adicionar todos os arquivos/diretórios

```
git add .	
```

##### Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)

```
git add -f arquivo_no_gitignore.txt
```

### Comitar arquivo/diretório

##### Comitar um arquivo

```
git commit meu_arquivo.txt
```

##### Comitar vários arquivos

```
git commit meu_arquivo.txt meu_outro_arquivo.txt
```

##### Comitar informando mensagem

```
git commit meuarquivo.txt -m "minha mensagem de commit"
```

### Remover arquivo/diretório

##### Remover arquivo

```
git rm meu_arquivo.txt
```

##### Remover diretório

```
git rm -r diretorio
```