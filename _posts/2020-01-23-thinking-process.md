---
layout: post
title: "Basou explique son thinking process en HU 5k€"
---

<header>
  <h1>
    Basou explique son thinking process en HU 5k€
  </h1>
</header>
<div class="content">
  <p>
    Pour sa "première" vidéo depuis son retour dans la team, Basou vous partage une méthodologie de travail qui vous permettra de suivre en détail son thinking process sur deux spots qu'il a disputé sur les tables de head's up NL5000 de PartyPoker.com.
  </p>
  <div class="video-container">
    <video id="player" controls>
      <source src="http://videos.poker-academie.com/videos/Basou_NL5K.mp4" type="video/mp4" />
    </video>
  </div>
  <h3>
    <a class="link" href="#" onclick="document.querySelector('#player').currentTime=210">
      <svg viewBox="0 0 24 24">
        <path d="M4 3h16a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5c0-1.1.9-2 2-2zm0 2v2h2V5H4zm0 4v2h2V9H4zm0 4v2h2v-2H4zm0 4v2h2v-2H4zM18 5v2h2V5h-2zm0 4v2h2V9h-2zm0 4v2h2v-2h-2zm0 4v2h2v-2h-2z"></path>
        <path d="M9 5h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm0 8h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1z"></path>
      </svg>
    </a>
    Présentation
  </h3>
  <div class="mermaid">
    graph LR
    Adversaire --> GTO
    Adversaire --> GTNO
    GTO --> Range
    GTO --> Flop
    Range --> Avantage
    Flop --> Avantage
    Avantage --> Frequence
    Avantage --> Sizing
    Frequence --> Strategie
    Sizing --> Strategie
    style Adversaire fill:#f5f5f5,stroke:#666666,stroke-width:1px
    style GTO fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
    style GTNO fill:#dae8fc,stroke:#6c8ebf,stroke-width:1px
    style Range fill:#d5e8d4,stroke:#82b366,stroke-width:1px
    style Flop fill:#d5e8d4,stroke:#82b366,stroke-width:1px
    style Avantage fill:#f8cecc,stroke:#b85450,stroke-width:1px
    style Frequence fill:#d5e8d4,stroke:#82b366,stroke-width:1px
    style Sizing fill:#d5e8d4,stroke:#82b366,stroke-width:1px
    style Strategie fill:#f8cecc,stroke:#b85450,stroke-width:1px
  </div>
  <p>
    On part toujours de l'adversaire. Doit on jouer GTO ou exploitant ? Ensuite on definie sa range preflop. Enfin avec le flop, on voit qui à le range advantage dans le spot.
  </p>
  <p>
    Enfin avec le sizing qu'il va utiliser, on va pouvoir en déduire sa fréquence et donc sa stratégie.
  </p>
  <h3>
    <a class="link" href="#" onclick="document.querySelector('#player').currentTime=360">
      <svg viewBox="0 0 24 24">
        <path d="M4 3h16a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5c0-1.1.9-2 2-2zm0 2v2h2V5H4zm0 4v2h2V9H4zm0 4v2h2v-2H4zm0 4v2h2v-2H4zM18 5v2h2V5h-2zm0 4v2h2V9h-2zm0 4v2h2v-2h-2zm0 4v2h2v-2h-2z"></path>
        <path d="M9 5h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1zm0 8h6a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1z"></path>
      </svg>
    </a>
    Cas pratique
  </h3>
  <blockquote>
    On est en HU. BTN open et BB call. <br/>
    Le board est
    9 <img style="width: 20px;" src="https://github.githubassets.com/images/icons/emoji/unicode/2663.png?v8" />
    9 <img style="width: 20px;" src="https://github.githubassets.com/images/icons/emoji/unicode/2764.png?v8" />
    5 <img style="width: 20px;" src="https://github.githubassets.com/images/icons/emoji/unicode/1f537.png?v8" />
  </blockquote>
  <p>
    Ici le joueur n'est pas loin des 100%. Le bas de range c'est 95o ici, il a plus d'OP et de bon 9 (on va 3Bet 98s, T9s, J9s, ...). De manière générale, il est en position avec un range advantage, il est donc favoris dans ce spot. Il a donc intéret à miser ici.
  </p>
  <p>
    Le joueur va donc souvent miser, il va donc avoir une fréquence importante. La fréquence et le sizing sont liés, plus on va miser, plus notre sizing sera petit sauf dans le cas particulier d'un gros avantage de range ou l'on peut utiliser un gros sizing.
  </p>
  <p>
    Ici le BTN fait 1/3p, il va donc avoir une grosse fréquence de CBET.
  </p>
</div>

<script>mermaid.initialize({startOnLoad:true});</script>
