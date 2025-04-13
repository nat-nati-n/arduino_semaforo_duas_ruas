# 🚦 Projeto Semáforo de Duas Ruas com Arduino

Este projeto simula a lógica de controle de **semáforos para duas ruas**, utilizando LEDs para representar os sinais de trânsito. O semáforo da **Rua 1 inicia com o LED verde aceso**, enquanto a **Rua 2 começa com o vermelho**. A alternância entre as duas vias é feita de forma sincronizada.

---

## 📅 Aula 06 - Programa 04  
📆 Data: 20/03/2025  
👩‍💻 Criado por: **Natalia**

---

## 🔧 Materiais Utilizados
- 1x Placa Arduino UNO  
- 6x LEDs (2 verdes, 2 amarelos, 2 vermelhos)  
- 6x Resistores de 330Ω  
- Protoboard  
- Jumpers

---

## 📌 Pinos Utilizados
### Rua 1:
- LED Verde → Pino **5**
- LED Amarelo → Pino **4**
- LED Vermelho → Pino **3**

### Rua 2:
- LED Verde → Pino **13**
- LED Amarelo → Pino **12**
- LED Vermelho → Pino **11**

---

## 🔁 Funcionamento do Semáforo

1. **Início:**
   - Verde da Rua 1 ligado
   - Vermelho da Rua 2 ligado

2. Após 8 segundos:
   - Rua 1 → Amarelo por 2 segundos
   - Depois, Vermelho

3. Simultaneamente:
   - Rua 2 → Verde por 8 segundos
   - Depois, Amarelo por 2 segundos

4. O ciclo se reinicia.

---

## 🔗 Simulação no Tinkercad
👉 (https://www.tinkercad.com/things/l4Nons3Hx04-semaforo-de-duas-ruas-/editel?returnTo=%2Fthings%2Fl4Nons3Hx04-semaforo-de-duas-ruas-)

---

## 📂 Arquivo do Código

O código do projeto está disponível no arquivo `semaforo_duas_ruas.ino`.

Se quiser, você pode fazer upload direto para sua placa Arduino e ver a lógica em ação!

---

📌 Projeto criado com fins educacionais para simular sistemas de controle de tráfego com Arduino.
