# 📝 Editor de Texto com Análise de Coesão e Coerência
Este projeto foi desenvolvido como parte do **Exercício de Programação Final (EPF)**, com o objetivo de criar uma ferramenta educativa em Python que auxilie na escrita e revisão de textos.
A aplicação permite que o usuário digite ou cole um texto e receba uma análise automática focada em **coesão e coerência textual**, apontando elementos como repetição de palavras, tamanho das frases e presença de conectores.

## 🚀 Funcionalidades

- Inserção de texto livre via terminal
- Análise de frases longas e curtas
- Detecção de palavras muito repetidas
- Verificação de conectores por tipo:
  - **Aditivos** (e, também, além disso)
  - **Adversativos** (porém, contudo, mas)
  - **Conclusivos** (portanto, logo, assim)
  - **Explicativos** (porque, pois, já que)
  - **Alternativos** (ou, ou então)
- Sugestões de melhoria com base na ausência ou presença desses conectores
- Salvamento do texto em arquivo `.txt`

## 💻 Como usar

1. **Abra o código no Google Colab** (ou execute localmente com Python 3)
2. Escolha uma opção no menu:
   - `1`: Inserir novo texto
   - `7`: Salvar texto como `.txt`
   - `8`: Analisar coesão e coerência do texto
