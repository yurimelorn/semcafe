# 🔍 Caça ao Casal

Jogo de "achar os escondidos" para 4 casais: Yuri & Duda, Álvaro & Andressa,
David & Bianca, Sammya & Luís Gustavo.

## Como funciona

Uma cena de parque é mostrada: um advogado de costas conversando com uma moça
que segura um livro. Cada pessoa está escondida num lugar da cena, e cada uma
tem sua própria animação de revelação:

| Onde clicar | Quem | Animação |
|---|---|---|
| 📷 Câmera no poste | Yuri | A tela vira a **visão da câmera** (outro cenário, estilo CCTV) e você precisa clicar nele lá dentro |
| 🚜 Terra no chão | David | Uma retroescavadeira entra, **cava 3 vezes** e puxa a foto |
| 👨‍💼 Cabeça do advogado | Luís Gustavo | Ele vira um **Hulk**: rasga o paletó, fica verde e gigante (e continua assim na cena!) |
| 🌸 Flor rosa | Duda | Uma **abelha** vem coletar o pólen e sai voando com a foto |
| 📖 Livro da moça | Bianca | O livro abre grande e vai sendo **folheado** até achar a foto |
| ✈️ Avião no céu | Andressa | O avião **vem na direção da tela** e a foto explode em cima de você |
| 😁 Dente do sorriso da moça | Álvaro | Um **brilho** estala no sorriso dela |
| 🕺 Menino do 67 perto da árvore | Sammya | Ele corre pra frente e **dança o SIX SEVEN** |

Ao achar alguém aparece: **"🎉 PARABÉNS! VOCÊ ENCONTROU A/O …! FALTAM X
PESSOAS PARA ENCONTRAR"** com a foto da pessoa. Achou os 8 → confete! 🎊

Extras: placar com os 8 nomes, botão 💡 de dicas (pisca os pontos por 3s) e
botão de reiniciar.

## Celular / tablet

O jogo é feito para jogar **na horizontal**: se o aparelho estiver em pé,
aparece uma tela pedindo para girar o celular.

## Como rodar

É um site estático — basta abrir o `index.html` no navegador, ou servir com:

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

Também funciona direto no GitHub Pages.

## Adicionando as fotos

Coloque as fotos na pasta [`fotos/`](fotos/LEIA-ME.md) com os nomes indicados
(`yuri.jpg`, `duda.jpg`, etc.). Enquanto não houver foto, o jogo mostra a
inicial do nome como espaço reservado.
