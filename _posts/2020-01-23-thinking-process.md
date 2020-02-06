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
  
  <div class="mermaid">
    graph LR
      Profil --> Strategie
      Strategie --> GTO
      Strategie --> GTNO
      Profil --> Range
      Range --> R[Range Advantage]
      Flop --> R[Range Advantage]
      Sizing --> S[Strategie]
      style Profil fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
      style Flop fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
      style Sizing fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
  </div>
  
  <figure class="image-center">
    <figcaption>
      HU Pot - The BTN open and the BB calls.
    </figcaption>
    <img src="/blog/img/picture.png">
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

</div>

<script>mermaid.initialize({startOnLoad:true});</script>
