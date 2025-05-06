# Bem-vindo

Este repositório contém alguns projetos de circuitos feitos no Tinkercad com aplicações diversas.

---

## Sobre o Projeto

Esse repositório foi criado com o propósito de aprimorar as minhas habilidades em programação e em eletrônica. Aqui você encontrará:

✔ **Vídeos, fotos e os códigos dos circuitos**  
✔ **Uma breve explicação de como foram feitos**  
✔ **Descrições sobre como poderiam ser usados**

---

## Estrutura do Repositório

📁 `images/`: Contém imagens e capturas de tela dos projetos.  
📁 `code/`: Contém os códigos fonte (.ino, .py, etc.).  
📄 `README.md`: Documentação detalhada sobre o projeto.

---

# __Sensor de Distância__

### Materiais usados:
- 🛠 1 Arduino Uno R3  
- 📏 1 Ultrasonic Distance Sensor  
- 🔔 1 Piezo (buzzer)  
- 💡 3 LEDs  
- 🔌 3 Resistores 220Ω  

### Finalidade:
➡ Pode ser usado como sensor de proximidade de um carro, emitindo um aviso sonoro quando o carro estiver muito próximo de algum objeto, facilitando o estacionamento.  
➡ Também pode impedir que animais de estimação entrem em locais indesejados, ativando o aviso sonoro para espantá-los.

### Como foi feito:
#### Funcionalidades importantes:
- 📏 **Detecção de distância**: O sensor ultrassônico mede distâncias com precisão, determinando quando ativar os alertas visuais e sonoros.  
- 🔔 **Feedback sonoro e visual**: LEDs e o buzzer fornecem alertas de proximidade, simulando sistemas de estacionamento assistido.  
- 🔄 **Versatilidade**: O projeto é facilmente adaptável para aplicações como robótica, segurança e automação residencial.

#### Dificuldades encontradas:
- ⚙ **Calibração do sensor**: Ajustar as medições do sensor para evitar leituras incorretas devido a interferências foi desafiador.  
- ⏱ **Sincronização dos alertas**: Foi necessário ajustar o código para que os LEDs e o buzzer funcionassem no tempo correto, evitando falhas.  
- 🧩 **Montagem no protoboard**: A organização dos componentes exigiu atenção para evitar erros nas conexões, especialmente ao trabalhar com resistores e LEDs.

---

## __Sensor de Temperatura__

### Materiais usados:
- 🛠 1 Arduino Uno R3  
- 🌡 1 Temperature Sensor [TMP36]  
- 🔌 1 Breadboard Small (protoboard)  
- 🔔 1 Piezo (buzzer)  
- 💡 3 LEDs  
- 🔌 3 Resistores 220Ω  

### Finalidade:
➡ Pode ser usado em residências para emitir um aviso sonoro caso a temperatura da cozinha fique muito alta.  
➡ Ideal para monitoramento de temperatura em incubadoras ou na criação de animais, onde a temperatura ambiente é essencial.

### Como foi feito:
#### Funcionalidades importantes:
- 🌡 **Monitoramento em tempo real**: O sensor TMP36 permite capturar mudanças de temperatura em tempo real, ideal para várias aplicações.  
- 🔔 **Alertas programáveis**: LEDs e o buzzer são ativados automaticamente quando a temperatura ultrapassa os limites definidos.  
- 🔄 **Versatilidade de aplicação**: Pode monitorar cozinhas, viveiros de animais e até data centers.

#### Dificuldades encontradas:
- ⚙ **Interpretação dos sinais do sensor**: Ajustar a leitura do sensor para garantir medições precisas foi desafiador.  
- 📊 **Definição dos limites de temperatura**: Determinar os valores ideais para os alertas exigiu testes e ajustes.  
- ⏱ **Integração com os alertas**: Sincronizar LEDs e buzzer com as mudanças de temperatura foi um desafio para evitar falsos positivos ou atrasos.
