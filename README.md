# 🔍 Caça ao Casal

Jogo de "achar os escondidos" para 4 casais: Yuri & Duda, Álvaro & Andressa,
David & Bianca, Sammya & Luís Gustavo.

## Como funciona

Uma cena de parque é mostrada: um advogado de costas conversando com uma moça
que segura um livro. Clicando nos lugares certos, a foto de cada pessoa aparece:

- 📷 **Câmera no poste** → Yuri
- 🌸 **Uma flor especial (a rosa)** → Duda
- 😁 **Dente do sorriso da moça** → Álvaro
- ✈️ **Avião passando no céu** → Andressa
- 🚜 **Terra no chão** → uma retroescavadeira entra na cena, cava e puxa a foto do David
- 📖 **Livro da moça** → Bianca
- 🐦 **Passarinho no galho** → Sammya
- 👨‍💼 **Cabeça do advogado** → Luís Gustavo

Há um botão de **💡 dicas** que pisca os pontos clicáveis por 3 segundos, um
placar com os 8 nomes e uma comemoração com confete quando todos são achados.

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
