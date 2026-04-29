# FarmTech Solutions — Sistema de Visão Computacional
### FIAP — Fase 6 | Redes Neurais & Visão Computacional

## Integrantes
- William Albert Cesário Vasconcelos
- Pedro Alves da Silva (RM 567029)
- Douglas Rafael do Amaral
- Cláudio Sartori

---

## Sobre o Projeto

A FarmTech Solutions está expandindo seus serviços de IA para a área de **visão computacional**. Neste projeto, desenvolvemos um sistema capaz de detectar e classificar dois objetos distintos em imagens:

- **Controle de PS4** (DualShock 4)
- **Livro**

Foram implementadas e comparadas três abordagens:
1. YOLOv5 customizado (treinado na nossa base)
2. YOLO padrão pré-treinado (COCO)
3. CNN treinada do zero

---

## Resultados

| Abordagem | Precisão | Observação |
|-----------|----------|------------|
| YOLOv5 Customizado (60ep) | mAP@0.5: 99.5% | Melhor para detecção com localização |
| YOLO Padrão (COCO) | — | Não reconhece controle_ps4 |
| CNN do Zero | 100% acurácia | Apenas classificação |

---

## Notebook

Todo o passo a passo da solução está documentado no notebook Jupyter:

🔗 https://colab.research.google.com/drive/1ZlXaOqNdTsuJwUllC4bMOTEc9ddlvbWE?usp=sharing

---

## Vídeo Demonstrativo

🎥 https://youtu.be/qqtAVACLEoE



## Tecnologias Utilizadas

- Python 3
- YOLOv5
- TensorFlow / Keras
- Google Colab
- Make Sense AI (rotulação)
