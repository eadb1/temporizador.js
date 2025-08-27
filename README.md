# Temporizador

Descrição
--------
Pequeno projeto front-end com HTML, CSS e JavaScript que demonstra um temporizador simples. Arquivos principais:

- `Index.html` - página principal.
- `assets/css/style.css` - estilos.
- `assets/js/main.js` - lógica do relógio/cronômetro.

Objetivo
--------
Fornecer um exemplo prático de manipulação de tempo em JavaScript, eventos de DOM (iniciar, pausar, zerar) e formatação de tempo.

Estrutura de arquivos
---------------------
```
  Index.html
  assets/
    css/
      style.css
    img/
    js/
      main.js
```

Como executar
-------------
Opções para abrir o projeto localmente:

1) Abrir diretamente no navegador
- Abra `Index.html` com duplo clique no Explorador de Arquivos ou arraste para o navegador.

2) Servidor local simples (recomendado para evitar problemas de CORS e testar recursos locais)
- Usando Python (se instalado):

```powershell
python -m http.server 8000
```
Acesse: http://localhost:8000/

- Usando Node (se tiver npm instalado):

```powershell
npx http-server . -p 8000
```

Uso
---
- Botão Iniciar: começa a contar os segundos.
- Botão Pausar: pausa o contador.
- Botão Zerar: para e reseta o contador para `00:00:00`.

Licença
-------
Uso pessoal / educacional. Adapte conforme necessário.

Contatos / Créditos
-------------------
Projeto criado como material didático.


