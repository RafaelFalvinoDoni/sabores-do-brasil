# Esboços do site "Sabores do Brasil"

**Tema:** gastronomia — pratos típicos das cinco regiões do Brasil.
**Público:** estudantes e curiosos que querem conhecer a culinária brasileira.
**Finalidade:** apresentar pratos por região de forma visual e rápida.
**Cores:** terracota (#b4441c) e creme (#fbf4ea), lembrando panela de barro e farinha.

## Esboço 1 — Computador (a partir de 992px)

```
+--------------------------------------------------------------------+
| [1 MENU] Sabores do Brasil     Início Destaques Pratos Perguntas Mais pratos |
+--------------------------------------------------------------------+
| [2 APRESENTAÇÃO]                                                   |
|  TÍTULO PRINCIPAL                      |  +---------------------+   |
|  Parágrafo sobre o tema                |  |  IMAGEM             |   |
|  [Conhecer os pratos] [Perguntas]      |  |  apresentacao.jpg   |   |
|   (texto à esquerda, imagem à direita - LADO A LADO)            |   |
+--------------------------------------------------------------------+
| [3 DESTAQUES] Carrossel (3 slides, avanço manual)                  |
|  [<]        IMAGEM LARGA destaque-1/2/3.jpg              [>]       |
|             [ legenda: nome do prato + região ]                    |
|             o o o  (indicadores)                                   |
+--------------------------------------------------------------------+
| [4 COLEÇÃO] Pratos típicos                                         |
|  +----------+  +----------+  +----------+   3 cards LADO A LADO    |
|  | imagem   |  | imagem   |  | imagem   |   (col-lg-4)             |
|  | [badge]  |  | [badge]  |  | [badge]  |                          |
|  | título   |  | título   |  | título   |                          |
|  | texto    |  | texto    |  | texto    |                          |
|  | [botão]  |  | [botão]  |  | [botão]  |                          |
|  +----------+  +----------+  +----------+                          |
|          [Anterior] [1] [2] [Próxima]   (paginação)                |
+--------------------------------------------------------------------+
| [5 INFORMAÇÕES] Perguntas frequentes                               |
|  [ALERT: Aviso: receitas variam...]                                |
|  [ Pergunta 1  v ]  (accordion: abre/fecha)                        |
|  [ Pergunta 2  > ]                                                 |
|  [ Pergunta 3  > ]                                                 |
+--------------------------------------------------------------------+
| [6 RODAPÉ] Autoria: Rafael — Fontes das imagens                    |
+--------------------------------------------------------------------+
```

## Esboço 2 — Celular (até 767px)

```
+------------------------+
| [1] Sabores do Brasil ≡|  <- botão ≡ abre/fecha o menu
|   Início               |     (links aparecem EMPILHADOS)
|   Destaques ...        |
+------------------------+
| [2] TÍTULO             |
| Parágrafo              |
| [Conhecer os pratos]   |
| [Perguntas]            |
| +--------------------+ |  <- imagem vai para BAIXO do texto
| | apresentacao.jpg   | |
| +--------------------+ |
+------------------------+
| [3] [<] IMAGEM 4:3 [>] |  <- legenda só com o título
|        o o o           |
+------------------------+
| [4] +--------------+   |
|     | card 1       |   |  <- cards EMPILHADOS (col-12)
|     +--------------+   |
|     | card 2       |   |
|     +--------------+   |
|     | card 3       |   |
|     +--------------+   |
|  [Ant][1][2][Próx]     |
+------------------------+
| [5] ALERT              |
|     Pergunta 1 v       |
|     Pergunta 2 >       |
+------------------------+
| [6] Rodapé             |
+------------------------+
```

Entre 768px e 991px (tablet), os cards ficam 2 por linha (col-md-6) e o terceiro vai para a linha de baixo.

**Função dos controles**
- ≡ (navbar-toggler): abre e fecha o menu no celular.
- Botões da apresentação: levam às seções Pratos e Perguntas.
- [<] [>] do carrossel: trocam o slide manualmente.
- Botões dos cards: levam à pergunta ou seção relacionada.
- Paginação: alterna entre index.html (página 1) e pagina2.html (página 2).
- Perguntas do accordion: mostram e escondem a resposta.
