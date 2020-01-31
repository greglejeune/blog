---
layout: article
title: Basou explique son thinking process en HU 5k€
subtitle: Basou en Janvier 2020
img: basou.jpg
video: Basou_NL5K.mp4
---

<div class="body">
  
  <p>Pour sa "première" vidéo depuis son retour dans la team, Basou vous partage une méthodologie de travail qui vous permettra de suivre en détail son thinking process sur deux spots qu'il a disputé sur les tables de head's up NL5000 de PartyPoker.com.</p>
  
  <div class="video">
    <video id="player" controls>
        <source src="http://videos.poker-academie.com/videos/{{ page.video }}" type="video/mp4">
    </video>
  </div>
  
  <h2>Thinking process</h2>
  
  <div class="mermaid">
    graph LR
      A[Profil Adversaire] --> S[Stratégie à adopter]
      S --> GTO
      S --> GTNO
      GTO --> N[Notre Range]
      GTNO --> N
      A --> R[Sa range PreFlop]
      Flop --> D[Range Advantage]
      N --> D
      R --> D
      D --> C[Sa Stratégie]
      Z[Sizing] --> C
      style A fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style Z fill:#f5f5f5,stroke:#666666,stroke-width:1px
      style D fill:#f8cecc,stroke:#b85450,stroke-width:1px
      style C fill:#f8cecc,stroke:#b85450,stroke-width:1px
      style S fill:#d5e8d4,stroke:#82b366,stroke-width:1px
      style Flop fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
  </div>
  
  <p>On commence le processus par l'adversaire. Quel est son profil ? Doit on jouer GTO contre lui ou exploitant ? Cela va nous permettre de définir sa range et notre range dans ce spot.</p>
  <p>
    Ici c'est un joueur de NL5K, on va donc jouer équilibré. Ici il ouvre presque 100% des mains et nous on a 95o comme bas de range. </p>
  <blockquote>
    9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" style="width: 20px;">&nbsp;9 <img src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8" style="width: 20px;">&nbsp;5 <img src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" style="width: 20px;">
  </blockquote>
  <p>Dans ce spot, nous avons autant de 5 que lui. Par contre nous avons moins de 9 car nous allons 3bet les 98s, T9s, J9s et quelques fois les A9o, K9s, Q9s. Nous n'aurons aussi presque pas d'OP.</p>
  <p>Nous avons tous les deux une range large, il a ses OP et plus de 9, il est donc favoris dans ce coup grâce à son avantage de range. Il a donc intérêt à miser, il va donc avoir une fréquence importante de CBET.</p>
  <blockquote>
    La fréquence et le sizing sont liés, si on bet à haute fréquence, on va réduire notre sizing sauf si on a un énorme range advantage.
    <br/>
    Exemple : Sur AKQ, KQT, on peut OB dès le flop a cause de notre avantage de NUTS.
  </blockquote>
  <p>Ici il a donc envie de protéger son équité mais pas de miser cher. Il fait 1/3p, il va donc avoir une fréquence de CBET importante, voila donc sa stratégie dans ce spot.</p>
  <p>Comme il va beaucoup miser, nous allons devoir défendre énormément. Nous allons pouvoir défendre en CALL ou en RAISE.</p>
  <p>Si il mise beaucoup, nous allons devoir défendre beaucoup, soit en CALL soit en RAISE.</p>
  <p>Ici on va FLOAT avec nos Ahi, nos backdoor FD avec OC/5 (J8s, Kxs, Kxo). Sur un petit sizing on va aussi avoir envie d'avoir une stratégie de X/R, avec le 9 mais aussi avec un 5 (mauvais kicker + backdoor) en protection.</p>
  <p>Il faut aussi réflechir à la STREET suivante, car c'est un bon spot à 2 BARREL car nous allons beaucoup FLOAT (OC, Ahi, ...) et nous n'avons donc jamais une range très forte ici.</p>
  
  <p>Ici comme on va X/R beaucoup, on va faire petit (3.5x), mais sur K72r (on a plus de DP, donc on fera 4-5x).</p>
  <p>Maintenant on va regarder la propriété de notre main (équité &amp; blocker).</p>
  <p>Ce qui est bon a X/R, ce sont les mains avec le plus d'équité vers les NUTS.</p>
  <p>Ici vs X/R, on va faire face à un Ahi, 5x, 9x, donc on peut deja prendre des mains &gt; 5.</p>
  <p>Ensuite on va pouvoir prendre, 97,67,T8s,J8s, backdoor SD+FD.</p>
  <p>Sur certain board sans équité, on va pouvoir prendre des mains avec des blockers (8,7,6).</p>
  <p>On utilise surtout les blockers en SS et plus l'équité quand on est deep.</p>
  <p>(17:00)</p>

  
</div>

<script>mermaid.initialize({startOnLoad:true});</script>
