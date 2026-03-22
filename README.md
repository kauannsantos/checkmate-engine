<div align="center">

```
                       ██████╗██╗  ██╗███████╗ ██████╗██╗  ██╗███╗   ███╗ █████╗ ████████╗███████╗
                       ██╔════╝██║  ██║██╔════╝██╔════╝██║ ██╔╝████╗ ████║██╔══██╗╚══██╔══╝██╔════╝
                       ██║     ███████║█████╗  ██║     █████╔╝ ██╔████╔██║███████║   ██║   █████╗  
                       ██║     ██╔══██║██╔══╝  ██║     ██╔═██╗ ██║╚██╔╝██║██╔══██║   ██║   ██╔══╝  
                       ╚██████╗██║  ██║███████╗╚██████╗██║  ██╗██║ ╚═╝ ██║██║  ██║   ██║   ███████╗
                        ╚═════╝╚═╝  ╚═╝╚══════╝ ╚═════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝   ╚══════╝

                              ███████╗███╗   ██╗ ██████╗ ██╗███╗   ██╗███████╗
                              ██╔════╝████╗  ██║██╔════╝ ██║████╗  ██║██╔════╝
                              █████╗  ██╔██╗ ██║██║  ███╗██║██╔██╗ ██║█████╗  
                              ██╔══╝  ██║╚██╗██║██║   ██║██║██║╚██╗██║██╔══╝  
                              ███████╗██║ ╚████║╚██████╔╝██║██║ ╚████║███████╗
                              ╚══════╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝╚═╝  ╚═══╝╚══════╝
```  

**Motor de xadrez em Java com Inteligência Artificial**

[![Java](https://img.shields.io/badge/Java-C0344D?style=for-the-badge&logo=openjdk&logoColor=white)](https://github.com/kauannsantos/checkmate-engine)
[![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-C0344D?style=for-the-badge&logoColor=white)]()
[![Author](https://img.shields.io/badge/Author-kauannsantos-C0344D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kauannsantos)

</div>

---

## Sobre o projeto

```java
public class CheckmateEngine {

    String linguagem  = "Java";
    String algoritmo  = "Minimax + Alpha-Beta Pruning";
    String objetivo   = "Motor de xadrez com IA para tomada de decisões";
    String propósito  = "Laboratório de evolução técnica em algoritmos e arquitetura";
    boolean em_jogo   = true;

}
```

Checkmate Engine é um motor de xadrez desenvolvido em Java que une **estratégia e inteligência artificial**. Mais do que um jogo, é um laboratório de evolução técnica, construído para aprofundar conhecimentos em algoritmos, estruturas de dados e arquitetura de software.

O motor utiliza **Minimax com poda Alpha-Beta** e **heurísticas de avaliação posicional** para tomar decisões de forma eficiente, simulando o raciocínio de um jogador real.

---

## Como funciona a IA

<table>
  <tr>
    <td valign="top" width="50%">

**Minimax**

Algoritmo de busca em árvore que explora todos os movimentos possíveis até uma profundidade definida, maximizando o resultado para o motor e minimizando para o oponente.

  </td>
  <td valign="top" width="50%">

**Poda Alpha-Beta**

Otimização do Minimax que elimina ramos da árvore que não influenciam o resultado final — reduzindo drasticamente o tempo de processamento sem perder qualidade de decisão.

  </td>
  </tr>
  <tr>
    <td valign="top" width="50%">

**Heurísticas de Avaliação**

Funções que atribuem um valor numérico a cada posição do tabuleiro com base em material, mobilidade e controle de casa — guiando o motor a escolhas estratégicas.

  </td>
  <td valign="top" width="50%">

**Geração de Movimentos**

Lógica completa de movimentação para todas as peças, incluindo roque, en passant e promoção de peão — com validação de xeque e xeque-mate.

  </td>
  </tr>
</table>

---

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,git&theme=dark" />

</div>

<div align="center">

`Java` &nbsp;·&nbsp; `Algoritmos` &nbsp;·&nbsp; `Estruturas de Dados` &nbsp;·&nbsp; `IA Clássica`

</div>

---

## Estrutura do Projeto

```
checkmate-engine/
├── src/
│   ├── board/          # Representação do tabuleiro e estado do jogo
│   ├── pieces/         # Lógica de cada peça (movimento, validação)
│   ├── engine/         # Motor de IA (Minimax, Alpha-Beta, Heurísticas)
│   └── main/           # Entrada do programa
├── README.md
└── .gitignore
```

---

## O que este projeto desenvolveu

- Pensamento algorítmico com busca em árvore e otimização
- Arquitetura orientada a objetos aplicada a um domínio complexo
- Avaliação de trade-offs entre profundidade de busca e performance
- Fundamentos de IA clássica aplicados a um problema real

---

## Autor

<div align="center">

Desenvolvido por [Kauã Santos](https://github.com/kauannsantos)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kauannsantos)
[![Gmail](https://img.shields.io/badge/Gmail-%23D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kauansantsdev@gmail.com)

*"Mais do que um jogo, um laboratório de evolução técnica."*

</div>
