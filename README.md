# 🍇 Simulação de Lançamento Oblíquo Interativo

Este projeto web permite simular o lançamento obíquo de objetos utilizando conceitos da física clássica, como velocidade inicial, ângulo e gravidade. Ele foi desenvolvido com HTML, CSS e JavaScript puro (vanilla JS), e é voltado para fins educacionais.

---

## 🚀 Demonstração

---

## 📅 Funcionalidades

 Selecionar o tipo de objeto a ser lançado (bola, pedra, flecha);
 Informar massa, velocidade inicial e ângulo de lançamento;
 Prever a distância de queda;
 Ver simulação animada em tempo real no canvas;
 Observar parâmetros dinâmicos como

   Tempo de voo
   Velocidade atual
   Distância percorrida
   Altura máxima
 Obter feedback sobre a precisão da previsão feita.

---

## 🔧 Tecnologias Utilizadas

 HTML5
 CSS3 (com variáveis e responsividade)
 JavaScript (cálculos físicos e animação)
 Canvas API

---

## 🌎 Como Usar

1. Clone o repositório

```bash
git clone httpsgithub.comgustaawnsimulacao-lancamento-obliquo.git
```

2. Navegue até a pasta do projeto

```bash
cd nome-do-repositorio
```

3. Abra o arquivo `simulacao-lancamento-obliquo.html` em qualquer navegador moderno.

---

## 📊 Cálculos Utilizados

 Altura máxima (h) $h = frac{(v_0 cdot sin(theta))^2}{2g}$
 Tempo de voo (t) $t = frac{2 cdot v_0 cdot sin(theta)}{g}$
 Alcance (x) $x = v_0 cdot cos(theta) cdot t$
 Posição (x, y)

   $x = v_0 cdot cos(theta) cdot t$
   $y = v_0 cdot sin(theta) cdot t - frac{1}{2}gt^2$

---

## 🌐 Acessibilidade

 Utiliza atributos ARIA como `aria-label`, `aria-describedby` e `aria-live`;
 Elementos responsivos para diferentes dispositivos;
 Contraste alto e fonte legível.

---

## 🔄 Melhorias Futuras

 Simulação com resistência do ar;
 Vários tipos de terrenos e cenários;
 Modo noturnodiurno dinâmico;
 Exportar dados em CSVJSON;
 Integração com biblioteca de gráficos para gerar curva da trajetória.

---

## 👤 Autor

Gustavo Munhoz Lima
Estudante e desenvolvedor iniciante apaixonado por educação, jogos e ciência.
[LinkedIn](httpswww.linkedin.comingustaawn)  [Instagram](httpswww.instagram.comgustaawn)  [GitHub](httpsgithub.comGustaawn)

---

## ✉️ Contribuições

Contribuições são bem-vindas! Sinta-se livre para abrir uma issue ou enviar um pull request.

---

## ✉️ Licença

Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
