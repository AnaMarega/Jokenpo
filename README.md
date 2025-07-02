# Jokenpô: Mario Version 🍄
## Introdução:
Bem-vindo ao mundo nostálgico dos games clássicos! O Jokenpô: Mario Version é um projeto inovador que combina a simplicidade do tradicional jogo Pedra-Papel-Tesoura com a magia sonora e visual do universo Super Mario Bros. Este sistema eletrônico desenvolvido em protoboard transforma uma brincadeira atemporal em uma experiência interativa única, onde tecnologia e diversão se encontram.

## Participantes:
* Ana Rita Marega Gonçalves - 15746365
* Luiz Henrique Martins Silva - 15695612 [GitHub](https://github.com/LuizUSP)
* Matias Aldrighi Mendonça - 11485044  [GitHub](https://github.com/Mitch-USP)
* Pedro Henrique Marques de Carvalho Silva - 16819166  [GitHub](https://github.com/PEDROHMCS)
  
## Descrição:
:moyai: :page_facing_up: :scissors:
O Jokenpô: Mario Version é um sistema eletrônico inteligente que simula um oponente automatizado no clássico jogo Pedra-Papel-Tesoura, mas com um toque especial do mundo dos videogames. O projeto utiliza uma protoboard como base para criar uma experiência imersiva que desperta nostalgia e diversão.
Desenvolvimento de Sistema Eletrônico na Protoboard para Simulação de Oponente Automatizado em Jogo Pedra-Papel-Tesoura (Jokenpô)
## 🎮 Funcionamento do Sistema:
### Início da Partida:
O sistema inicia tocando a icônica música tema do Super Mario Bros
As luzes LED piscam sincronizadas com o ritmo da música, criando um espetáculo visual
O jogador aguarda o momento certo para fazer sua jogada
### Sistema de Cores e Movimentos:
* 🔴 Vermelho = Pedra (Força bruta do Mario)
* 🟡 Amarelo = Papel (Flexibilidade como uma estrela)
* 🟢 Verde = Tesoura (Agilidade como o Luigi)
### Mecânica do Jogo:
O jogador seleciona sua cor/movimento
O computador randomiza automaticamente seu movimento
O sistema processa a comparação entre as jogadas
O resultado é exibido com efeitos sonoros característicos do Mario
### 🏆 Regras do Jogo:
Empate: Cores iguais resultam em empate
Verde (Tesoura): Vence Amarelo (Papel) | Perde para Vermelho (Pedra)
Vermelho (Pedra): Vence Verde (Tesoura) | Perde para Amarelo (Papel)
Amarelo (Papel): Vence Vermelho (Pedra) | Perde para Verde (Tesoura)
### 🎵 Experiência Audiovisual:
Trilha Sonora: Música tema original do Super Mario Bros
Efeitos Sonoros: Sons característicos do Mario para cada resultado
Sincronização Visual: LEDs piscando no ritmo da música tema
Feedback Imediato: Resposta visual e sonora instantânea para cada jogada

## Componentes Utilizados
| Quantidade | Componente       | Especificação                    | Valor    |
|------------|------------------|----------------------------------|----------|
| 6          | LED              | 5MM (2Verm/2Azul/2Amarelo)      | R$ 3,00  |
| 6          | Resistor         | CR25 4K7 Carvão ROHA            | R$ 4,20  |
| 16         | Jumper           | Macho x Macho                   | R$11,20  |
| 1          | Protoboard       | BB-01 400P S/BASE TOWER         | R$21,70  |
| 4          | Chave Táctil     | 6x6mm 180g - 4 pinos Tower      | R$ 4,80  |
| 2          | Sonalarme        | SEM-12A-3/7V-C-N (2A/7V)        | R$19,40  |
| 1          | Arduíno Uno      | Emprestado                      | FREE     |
| **TOTAL**   |                  |                                  | **R$64,30** |
## Explicação dos Componentes:
#### ProtoBoard:
 > A protoboard é uma placa de desenvolvimento com orifícios interconectados internamente que possibilita a montagem temporária de circuitos eletrônicos por meio da inserção direta de componentes como resistores, LEDs e jumpers, dispensando soldagem. Sua estrutura modular permite configurações experimentais rápidas e ajustes imediatos, sendo amplamente utilizada na fase preliminar de projetos eletrônicos por estudantes e entusiastas devido à sua praticidade na validação de conceitos antes da implementação definitiva.

#### LED (5MM - 2 Vermelhos/2 Azuis/2 Amarelos)
 > Diodos emissores de luz que convertem energia elétrica em luz visível através da recombinação eletrônica em material semicondutor. As cores diferentes indicam diferentes comprimentos de onda (vermelho ≈ 620nm; azul ≈ 470nm; amarelo ≈ 590nm), sendo utilizados para sinalização visual no circuito.

#### Resistor CR25 4K7 Carvão ROHA
 > Componente passivo que limita o fluxo de corrente elétrica através de material resistivo (carbono). O valor 4K7 indica resistência de 4.700Ω (±5%), essencial para ajustar níveis de tensão/corrente nos LEDs e demais componentes sensíveis.

#### Jumper Macho x Macho
 > Cabos condutores com conectores metálicos nas extremidades para interligação entre pontos da protoboard. Permitem criar trajetos personalizados para a corrente elétrica sem necessidade de solda, ideal para montagens experimentais.

#### Chave Táctil 6x6mm (180g - 4 pinos)
 > Interruptor momentâneo que completa o circuito apenas quando pressionado fisicamente. A força de acionamento (180gf) e o tamanho reduzido (6mm²) permitem integração em projetos compactos para controle manual de subsistemas.

#### Sonalarme SEM-12A-3/7V-C-N
 > Transdutor eletroacústico que converte pulsos elétricos em sinais sonoros audíveis (~70dB). Operando em 7V DC com consumo máximo de 2A, é utilizado para alertas sonoros ou feedback acústico em sistemas automatizados.

#### Arduino Uno 
 > Microcontrolador baseado no chip ATmega328P que serve como cérebro programável do projeto. Fornece interfaces digitais/analógicas para leitura de sensores e acionamento de atuadores, com alimentação via USB ou fonte externa (7-12V).

## Circuito Arduino
<img src= "https://github.com/AnaMarega/Jokenpo/blob/1ec5f4c4a8e2628ed5a450874d0d3e1f98166eb0/imagens/Circu%C3%ADto2.png" width="700">

<img src= "https://github.com/AnaMarega/Jokenpo/blob/78ae7d9c31e5f23d565ac10f4a646e4c8810d329/imagens/Circu%C3%ADto.png" width="600">

## Link Círcuito no Tinkercard:

Clique para acessar o [Tinkercard](https://www.tinkercad.com/things/04uaA1mrBCj/editel?returnTo=%2Fdashboard&sharecode=968SHC6sP_CXqYMkcjzw7VgCyvIV4Mg-XQVd2ycNu24)

## Código do Projeto
O código completo está disponível no repositório:
👉 **[Visualizar Código Principal](https://github.com/AnaMarega/Jokenpo/blob/1ec5f4c4a8e2628ed5a450874d0d3e1f98166eb0/C%C3%B3digo%20Jokenp%C3%B4)**


## Imagens do Projeto
<img src= 
<img src=

## Vídeo do Projeto
Link para o Vídeo do [Projeto]()
