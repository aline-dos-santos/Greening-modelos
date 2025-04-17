
## Modelos Utilizados

Foram treinados cinco modelos diferentes para comparação de desempenho:

- YOLOv7
- YOLOv8
- YOLOv9
- YOLOv11
- YOLOv12

## 🥇 Melhor Modelo: YOLOv9

Após o processo de treinamento e avaliação, o modelo **YOLOv9** obteve os **melhores resultados de precisão e desempenho geral**, superando as demais versões. Por isso, **foi o escolhido como base para o tutorial de uso**.

## 📚 Tutorial de Uso

No notebook `tutorial_treinamento_yolov9.ipynb`, você encontrará:

- Explicação da estrutura de dados
- Etapas de pré-processamento
- Treinamento do modelo YOLOv9
- Avaliação dos resultados
- Inferência em novas imagens

---

## 🚀 Requisitos

- Python ≥ 3.8
- PyTorch ≥ 2.x
- CUDA (para uso com GPU)
- YOLOvX (dependendo do modelo)
- Outros: `wandb`, `opencv`, etc.

## 📌 Observações

- Os modelos estão salvos na pasta `Pesos/` com os nomes respectivos.
- Para reproduzir os experimentos, verifique os caminhos em `data.yaml` e ajuste conforme a organização do seu Colab ou sistema local.

---

## 👨‍🔬 Autor

Projeto desenvolvido por Aline dos Santos, com orientação de Prof. Samuel Baraldi Mafra como parte de estudos no desenvolvimento de uma armadilha  multiculturas baseada em IoT e IA.

