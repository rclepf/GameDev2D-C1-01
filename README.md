# GameDev2D-C1-01 — Desmontando o castelo

**Jornada GameDev 2D · SENAI CTTI**
C1 · Design de Jogos 2D: da Ideia ao GDD · Site 1 de 3 · Aula inicial (sábado, presencial)

Explicação do professor e introdução ao tema: a jornada, o jogo modelo jogável no navegador, elementos formais, MDA, loop central e GDD de uma página. Termina com a Atividade C1.1 (GDD do castelo).

🔗 **Site publicado:** https://rclepf.github.io/GameDev2D-C1-01/

## Conteúdo

| Seção | Tema |
|---|---|
| Sala 01 | A jornada em oito portas |
| Sala 02 | Jogue como designer |
| Sala 03 | Os elementos formais |
| Sala 04 | MDA: da regra à sensação |
| Sala 05 | O loop central |
| Sala 06 | O GDD de uma página |
| Sala 07 | Engenharia reversa: o GDD do castelo |
| Sala 08 | Onde estamos na jornada |

## Estrutura do repositório

- `index.html` — a página do site
- `trilha.css` — identidade visual da jornada (tema “castelo”, comum a todos os sites)
- `trilha.js` — realce de código GDScript e botão “copiar”
- `img/` — sprites, telas do jogo modelo e ícones
- `jogar/` — jogo modelo *O Rei e os Porcos* exportado para Web (Godot 4)
- `Modelo_GDD_1_Pagina.docx` — modelo de GDD da jornada

## Publicar no GitHub Pages

1. Crie o repositório público `GameDev2D-C1-01` na conta `rclepf`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório (o `index.html` precisa ficar na raiz).
3. Em **Settings → Pages**, escolha **Deploy from a branch → `main` / `(root)`** e salve.
4. Em 1 a 2 minutos o site fica disponível em `https://rclepf.github.io/GameDev2D-C1-01/`.

## Testar no computador antes de publicar

O jogo da pasta `jogar/` **não abre com duplo clique** no `index.html` (o navegador bloqueia o carregamento de arquivos locais e mostra *Failed to fetch*). Sirva a pasta por um servidor local:

```bash
python -m http.server 8000
```

e abra `http://localhost:8000/` (site) ou `http://localhost:8000/jogar/` (jogo). No VS Code, a extensão **Live Server** faz o mesmo.

> O arquivo `jogar/index.wasm` tem cerca de 44 MB. O upload pelo navegador do GitHub aceita até 25 MB por arquivo: envie o repositório pelo **GitHub Desktop** ou pela linha de comando.

## Créditos

- Material didático: Rodolfo Clepf de Carvalho — SENAI CTTI (FIEMG), Belo Horizonte.
- Jogo modelo *O Rei e os Porcos*: desenvolvido em Godot 4 para a jornada.
- Artes e áudios do jogo modelo: pacote da série *“Criando um jogo DO ZERO com Construct 3”* (Daniel Valadares, canal Gamecraft).
- Fontes: Atkinson Hyperlegible, Bricolage Grotesque e JetBrains Mono (Google Fonts).
- Materiais externos citados nos sites pertencem aos seus autores e instituições.
