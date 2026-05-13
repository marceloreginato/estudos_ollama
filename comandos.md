# Comandos Ollama

Comandos principais para utilização do Ollama.

```bash
# Ver a versão instalada
ollama --version
```

```bash
# Listar os modelos disponíveis localmente
ollama ls
```

```bash
# Listar os modelos em execução
ollama ps
```

```bash
# Buscar modelos oficiais para baixar
ollama pull modelo
```

```bash
# Rodar o modelo interativamente no terminal
ollama run modelo

# flag --verbose mostra detalhes sobre a resposta
```

```bash
# Perguntar algo sem abrir shell interativo
ollama run modelo "Explique..."
```

```bash
# Parar o modelo
ollama stop modelo
```

```bash
# Apagar um modelo
ollama rm modelo
```




