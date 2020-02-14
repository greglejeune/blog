---
layout: article
title: Basou explique son thinking process en HU 5k€
subtitle: Basou en Janvier 2020
img: basou.jpg
video: Basou_NL5K.mp4
categories: poker
---

<div class="body">
  
  <p>Pour sa "première" vidéo depuis son retour dans la team, Basou vous partage une méthodologie de travail qui vous permettra de suivre en détail son thinking process sur deux spots qu'il a disputé sur les tables de head's up NL5000 de PartyPoker.com.</p>
  
  <div class="video">
    <video id="player" controls>
        <source src="http://videos.poker-academie.com/videos/{{ page.video }}" type="video/mp4">
    </video>
  </div>
  
  <h2>Thinking Process</h2>
  
  <div class="mermaid">
    graph LR
      Profil --> Strategie
      Strategie --> GTO
      Strategie --> GTNO
      Profil --> Range
      Range --> R[Range Advantage]
      Flop --> R[Range Advantage]
      Sizing --> S[Strategie]
      Reponse --> Spot
      Reponse --> Main
      Main --> Equite
      Main --> Bloker
      Equite --> Deep
      Bloker --> SS
      style Profil fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
      style Flop fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
      style Sizing fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
      style Strategie fill:#d5e8d4,stroke:#82b366,stroke-width:1px
      style Reponse fill:#d5e8d4,stroke:#82b366,stroke-width:1px
      style Range fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Spot fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Main fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Equite fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Bloker fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Deep fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style SS fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style GTO fill:#f8cecc,stroke:#b85450,stroke-width:1px
      style GTNO fill:#f8cecc,stroke:#b85450,stroke-width:1px
      style R fill:#f8cecc,stroke:#b85450,stroke-width:1px
      style S fill:#f8cecc,stroke:#b85450,stroke-width:1px
  </div>
  
  <figure class="image-center">
    <figcaption>
      BTN opens and BB calls.
    </figcaption>
    <img src="/blog/img/2020-01-23-1.png">
    <figcaption>
      The BB checks and the BTN bets 1/3 pot.
    </figcaption>
  </figure>

  
  <p>Dans ce spot, le bas de range est 95o. Vilain a ici toutes ses OP et de meilleurs 9 ( car nous allons 3bet J9s, T9s, 98s, A9o, K9s, Q9s ). Il a en plus la position et de bonne hauteur A. Il est donc favoris dans ce coup, il a l'avantage de range et la position, il devrait souvent miser.</p>

  <p><span>Le fréquence et le sizing sont des choses souvent liées, plus la fréquence est importante, plus le sizing sera faible.</span> Dans des situations avec un gros avantage de range ( AKQ, KQT, ... ) on peut utiliser de gros sizing mais toujours avec une fréquence moindre.</p>
  
  <p>Ici il va vouloir protéger son équité et devrait faire une petit sizing. Il fait 1/3p, ce qui fait sens. Ca veut dire qu'il va avoir une frequence de bet importante. Comme il va avoir une grosse fréquence, on va devoir défendre beaucoup.</p>
  
  <table class="board">
    <tbody>
      <tr>
        <td rowspan="2">A</td>
        <td rowspan="2">K</td>
        <td rowspan="2">Q</td>
        <td class="basel ingame" rowspan="2">J</td>
        <td class="ingame" rowspan="2">T</td>
        <td class="flop top">9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 10px;"></td>
        <td class="ingame" rowspan="2">8</td>
        <td class="ingame" rowspan="2">7</td>
        <td class="ingame" rowspan="2">6</td>
        <td class="flop ingame" rowspan="2">5 <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 10px;"></td>
        <td class="ingame" rowspan="2">4</td>
        <td class="baser ingame" rowspan="2">3</td>
        <td rowspan="2">2</td>
      </tr>
      <tr>
        <td class="flop down">9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8" style="width: 10px;"></td>
      </tr>
    </tbody>
  </table>
  
  <div>
    <svg xmlns="http://www.w3.org/2000/svg" width="432" height="54">
      <g data-name="Groupe 42">
        <g data-name="Groupe 27" opacity=".502">
          <g data-name="Groupe 14" transform="translate(334 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="9" transform="translate(394 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">9</tspan>
          </text>
        </g>
        <g data-name="Groupe 28" opacity=".502">
          <g data-name="Groupe 14" transform="translate(262 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text transform="translate(322 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-18.936" y="0">T</tspan>
          </text>
        </g>
        <g data-name="Groupe 30" opacity=".502">
          <g data-name="Groupe 14" transform="translate(478 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="7" transform="translate(538 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">7</tspan>
          </text>
        </g>
        <g data-name="Groupe 32" opacity=".502">
          <g data-name="Groupe 14" transform="translate(406 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="8" transform="translate(466 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">8</tspan>
          </text>
        </g>
        <g data-name="Groupe 33" opacity=".502">
          <g data-name="Groupe 14" transform="translate(190 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text transform="translate(250 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-15.5" y="0">J</tspan>
          </text>
        </g>
        <g data-name="Groupe 34" opacity=".502">
          <g data-name="Groupe 14" transform="translate(118 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text transform="translate(178 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-24.113" y="0">Q</tspan>
          </text>
        </g>
        <g data-name="Groupe 35" opacity=".502">
          <g data-name="Groupe 14" transform="translate(46 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text transform="translate(106 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-20.677" y="0">K</tspan>
          </text>
        </g>
        <g data-name="Groupe 36" opacity=".502">
          <g data-name="Groupe 14" transform="translate(-26 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text transform="translate(34 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-20.677" y="0">A</tspan>
          </text>
        </g>
        <g data-name="Groupe 37" opacity=".502">
          <g data-name="Groupe 14" transform="translate(550 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="6" transform="translate(610 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">6</tspan>
          </text>
        </g>
        <g data-name="Groupe 38" opacity=".502">
          <g data-name="Groupe 14" transform="translate(622 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="5" transform="translate(682 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">5</tspan>
          </text>
        </g>
        <g data-name="Groupe 39" opacity=".502">
          <g data-name="Groupe 14" transform="translate(694 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="4" transform="translate(754 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">4</tspan>
          </text>
        </g>
        <g data-name="Groupe 40" opacity=".502">
          <g data-name="Groupe 14" transform="translate(766 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="3" transform="translate(826 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">3</tspan>
          </text>
        </g>
        <g data-name="Groupe 41" opacity=".502">
          <g data-name="Groupe 14" transform="translate(838 -509)">
            <rect data-name="Rectangle 8" width="67" height="101" rx="8" transform="translate(26 514)" fill="#bbbcbf" />
            <rect data-name="Rectangle 7" width="67" height="102" rx="8" transform="translate(26 509)" fill="#fff" />
          </g><text data-name="2" transform="translate(898 52)" fill="#515262" font-size="62" font-family="Helvetica">
            <tspan x="-17.241" y="0">2</tspan>
          </text>
        </g>
      </g>
    </svg>
  </div>
  
  <p>Dans ce spot on va beaucoup FLOAT, des hauteurs A, des backdoors FD + OC/5 ( J8cc, Kx ). On va vouloir avoir aussi une grosse stratégie de X/R, pour value des 9 mais aussi protéger des 5 ( Kicker faible + backdoor ).</p>
  
  <p>On va vouloir aussi anticiper la TURN, car comme on va beaucoup FLOAT, on va souvent subir une deuxième bet car c'est une bon board à second barrel. Nous n'avons jamais une range très forte, il va donc pouvoir value thin et nous mettre beaucoup de pression avec ses bluffs. Il va donc falloir que l'on défende cette range.</p>
  
  <p>On va donc X/R pas mal, on va donc faire un petit sizing, un 3.5x surement.</p>
  
  <p>Ensuite on va regarder la <span>propriété de notre main</span> pour sélectionner nos combos.</p>
  
  <p>Les premières mains bonne à X/R ce sont celles avec le plus d'équité vers les NUTS. Dans ce spot on fera souvent face à des 9x, 5x, hauteur A, on va donc vouloir prendre des mains avec des cartes au dessus du 5 et avec des backdoors FD ou SD.</p>
  
  <p>Sur certains board, on n'a pas assez de mains à équité alors on va prendre des mains avec des blockers. Mais ici ce n'est pas le cas.</p>
  
  <p><span>On utilise les blockers quand le jeu est short par contre plus le jeu est deep, plus on va vouloir chercher de l'équité.</span></p>
  
  <h2>FLOP : 9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 15px;"> 9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8" style="width: 15px;"> 5 <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 15px;"></h2>
  
  <p>Si on se plonge plus en detail dans ce coup, on va vouloir X/R nos 9 mais on va aussi vouloir X/C pour avoir une range de X/R en value à la TURN. Comme on va call avec beaucoup de backdoor, quand elles rentreront on voudra aussi X/R ( J6cc ).</p>
  
  <p>Avec 9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 10px;">&nbsp;7 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8" style="width: 10px;">, on va choisir de X/C au flop car avec ce kicker on va jamais faire de gros setup. De plus on bloque la range de call de vilain A7s, K7s, 87s, 76s, 87o, 76o.</p>
  
  <h2>TURN : 4 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 15px;"></h2>
  
  <p>Vilain fait 1/2p. Il devrait value thin ici vu notre range. Il ne fait pas trop petit pour ne pas nous faciliter la vie et pas trop gros pour pouvoir value thin et protéger sa main.</p>
  
  <p>La TURN nous amène des bluffs, on peut alors X/R nos mains de value. On devrait sizer proche des 4x car on se polarise ici.</p>
  
  <h2>RIVER : J <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 15px;"></h2>
  
  <p>On veut value encore nos 9, il va donc falloir trouver des bluffs. 76 sans <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 10px;"> serait un bon bluff et on devrait give up nos <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 10px;"> car on a envie des les faire folder à la RIVER.</p>
  
  <figure class="image-center">
    <figcaption>
      BTN opens and BB calls.
    </figcaption>
    <img src="/blog/img/2020-01-23-2.png">
    <figcaption>
      The BB checks and the BTN checks.
    </figcaption>
  </figure>
  
  <p>BTN check ce board.</p>
  
  <p>Il est capé ici car il devrait beaucoup cbet cette texture de board. Il devrait cbet ses Nuts, ses 7x &amp; 6x pour protection, il pourrait bet des 8x car ça bloque la calling range.</p>
  
  <p>Donc sur le 8 à la TURN, sa range n'est pas très forte. On va donc avoir une stratégie agressive. Soit avec un petit sizing à haute fréquence pour protection 6x, 7x car comme il est capé il ne devrait pas nous raise souvent. Soit avec un gros sizing car il est capé et on veut lui mettre beaucoup de pression, on utilisera ce sizing avec nos Nuts et nos 63 car on ne bloque pas la range de call, on utilise la propriété de notre main, mais aussi avec nos bon 8x.</p>
  
  <p>Dans ce spot on va donc beaucoup bluffer, sauf nos hauteur A qui ont de la SD value. Avec 4x, 5x par exemple. Avec 4x on pourra sizer petit deux fois pour target les draw (9x). Par contre avec une a grosse équité, pas besoin de faire petit, car si on est call on peut encore améliorer.</p>
  
  <p>Il y a donc deux réponses possibles à une range capée, soit un gros sizing pour mettre de la pression sur sa range, soit un blocking bet pour value très large. Attention, il faut block bet aussi avec des mains fortes. Ici on peut le faire avec 9T, mais il serait mieux de ne pas avoir de <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 10px;">&nbsp;pour de temps en temps induce des raises.</p>

</div>

<script>mermaid.initialize({startOnLoad:true});</script>
