# Classificador de Nível de Herói

Projeto de classificação de heróis baseado em experiência (XP) usando JavaScript. Este projeto faz parte de uma atividade da DIO e demonstra conceitos básicos de variáveis, operadores, laços de repetição e estruturas de decisão.

## Ferramentas Utilizadas
- **JavaScript**: para a lógica de classificação
- **HTML**: para a interface de entrada
- **VS Code**: como editor de código
- **Git e GitHub**: para versionamento e armazenamento do projeto

## Passo a Passo para Implementação

### 1. Estrutura do Projeto
- Crie um arquivo `index.html` para a interface.
- Crie um arquivo `script.js` para a lógica em JavaScript.

### 2. Código HTML (index.html)
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classificador de Nível de Herói</title>
</head>
<body>
    <h1>Classifique seu Herói</h1>
    <label for="nome">Nome do Herói:</label>
    <input type="text" id="nome">
    
    <label for="xp">Experiência (XP):</label>
    <input type="number" id="xp">
    
    <button onclick="classificarHeroi()">Classificar</button>
    
    <p id="resultado"></p>
    
    <script src="script.js"></script>
</body>
</html>
