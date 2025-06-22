FloodTrack Edge – Sistema Inteligente de Alerta contra Enchentes

Sobre o projeto
O FloodTrack Edge nasceu com uma missão simples: proteger vidas e minimizar os impactos causados por enchentes.
Usando um Arduino, um sensor ultrassônico e alguns componentes básicos, o sistema detecta quando o nível da água começa a subir e emite alertas sonoros e visuais automaticamente.

A ideia é trazer uma solução acessível, funcional e fácil de replicar — principalmente em comunidades onde o acesso à tecnologia ainda é limitado, mas o risco de alagamentos é constante.

Qual problema estamos resolvendo?
Infelizmente, enchentes são parte da realidade de muitas cidades brasileiras. Ruas alagadas, casas invadidas pela água e pessoas sem tempo de se preparar.
O maior problema é a falta de alerta antecipado. Com esse sistema, queremos oferecer um aviso rápido e claro, permitindo que as pessoas ajam antes do pior acontecer.

O que a solução faz?
Usa um sensor ultrassônico para medir a distância entre o chão e o nível da água. Quando essa distância diminui (ou seja, a água sobe), ele aciona um LED vermelho e um buzzer para avisar que o local está em risco.

É simples, direto e funcional.

O que foi usado?
- Arduino UNO – o cérebro do sistema
- Sensor Ultrassônico HC-SR04 – para medir a distância até a água
- LED vermelho – alerta visual
- Buzzer – alerta sonoro
- Protoboard e jumpers – montagem do circuito
- Simulador Wokwi – pra testar tudo sem precisar dos componentes reais

Como funciona?
Assim que o sistema é ligado, o sensor começa a monitorar a distância. Se detectar que a água está chegando perto (distância menor que 200 cm), ele ativa os alarmes.

Regras da lógica:
- Se a distância for maior ou igual a 200 cm, tudo normal — sem alerta.
- Se a distância for menor que 200 cm, LED + buzzer ativados — perigo detectado.

Tudo isso é processado em tempo real pelo Arduino.


Simulação online
Você pode testar esse sistema no Wokwi clicando aqui:

👉 [Acessar projeto no Wokwi](https://wokwi.com/projects/375913265503799297)
👉 [Acessar o video do projeto](https://youtu.be/zUh-S85iZyY?si=oM6xf2izHVM9vQ4W)
