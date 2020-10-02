# RPGOS - Open Source Role Playing Game

Lê-se "érri-pê-gê--ô-esse".

## Introdução

Já se sentiu frustrado alguma vez quando em sua aventura de RPG você fez algo extraordinário e no fim do dia você ganha a mesma quantidade de XP que seus colegas? Acha muito linear as progressões dos RPGs convencionais? Sente que não consegue criar muito ou reagir de formas diferentes a situações em seu jogo (somente dispel funciona contra aquela barreira de fogo, mas o que acontece se eu jogar um balde d'água)? 


## Desafio

O próposito do RPGOS é criar (mais um! yeee) sistema de RPG genérico, mas nosso foco é em dois pontos cruciais: 

- Sistema Operacional: base simples, mas abrangente, onde a comunidade pode construir qualquer ambiente, de mundano a épico, de jurássico a futurista, de pós-apocaliptico a esportes;
- Open source: foco na comunidade. A comunidade construi o sistema;

### Sistema Operacional
O "sistema operacional" (como windows, macOS, linux e etc). Nosso desafio aqui é criar um set de regras extremamente simples e abrangente, ou seja, se este livro (será que vai virar um livro?) tiver mais de 20 páginas, nos falhamos! Aqui você não vai encontrar nenhum descritivo extenso de equipamentos, magias, perícias e etc. 

### Open source

Justamente pela segunda característica do nosso "OS" - *open-source*, também derivado do mercado de tecnologia, os softwares open source, são aqueles softwares de código aberto, onde o dono do software é a comunidade! E aqui não é diferente, a comunidade é dona do RPGOS. A comunidade é responsável por manter, evoluir e criar coisas com ou ao redor deste software. Mesma coisa para o nosso RPGOS, ele nasceu com o propósito de criar e crescer na mão da comunidade. *One RPG to rule them all!*. 

#### Plataforma rpgos.net
Disponibilizamos uma plataforma para gestão de todo o conteúdo do RPGOS. Em rpgos.net você poderá buscar por milhares de habilidades, aventuras, cenários, monstros, mapas, NPCs, personagens prontos, mapas e muito mais. Veja o que está bombando, vote no conteúdo que mais curtiu, discuta em nossos foruns e até mesmo ganhe dinheiro vendendo conteúdos exclusivos para nossa comunidade. Sim, nosso intuito é que você possa viver de RPG! É o nosso sonho, pq não pode ser o seu também?

## Objetivo

A essência do RPGOS é explorar ao **MÁXIMO** a criatividade dos e a flexibilidade para os jogadores fazerem o que quiserem (quer lançar uma bola de fogo e invocar um sundae de morange na cabeça do seu inimigo para que saia fumacinha colorida após atingir? Claro, você pode tentar!), mas sem que o sistema seja extremamente complexo e cheio de regras. Para isso, **Regra número zero do RPGOS**: PARTICIPE! Submeta sugestões e alterações para set de regras, e quem decide incluir ou não aquele conteúdo é a comunidade. Em nossa plataforma (rpgos.net)[rpgos.net] você pode votar em todo conteúdo que for gerado pela comunidade.

## Vamos ao que interessa

### Como funciona?

Escolhemos o modelo de pontos para governar o sistema, porque acreditamos que ele permita a maior flexibilidade e expressão da criatividade que gostaríamos de promover nas mesas de RPGOS. Tudo é possível dentro de RPGOS, mesmo que um personagem não possua a capacidade de levitar, ele pode tentar! Todas as ações em RPGOS seguem o básico:
```
dado + bonus >= dificuldade
```
**Regra número 1 do RPGOS** nada é uma regra. Se você quiser por exemplo que as rolagens de ação sejam menores que a dificuldade (e não menor ou igual a), claro que você pode! Queremos dar o maior poder aos jogadores e narradores, para construirem juntos uma aventura épica (e não seguir caminhos pré-definidos determinados por classes ou arquétipos.

#### Dado
Os dados de determinada habilidade determinam seu conhecimento, sua capacidade perante determinada situação. Adquirir dados é interessante pois aumenta seu alcance e te permite realizar tarefas mais difícies (não aumenta sua probabilidade de acerto - para isso adquira especialidade).

#### Bonus
Especialidade, determina quão familiar você com determinada habilidade. É um bonus fixo, ou seja, sempre aumenta sua probabilidade em qualquer disputa daquela habilidade.

#### Dificuldade

Em RPGOS toda a ação possui um valor numérico de dificuldade para ser realizada. Sugerimos que as dificuldades sejam equivalentes aos dados do jogo (4, 6, 8, 10, 12, 20 e 100), sendo a menor, mais fácil até a maior praticamente impossível. As difculdades para realiazar uma ação serão totalmente subjetivas e decidadas pelo narrador durante a aventura. Elas podem inclusive variar de jogador para jogador (se um jogador tiver alguma limitação fisíca, talvez seja mais fácil, aumentar a dificuldade da ação para ele - promovendo até um momento de superação - do que ficar contabilizando bonus e penalidades nas fichas). Fica aqui a menção a **regra número 1**, caso tenham preferência de uma dificuldade fixa para os jogadores e aplicar penalidades nas rolagens ao invés disso.

Outra sugestão para o sistema de dificuldade é o sistema de **disputa**. Como uma ação (com um custo de esforço) o alvo da ação pode fazer algo que modifique a dificuldade (seja para um valor fixo mais alto, seja para uma rolagem de dado). O exemplo mais clássico da disputa é uma jogada básica de ataque. A jogada de ataque em primeiro lugar é (**regra número 1** pode ser) uma rolagem de agilidade física do personagem contra o bonus de agilidade física do inimigo. 

```
Ron Silva tem agilidade física 2 e Jobert Paxton tem agilidade física 1. Ron joga 1d4 (dado base, uma vez que Ron não é habilidoso em nenhuma arte de combate) + 2 \(bonus de agildade física). Qualquer que seja o resultado Ron acerta Jobert em situações normais (1d4+2 sempre vai ser maior que 1 - mais uma referência a **regra\ número 1** - se quiserem colocar falha fatal também será bem vinda - ou seja - toda rolagem 1, independente do resultado final é uma falha). Porém, ciente do\ perigo, Jobert vai fazer um esforço adicional e tentar desviar do golpe de Ron. Jobert não é habilidoso em desvio, então como é uma ação de agilidade, ele joga \ 1d4 mais seu bonus de agilidade física (1d4+1). Wow, mesmo sendo muito mais ágil Ron não conseguiu acertar Jobert nesse ringue de boxe! Ron rolou um 2 no dado (4\ no total, 2 do dado + 2 do seu bonus de agilidade física), porém Jobert se esforçou muito e conseguiu desviar do golpe com um 4 no dado (total 5, 4 do dado e 1 de\ bonus).
```

Jobert poderia por exemplo, fazer um esforço de bloqueio por exemplo (onde ele recebe o golpe de Ron, mas reduz o dano rolando uma disputa de força física contra Ron). Ou Kalinder, o paladino consegue manifestar uma massa de ar, que impede que inimigos se aproximem, então ele joga o seu dado relacionado a sua habilidade de "barreira de ar" ou "escuto dos ventos" mais seu bonus de força mental contra a força física dos zumbis que o estão atacando. 

O narrador pode ainda incrementar a situação colocando dificuldades combinadas para realizar uma ação. Os vampiros estão avançando para cima de Kalinder, e são muito ageis, habilidosos em deslocamento, rolam 1d8+2 para avançar em cima de Kalinder, e este precisa ser sagaz na manifestão da sua "cortina de vento" (note que variamos o nome da habildade aqui diversas vezes, cada aventura é única, cada história, e cada habilidade pode ser única da sua aventura também). Para manifestar a cortina de vento antes que os vampiros se aproximem Kalinder precisa fazer uma rolagem de agilidade mental contra agilidade física dos vampiros. Oh não Apesar de habilidoso Kalinder foi surpreendido por mais vampiros!

Ao elaborar as situações de cada ação, o narrador deve entender a natureza da situação para definir as dificuldades. Existem 4 atributos (ou até mesmo saúde pode ser usada), 2 físicos e 2 mentais, que podem ser combinados da maneira que o narrador preferir. Uma jogada de ataque convencional pode ser uma rolagem de agilidade física para acertar, seguida de uma rolagem de força física para determinar o dano. **regra número 1** ou se quiserem facilitar e ter uma jogabilidade mais ágil, rolar somente uma jogada de força física. Se quiser um combate mais complexo, pode combinar uma dificuldade de agilidade física, com agilidade mental para determinar onde no corpo do inimigo que o golpe atingiu (ou se o personagem quiser atingir um ponto específico do corpo do inimigo). Isso pode ter consequências como bonus no dano, penalidades nas jogadas do inimigo, redução do esforço do inimigo e etc. Fica a cargo do narrador definir as regras, dificuldades e consequências, ou então consulte nossa comunidade em [rpgos.net](rpgos.net) para situações e cenários prontos.

Incentivamos também a criação de habilidades que facilitem determinadas ações. Um mestre do kung-fu pode por exemplo, combinar sua força física, força mental, agilidade física e agilidade mental para combinar golpes devastadores, tanto em maior chance de acerto, quanto no estrago que vai fazer.

O sistema de dificuldades faz com que cada combate seja único. Veja na sesssão de exemplos de situações para entender a diversidade que a dificuldade acrescenta.

#### Esforço

Toda ação requer um determinado esforço para ser realizada. Não vai achando que seu personagem consegue executar 18 golpes em uma única rodada. Ele até pode conseguir, mas deve ser treinado para isso. O **Esforço** representa o custo de ação e a capacidade de realizar. Assim como as demais regras do RPGOS o esforço é medido em pontos. Cada personagem tem uma quantidade de pontos de esforço que pode gastar por turno. Por exemplo, atacar um inimigo pode custar 2 pontos de esforço dos 3 que o personagem possui. 

Não vamos determinar aqui quantos pontos de esforço começar, ou quanto cada ação deve custar. Vamos deixar isso para nossa comunidade determinar, e que vocês em suas narrativas, tenham a liberdade de definir isso. Quer fazer personagens bem humanos, com 2 de capacidade de esforço? Ou então personagens semi-deuses com capacidade de esforço de 100. A quantidade de esforço vai ser determinada também em cima do custo das habilidades de sua campanha que os personagens querem realizar. Isso dá uma sensação de "nível" do personagem. 

```
Tibault, está tentando aprender uma magia chamada convocar meteoros, porém por mais que consiga aprendê-la, precisa de um esforço de 30, enquanto tibault só possui esforço 5! Ele pode usar 6 rodadas para evocar a magia? Se vocês entederem que sim! Ou não, personagens não podem realizar ações maiores que seus esforços. Ou melhor ainda! (ver a próxima sessão), apesar de saber como invocar os meteoros, Tibault precisa fazer um teste de superação para conseguir realizar tal proeza sobrehumana.
```

Em via de regra geral, o esforço é a capacidade do personagem de executar ações. Podemos incrementar (não somente com as rolagens de superação), mas com um sistema de recuperação de esforço (imaginem o esforço como sendo o fôlego do personagem). Então Tibault possui 5 pontos de esforço por rodada, mas recupera apenas 2 a cada nova rodada. Podem haver habilidades que impactem o esforço ou a recuperação do esforço. Para um jogo mais fluido, recomendamos que o esforço seja a capacidade de ações que o personagem consegue realizar.

#### Superação

Só porque uma ação tem dificuldade 10 e personagem só consegue tirar 5 no máximo no dado (1d4 + 1 de FF), não quer dizer que o personagem não consiga realizar qualquer ação. O personagem pode tentar fazer um ato sobrehumano (ultrapassando seus limites) e realizar essa ação em uma situação de extrema dificuldade. Recomendamos que geralmente nessas situações que o personagem ganhe pontos de habilidade, ou então ganhe um aumento de atributo (lembra do nosso mago que levantou uma rocha super pesada? É aqui que ele ganha +1 de Força Física). Vamos estudar mais afundo este exemplo.

```
Baj Omara, é um mago iniciante e esta peregrinando para aprender novas magias. Ele é um estudioso do fogo (detalhe irrelevante para esse momento, mas a gente é criativo né?). Ouviu dizer que há um eremita morando em uma caverna com conhecimentos ancestrais que pode lhe ensinar o caminho da magia arcana. Enfim, chegando na caverna Baj ve que há uma pedra Muito grande impedindo a entrada na caverna. Baj não tem nenhuma habilidade que possa lhe ajudar (magia, manobra, conhecimento, nadica!). Ele vai tentar remover a pedra com sua força bruta. A dificuldade definida pelo mestre para remover a pedra é 10. É uma ação pura de força física. Baj não tem nenhum bonus de força física, e como falamos anteriormente não é **habilidoso** nem **especialista** em nada que possa lhe ajudar. Ele vai tentar então realizar uma ação de superação. 
```

Como funciona:
- Calcule o alcance máximo que o personagem consegue atingir de resultado (1d4, sendo 4 o alcance máximo);
- Calcule a diferença entre o alcance e a dificuldade do teste: 10 (dificuldade) - 4 (alcance) = 6 (chamamos este resultado de **diferença**);
- O personagem deve fazer uma rolagem de *dDiferença*, ou seja, o dado correspondente a diferença (6 aqui no caso 1d6) e deve rolar o resultado máximo deste dado (no caso 6). Qualquer outro resultado ele falha (afinal ele está dando o máximo de si).

##### Probabilidades

Abaixo temos as probabilidades de cada rolagem e seus dados equivalentes (recomendamos fortemente manter as jogadas simples e determinar dificuldades que resultem em rolagens de superação com os dados padrão para facilitar os cálculos)

| Dado     | Probabilidade |
| ---------|--------------:|
| 1d4      | 25%           |
| 1d6      | 17%           |
| 1d8      | 13%           |
| 1d10     | 10%           |
| 1d12     | 8%            |
| 2d4      | 6%            |
| 1d20     | 5%            |
| 2d6      | 3%            |
| 2d8      | 2%            |
| 2d10     | 1%            |
| 2d12     | .7%           |
| 2d20     | .3%           |

Para sua conveniência, colocamos aqui outras probabilidades e dados (aproximados) que podem ser rolados para diferença:

| Diferença | Probabilidade | Dado Equivalente |
| ----------|:-------------:|-----------------:|
| 2         | 50%           | 1d4 (3 ou 4)     |
| 3         | 33%           | 1d6 (5 ou 6)     |
| 5         | 20%           | 1d10 (9 ou 10)   |
| 7         | 14%           | 1d8              |
| 9         | 11%           | 1d10             |
| 11        | 9%            | 1d10             |
| 13        | 8%            | 1d12             |
| 14        | 7%            | 1d12             |
| 15        | 7%            | 2d4              |
| 16        | 6%            | 2d4              |
| 17        | 6%            | 2d4              |
| 18        | 5%            | 1d20             |
| 19        | 5%            | 1d20             |

##### Consequência
Indepedente do resultado da superação, ela é uma ação que exige extremo esforço (físico, mental ou os dois). Em caso de **sucesso** o personagem perde 1/4 dos seus pontos de esforço por 1 hora. Em caso de falha (normal, ou seja, qualquer resultado diferente de 1 e do máximo), ele perde metade dos seus pontos de esforço durante 2 horas, e em caso de falha fatal (oh no, alguma coisa deu errado), ele perde 3/4 do seu esforço durante 4 horas! Além disso, em caso de falha, o personagem não pode tentar outra superação nas próximas 6 horas (Lembrem-se da regra **número 1**, se quiserem fazer uma aventura *a la* cavaleiros do zodiaco, onde tudo é na base da superação, fiquem a vontade para remover essa contingência).

Tabela alterantiva de consequências:

##### Recompensa
Além de conseguir superar o obstáculo, a superação evolui, melhor, faz o personagem crescer. Fica a critério do narrador quais as recompensas em uma superação bem sucedida, e vamos deixar aqui uma tabela com uma sugesestão de recompensas

O personagem pode estar sempre tentando se superar e isso vai torná-lo o campeão da aventura épica.

 Personagem tem força física 2, e precisa levantar uma rocha, cuja dificuldade é 8. Em condições normais, é impossível que ele consiga realizar esse feito (resultado máximo 6: 1d4+2), mas ele pode tentar uma superação. 
Para isso ele transforma a jogada da seguinte maneira:
Dado da dificuldade: d2 (equivalante diferença entra a dificuldade e o alcance, mínimo d4, arredondado para o próximo dado)

, em uma jogada de superação, onde ele rola um dado - em que a dificuldade é o resultado máximo do dado, ou seja, dificuldade 8, o personagem rola um 1d8 para tentar superar o obstáculo, onde somente com um 8 ele consegue superar o obstáculo (qualquer dificuldade é aceita desde que haja uma combinação possível de dados e seu resultado máximo, exemplo: dificuldade 24 pode ser elaborada com 4d6, sendo fatalidade 4 e sucesso 24, apesar de não ser proibido é melhor evitar dificuldades não homogeneas).

A consequênica da superação: 
Sucesso: -1/4 de stamina durante 1 hora;
Falha: -1/2 de stamina durante 1 hora;
Fatalidade (resultado mínimo): -3/4 de stamina durante 2 hora;

##### Jogadas aleatórias

Muitas vezes o jogador não sabe o que fazer, mas mesmo assim dá certo. Caminhar na escuridão, lutar sem os sentidos, jogar poker e por ai vai. Nessa situação o narrador deve definir uma dificuldade em % (quanto maior mais difícil) e o personagem deve fazer uma rolagem de um d100 (2d10) para conseguir realizar o feito (o resultado deve ser maior ou igual a dificuldade). Nenhum bonus é aplicado, pois o jogador está fazendo uma ação sem nenhuma direção, sem nenhum atributo para fortalecê-lo. Normalmente jogadas aleatórias não dão recompensas, mas as vezes se o narrador achar pertinente ele pode recompensar o jogador dada a relevância do feito.

### Habilidades

As habilidade substituem rolagens padrão de atributo (1d4+bonus) para lidar com detarminadas situações, ao qual o personagem já tenha vivenciado, estudado ou adquirido de alguma forma (item, equipamento, pergaminho mágico, maldição, benção, feitiço). Tudo em RPGOS podem ser habilidades: ações, magia, combate, defesa, movimento, conversas, ladinagem, observação, esconder, 

Como dito anteriormente uma pessoa não treinada ou não-**habilidosa** em determinada ação fará uma rolagem inexperiente (1d4) contra a dificuldade daquela ação. Já uma pessoa **habilidosa** ou treinada, que tem alguma experiência sobre aquela ação substituem o dado inexperiente pelo seu dado daquela ação. 

```
Robert Ludoc está dirigindo seu carro de F1 quando vê Sakato Naboko se aproximando para ultrapassagem. Ludoc vai tentar fazer uma manobra para impedir que Sakato o ultrapasse na última volta da corrida. Obviamente Ludoc tem treinamento em "manobras evasivas com carros de formula 1" e ao invés de fazer um teste (básico) de agilidade mental (para perceber Naboko) e um teste de agilidade física para tentar bloquear a passagem (ambos com d4+bonus), "manobras evasivas com carros de formula 1" da a Ludoc (que é um fenomeno das pistas) 1d12 na rolagem mais seus bonus (combinados) de agilidade física e mental (+1 e +5 respectivamente). O narrador define a dificuldade 12 para evitar a ultrapassagem (ou ele poderia rolar também um dado com as habilidades de Nakobo), e com 1d12+6, Ludoc precisa tirar um 6. Que pena Ludoc, apesar de muito esforço e perícia, Nakobo também é um grande piloto e com um 5 no dado, por um triz, Nakobo ultrapassa Ludoc e vence o GP de Monaco!
```

##### Leveless
**Regra número 2 do RPGOS** Não existe nível. Não existe uma progressão linear para seu personagem, ou multiclasses. Ações no jogo geram **pontos de habilidade**.
Seu mago conseguiu levantar uma rocha extremamente pesada? Ele vai ganhar alguns músculos ali sim! Se ele vai conseguir é outra história. Esses pontos de habilidade são usados para aprender habilidades. Cada habilidade tem um custo para aprender e o jogador deve gastar esses PHs para comprar novas habilidades. Isso abre um leque de eventos e interpretações para a própria evolução do personagem, o aprendizado e crescimento do personagem, passa a ser parte da aventura. 

```
Jin Liu Bei está treinando com o mestre ancião Dong Chao Jen nos picos nevados de Horuzaki, e somente quando Jin atingir um certo patamar de força física, agilidade e agilidade mental, ele será capaz de realizar o golpe Louva-Deus da Lua, que atinge os pontos vitais e prosta o inimigo até uma morte lenta e dolorosa. 
```

**Regra número 3 do RPGOS** tudo no mundo pode ser aprendido pelos personagens. Seu paladino perdeu a fé e agora quer soltar magias arcanas, tudo bem! Ele pode seguir um caminho para tentar aprender. Claro que o próprio aprendizado de novas habilidades tem uma dificuldade e alguns pré-requisitos devem ser antigidos para que o personagem possa aprender e realizar determinada ação. John Statin quer aprender telecine, mas ele não tem nenhuma força, agilidade ou saúde mental! Poxa John me ajuda a te ajudar ne? No entanto, John pode se exercitar, estudar para crescer seu intelecto, melhorar seus atributos mentais, conhecer um telepata, aprender algo como Manifestação Psiônica (pode ser uma habilidade base para todas as demais habilidades psiônicas) e após ele conseguir 50 pontos de habildade ele consegue 
finalmente aprender a telecinese (básica), levanta canetas e entorta colheres, para fortalecer sua telecinese, ele deve fortalecer sua força mental e juntar mais 50 pontos para "evoluir" a telecinese (todos estes conceitos serão discutidos em detalhe posteriormente). 

#### Ganhando pontos de habilidade

- For
	- Físico (FF)
	- Mental (FM)
- Agl
	- Física (AF)
	- Mental (AM)
- Saúde
	- Física (SF)
	- Mental (SM)

- Aprender (Custo)
- Esforço
	- Físico (EF)
	- Mental (EM)
- Resistência
	- Física (RF)
	- Mental (RM)

Dado 	Bonus 		Dificuldade
Nd	+B	vs	F / Nd+B

### Equipamento

Gerenciar equipamento em RPGOS também deve ser tão simples quanto criar habilidades. E para isso pensamos no uso dos equipamentos como o próprio uso de habilidades! 

```
Uma cota de malha por exemplo adiciona +3 na força física do personagem quando resistindo a ataques físicos, ou mágicos com manifestação física. Não quer dizer que o personagem fica mais forte, mas a dificuldade de causar dano nele fica mais alta.
```

## Exemplos de situações

Alguns exemplos de como lidar com algumas situações em RPGOS.

#### Cobertura

Vassili Zaitsev está emboscado no cemitério de trens e não consegue encontrar o major Erwin König. Após mais de 12 horas, (e um bem sucedido teste de rastreamento) Vassili vê ao longe o rosto de König em um instante, no reflexo do retrovisor de uma carcaça de um carro abandonado. Vassili calcula que König esteja a mais ou menos 50m de distância dentro de um container abandonado coberto por alguns carros e destroços da cidade bombardeada. É um tiro praticamente impossível, mas vassili é um combatente treinado. Possui a habilidade sniper, que o permite atirar com 1d10. Em relação aos bônus, por seu treinamento em sniper ele é duplamente especialista, adicionando +2 em suas jogadas além dos bonus de força mental, agilidade mental e agilidade física, totalizando +7 (+2 especialista, +1 agilidade física, +2 agilidade mental e +2 força mental)! Antes o narrador pede a Vassili, pelo frio e o tempo sem comida, que ele faça um teste de força mental para estabilizar a arma. Caso de sucesso ele pode realizar o tiro, em caso de falha ele pode atirar mesmo assim, mas será uma jogada aleatória (com dificuldade a ser definida pelo narrador). Vassili possui a habilidade "frieza" o que o permite jogar um 1d8 (além do seu bonus de força mental) para situações extremas do seu corpo, que exigem concentração. O narrador define a dificuldade 4 (dificuldade extrema para seres humanos normais, mas não para Vassili). Ele rola 1d8 +2 (seu bonus de força mental) e sucesso! Um 9 (7+2)! Estabilizou com louvor (em pré testes muito bem sucedidos de dificuldade o narrador pode ainda dar um bonus adicional para o próximo teste do jogador). Pela maestria e concentração de Vassili o narrador decide dar +1 bonus na sua jogada de atirar. Tudo pronto para o tiro. 1d10+8, uma capacidade de atirar totalmente excepcional para um humano. Alcance 18, entrento o narrado diz q dadas as condições de cobertura a dificuldade para acertar König é de 26!!! É um tiro extremamente dificil, mas se há alguém que consegue fazê-lo, esse alguém é Vassili. Ele vai tentar uma superação, para isso a diferença entre a dificuldade e seu alcance é de 8, Vassili precisa de 8 em uma rolagem de 8 para acertar König. E ele consegue!!!!! Vassili rapidamente puxa o gatilho e com um belissimo 8 no dado acerta o olho do major König encerrando a longa batalha.

Para um outro soldado, um soldado raso talvez, poderiamos fazer um setup diferente: como uma dificuldade maior, ou até mesmo a mesma dificuldade sabendo que o soldado só teria 1d4+1 para acertar por exemplo (ficando uma jogada de superação d20 por exemplo), ou então, ele não faz a menor ideia de onde König está e faz uma jogada de tiro aleatória (dificuldade 95 em 100).

#### 

## Exemplos de habilidades

Aqui listamos exemplos de habilidades que podem ser utilizadas, modificadas ou ignoradas em suas campanhas. Consulte nosso compendium de habilidades em (rpgos.net)[rpgos.net] para encontrar uma listagem com milhares de habilidades criadas por nossa comunidade.

Habilidade (tudo: magia, skill, ataque, defesa, ...)
Custo: Quantos pontos o personagem deve gastar para aprender esta habilidade
Esforço: Qual o esfoço (fisico/mental/ambos) 
Desc:
Prereq:
Consequência: 
Evolução (evo):
- Habilidoso (Pelo mesmo custo base, aumenta em um dado a abilidade se houver algum teste de disputa);
"Você não tem muito controle sobre aquilo que faz, mas consegue realizar feitos melhores"
- Especialista (Pelo dobro do custo base, aumenta +1, se houver algum teste de disputa);
"Você tem mais assertividade naquilo que você faz"
- Especial (descrito na abilidade);

Exemplo:
Bater
Custo: 5
Esforço: 2
Descrição: Abilidade de luta
Prereq: FF 1, AF 1
Disputa: Use d6 contra defesa do inimigo
Consequência: A partir daqui, use seu dado de bater +FF, +Esp em combates

Arte marcial:
Custo: 20
Esforço: 5
Descrição: Une Força e Agilidade em combate
Prereq: FF 2, AF 2, Bater
Consequências: 
	- A partir daqui, use seu dado de bater +FF, +AF, +Esp em combate
	- A partir daqui, use seu dado de dano +FF, +AF +Esp no ferimento
Evolução: 

Estrategista:
Custo: 10
Esforço: 5(F) e 3(M)
Descrição: Você sabe onde doi
Prereq: FF 2, AM 2, Bater
Consequência: A partir daqui, use seu dado de bater +FF+AM+Esp em combate

Desviar
Custo: 5
Esforço: 2
Descrição: Permite ao personagem desviar de golpes físicos
Prereq: Agl física 1
Disputa: Antes do impacto de um golpe físico, faça uma disputa contra o dado de ataque do inimigo.
Consequência: O inimigo erra o ataque automaticamente

Golpe da serpente:
Custo: 20
Esforço: 10
Descrição: Você executa uma sequência de ataques atingindo pontos vitais do inimigo.
Prereq: Agl fisica 5, Agl Mental 4, skill xyz
Disputa: Acerte 4 ataques no inimigo
Consequência: O inimigo perde metade do seu esforço por 1 minuto;
Evolução:
	- Mestre da serpente: dobra a duração

Amarrar:
Custo: 10
Esforço: 5
Descrição: Você amarra o inimigo, imobilizando-o
Prereq: FF 2, AF 2, AM 1 e corda
Disputa: Acerte um ataque no inimigo
Consequência: O inimigo fica imobilizado, seu esforço caindo a zero. Deve fazer uma disputa de Força Física contra sua Força Física para se soltar;
Trilha: 
- Laço melhorado (+1 na disputa de FF);
- Habilidoso (+1 na disputa de FF);