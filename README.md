# Sistema de reconhecimento facial

Protótipo académico de reconhecimento facial desenvolvido em colaboração com uma colega.

## O que faz

- Capta vídeo através da webcam.
- Deteta rostos e compara as características faciais com utilizadores registados.
- Permite registar um utilizador através da tecla `c` quando existe um rosto visível.
- Apresenta o resultado de acesso e regista eventos de autorização ou recusa.

## Tecnologias

Python, OpenCV, NumPy, InsightFace e ONNX Runtime.

## Executar

1. Crie e ative um ambiente virtual Python.
2. Instale as dependências com `pip install -r requirements.txt`.
3. Execute `python reconhecimento.py` com uma webcam disponível.
4. Prima `c` para registar um rosto e `q` para terminar.

O programa cria as pastas e o ficheiro local de utilizadores na primeira execução. Este repositório não contém imagens faciais, embeddings ou registos de utilizadores. Não adicione dados biométricos reais, ficheiros `utilizadores.json` ou `logs.txt` ao GitHub.

Este projeto é um protótipo de aprendizagem e não um sistema de segurança pronto para utilização real.
