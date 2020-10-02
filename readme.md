# RPGOS - Open Source Role Playing Game

## Introdução
Já se sentiu frustrado alguma vez quando em sua aventura de RPG você fez algo extraordinário e no fim do dia você ganha a mesma quantidade de XP que seus colegas? Acha muito linear as progressões dos RPGs convencionais? Sente que não consegue criar muito ou reagir de formas diferentes a situações em seu jogo (somente dispel funciona contra aquela barreira de fogo, mas o que acontece se eu jogar um balde d'água)? 


## Desafio
### Sistema Operacional
O próposito do RPGOS é criar (mais um! yeee) sistema de RPG genérico, mas nosso foco é no "sistema operacional" (como windows, macOS, linux e etc). Nosso desafio aqui é criar um set de regras extremamente simples e abrangente, ou seja, se este livro (será que vai virar um livro?) tiver mais de 20 páginas, nos falhamos! Aqui você não vai encontrar nenhum descritivo extenso de equipamentos, magias, perícias e etc. 

### Open source
Justamente pela segunda característica do nosso "OS" - *open-source*, também derivado do mercado de tecnologia, os softwares open source, são aqueles softwares de código aberto, onde o dono do software é a comunidade! E aqui não é diferente, a comunidade é dona do RPGOS. A comunidade é responsável por manter, evoluir e criar coisas com ou ao redor deste software. Mesma coisa para o nosso RPGOS, ele nasceu com o propósito de criar e crescer na mão da comunidade. *One RPG to rule them all!*. 

#### Plataforma rpgos.net
Disponibilizamos uma plataforma para gestão de todo o conteúdo do RPGOS. Em rpgos.net você poderá buscar por milhares de habilidades, aventuras, cenários, monstros, mapas, NPCs, personagens prontos, mapas e muito mais. Veja o que está bombando, vote no conteúdo que mais curtiu, discuta em nossos foruns e até mesmo ganhe dinheiro vendendo conteúdos exclusivos para nossa comunidade. Sim, nosso intuito é que você possa viver de RPG! É o nosso sonho, pq não pode ser o seu também?

## Objetivo
A essência do RPGOS é explorar ao **MÁXIMO** a criatividade dos e a flexibilidade para os jogadores fazerem o que quiserem (quer lançar uma bola de fogo e invocar um sundae de morange na cabeça do seu inimigo para que saia fumacinha colorida após atingir? Claro, você pode tentar!), mas sem que o sistema seja extremamente complexo e cheio de regras. Para isso, **Regra número zero do RPGOS**: PARTICIPE! Submeta sugestões e alterações para set de regras, nossa equipe vai avaliar (só pra ver se não tem uma foto de chibata no meio né?), mas quem decide incluir ou não aquele conteúdo é a comunidade. Em nossa plataforma rpgos.net você pode votar em todo conteúdo que for gerado pela comunidade.

## Vamos ao que interessa
### Como funciona?
Escolhemos o modelo de pontos para governar o sistema, porque acreditamos que ele permita a maior flexibilidade e expressão da criatividade que gostaríamos de promover nas mesas de RPGOS. Tudo é possível dentro de RPGOS, mesmo que um personagem não possua a capacidade de levitar, ele pode tentar! Todas as ações em RPGOS seguem o básico:
```
dado + bonus >= dificuldade
```
**Regra número 1 do RPGOS** nada é uma regra. Se você quiser por exemplo que as rolagens de ação sejam menores que a dificuldade (e não menor ou igual a), claro que você pode! Queremos dar o maior poder aos jogadores e narradores, para construirem juntos uma aventura épica (e não seguir caminhos pré-definidos determinados por classes ou arquétipos.

#### Dado

#### Bonus

#### Dificuldade

#### Esforço

#### Superação

### Leveless
**Regra número 2 do RPGOS** Não existe nível. Não existe uma progressão linear para seu personagem, ou multiclasses

Seu mago conseguiu levantar uma rocha extremamente pesada? Ele vai ganhar alguns músculos ali sim!

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

Só anota aquilo que te afeta (se não tem bonus ou penalidade, sempre será d4);

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


- Superação:
O personagem pode tentar fazer um ato sobrehumano (ultrapassando seus limites), com algum tipo de desvantagem
em caso de sucesso, e de acordo com a situação (consultar o narrador) esse personagem ganha pontos de aprendizado, ou ganha
automaticamente um aumento em determinado atributo.

Exemplo: Personagem tem força física 2, e precisa levantar uma rocha, cuja dificuldade é 8. Em condições normais, é impossível que ele consiga realizar esse feito (resultado máximo 6: 1d4+2), mas ele pode tentar uma superação. 
Para isso ele transforma a jogada da seguinte maneira:
Dado da dificuldade: d2 (equivalante diferença entra a dificuldade e o alcance, mínimo d4, arredondado para o próximo dado)

Exemplos:
dif 20
alcance d6 + 2: 8
diferença: 12
rolagem: d12 + 8

dif: 8
alcance: d4 + 2: 6
diferença: 2 (d2)
rolagem: 1d4 + 2
(sempre transformar para o maior dado próximo, com penalidade)

dif: 20
alcance d8 + 3
diferença: 20-(8+3)=9
rolagem: d10 - 1

dif 20
alcance: d4
diferença: 16
rolagem: d20 + 4

dif 20
alcance: d4 + 1 = 5
diferença: 15
rolagem: d20 - 5

Diferença	Rolagem
1		1d4+3
2		1d4+2
3		1d4+1
4		1d4
5		1d6+1
6		1d6
7		1d8+1
8		1d8
9		1d10-1
10		1d10
11		1d12-1
12		1d12
13		1d20-7
14		1d20-6
15		1d20-5
16		1d20-4
17		1d20-3
18		1d20-2
19		1d20-1
20		1d20

, em uma jogada de superação, onde ele rola um dado - em que a dificuldade é o resultado máximo do dado, ou seja, dificuldade 8, o personagem rola um 1d8 para tentar superar o obstáculo, onde somente com um 8 ele consegue superar o obstáculo (qualquer dificuldade é aceita desde que haja uma combinação possível de dados e seu resultado máximo, exemplo: dificuldade 24 pode ser elaborada com 4d6, sendo fatalidade 4 e sucesso 24, apesar de não ser proibido é melhor evitar dificuldades não homogeneas).

A consequênica da superação: 
Sucesso: -1/4 de stamina durante 1 hora;
Falha: -1/2 de stamina durante 1 hora;
Fatalidade (resultado mínimo): -3/4 de stamina durante 2 hora;
