Bem-vindo, este repositório contém alguns projetos de circuitos feitos no Tinkercad com aplicações diversas.

## Sobre o Projeto

Esse repositório foi criado com o propósito de aprimorar as minhas habilidades em programação e em eletrônica. Aqui você encontrará:

- Vídeos, fotos e os códigos dos circuitos
- Uma breve explicação de como foram feitos
- Descrições sobre como poderiam ser usados
  
---

## Estrutura do Repositório

- `images/`: Contém imagens e capturas de tela dos projetos.
- `code/`: Contém os códigos fonte (.ino, .py, etc.).
- `README.md`: Documentação detalhada sobre o projeto.

# -__Sensor de Distância__-

## Materiais usados:
- 1 Arduino Uno R3
- 1 Ultrasonic Distance Sensor
- 1 Piezo (buzzer)
- 3 LEDs
- 3 Resistores 220Ω

## finalidade:
- Pode ser usado como sensor de proximidade de um carro por exemplo,
  dá um aviso sonoro de quando o carro está muito próximo à algum objeto quando o motorista estiver tentando estacionar.
- Também pode ser usado para impedir que algum animal de estimação entre em algum lugar que não deve, ativando o aviso sonoro
  e espantando o animal para outro lugar.  

## como foi feito:
### Funcionalidades importantes:
- **Detecção de distância**: O sensor ultrassônico permite medir distâncias com precisão, sendo essencial para calcular o momento de ativar os alertas visuais e sonoros.
- **Feedback sonoro e visual**: Os LEDs e o buzzer foram configurados para fornecer alertas de proximidade, simulando sistemas reais de estacionamento assistido.
- **Versatilidade**: Este projeto pode ser adaptado facilmente para diversas aplicações, como robótica, segurança e automação residencial.

### Dificuldades encontradas:
- **Calibração do sensor**: Ajustar as medições do sensor ultrassônico para evitar leituras incorretas devido a interferências ou reflexos inesperados foi um desafio.
- **Sincronização dos alertas**: Foi necessário ajustar o código para garantir que os LEDs e o buzzer fossem acionados no tempo certo, evitando atrasos ou falhas.
- **Montagem no protoboard**: A organização dos componentes no protoboard exigiu atenção para evitar conexões erradas, especialmente ao trabalhar com resistores e LEDs.

---------------

## -__Sensor de Temperatura__-

## Materiais usados:
- 1 Arduino Uno R3
- 1 Temperature Sensor [TMP36]
- 1 Breadboard Small (protoboard)
- 1 Piezo (buzzer)
- 3 LEDs
- 3 Resistores 220Ω

## Finalidade:
- Pode ser usado em residências por exemplo, se a temperatura da cozinha estiver muito alta, haverá um aviso sonoro.
- Também pode ser usado na criação de animais ou na incubação de ovos, já que monitorar a temperatura do ambiente nesses casos
  é essencial

## Como foi feito:
### Funcionalidades importantes:
- **Monitoramento em tempo real**: O sensor TMP36 permite capturar mudanças de temperatura em tempo real, sendo ideal para uso em aplicações como monitoramento doméstico ou incubadoras.
- **Alertas programáveis**: Os LEDs e o buzzer são ativados automaticamente quando a temperatura ultrapassa os limites pré-definidos, proporcionando segurança e praticidade.
- **Versatilidade de aplicação**: O projeto pode ser adaptado para monitorar ambientes variados, como cozinhas, viveiros de animais ou até mesmo data centers.

### Dificuldades encontradas:
- **Interpretação dos sinais do sensor**: Foi necessário ajustar a leitura do sensor TMP36 para garantir medições precisas, considerando fatores como ruído no circuito e desvios de tensão.
- **Definição dos limites de temperatura**: Determinar os valores ideais para os alertas exigiu testes e ajustes para atender a diferentes aplicações.
- **Integração com os alertas**: Sincronizar os LEDs e o buzzer com base nas mudanças de temperatura foi um desafio, especialmente para evitar falsos positivos ou atrasos.
