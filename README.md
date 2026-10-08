## 👥 Integrantes

* Arthur Massarão Marcomini
* Gabriela de Oliveira
* Maria Eduarda Rocha Castro
* Mateus Aristóteles Fernandes

**Curso:** Técnico em Desenvolvimento de Sistemas
**Instituição:** SENAI A. Jacob Lafer
**Ano:** 2026

<br>

# 🐾 Smart Pet Feeder

Alimentador pet automatizado e inteligente desenvolvido com **ESP32** e conceitos de **Internet das Coisas (IoT)**.

O sistema permite liberar ração por meio de um botão, utilizando um servo motor para controlar a comporta. O projeto também possui LCD 16x2, LED RGB, conexão Wi-Fi e registro das alimentações no Firebase.

## ⚙️ Funcionamento

- 🔘 Botão → inicia a alimentação
- ⚙️ Servo Motor → abre e fecha a comporta
- 📺 LCD 16x2 → exibe informações
- 💡 LED RGB → indica o estado do sistema
- 📡 ESP32 + Wi-Fi → realiza a comunicação
- ☁️ Firebase → armazena os registros

## 🧩 Tecnologias

- ESP32
- C/C++
- Wokwi
- Wi-Fi
- Firebase Realtime Database
- NTP
- Servo Motor
- LCD 16x2
- LED RGB

<br>

<p align="center">
  <img src="./img/imagem (1).png" width="800">
</p>

## 🏗️ Arquitetura

```text
[Botão]
   ↓
[ESP32]
   ↓
[Servo + LED + LCD]
   ↓
[Wi-Fi]
   ↓
[Firebase]
````

## 💰 Viabilidade

| Componente  | Qtd. |         Valor |
| ----------- | ---: | ------------: |
| ESP32       |    1 |      R$ 40,75 |
| Servo Motor |    1 |      R$ 52,25 |
| LED RGB     |    1 |       R$ 0,86 |
| Push Button |    1 |       R$ 0,57 |
| LCD 16x2    |    1 |      R$ 16,06 |
| **Total**   |      | **R$ 110,49** |

## 🔗 Wokwi

[Visualizar circuito no Wokwi](https://wokwi.com/projects/476797194471556097)


```
