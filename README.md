# Reconhecimento de Personagens - Two and a Half Men & Reconhecimento de Objetos usando a WebCam em tempo real

## Sobre o Projeto
Este projeto implementa um sistema de detecção de objetos usando YOLOv8, com dois objetivos principais:
1. Reconhecimento dos personagens principais da série "Two and a Half Men" (Charlie, Alan e Jake)
2. Demonstração de detecção de objetos em tempo real usando webcam

O projeto foi inteiramente desenvolvido no Google Colab, permitindo fácil acesso e execução sem necessidade de configuração local.

### Notebook Original
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/155CGi44G_qBSTjT88l9svPjP7xIzdGRt#scrollTo=3MISNbxkIAhE)

> **Nota**: Você pode acessar e executar o projeto diretamente no Google Colab através do link acima.

## Características
- Treinamento personalizado da YOLOv8 para reconhecimento de personagens
- Interface interativa para captura e detecção via webcam
- Detecção em tempo real de 80 classes diferentes (modelo COCO)
- Processamento de imagens estáticas e stream de vídeo

## Tecnologias Utilizadas
- Python 3.x
- YOLOv8
- OpenCV
- TensorFlow/PyTorch
- Google Colab
- JavaScript (para interface webcam)

## Dataset
- Dataset personalizado dos personagens de Two and a Half Men
- Disponível no Kaggle: [Two and a Half Men Dataset](https://www.kaggle.com/rafaelbortoluzzi/two-and-a-half-men)
- Classes: Charlie, Alan e Jake
- Inclui 4 imagens de teste na pasta 
`Samples`
:
  - test1.jpg
  - test2.jpg
  - test3.jpg
  - test4.jpg
- As imagens de teste são utilizadas para demonstrar o funcionamento do modelo treinado

## Como Usar
1. Abra o notebook no Google Colab
2. Execute as células em sequência
3. Para treinamento personalizado:
   - Configure suas credenciais Kaggle
   - Execute o treinamento (recomendado: YOLOv8l, 100 épocas)
4. Para teste com webcam:
   - Permita acesso à webcam quando solicitado
   - Use os controles na interface para captura e detecção

## Estrutura do Projeto
- Preparação e configuração do ambiente
- Download e organização do dataset
- Treinamento do modelo YOLOv8
- Teste com imagens estáticas
- Detecção via webcam (captura única)
- Detecção em tempo real (streaming)

## Requisitos
- Conta Google (para Colab)
- Conta Kaggle (para dataset)
- Webcam (para testes em tempo real)
- GPU recomendada para treinamento

## Resultados
- Detecção precisa dos personagens principais
- Tempo real com baixa latência
- Visualização clara com bounding boxes e níveis de confiança

## Licença
MIT License - veja [LICENSE](LICENSE) para mais detalhes

## Autor
*Rafael Bortoluzzi*

*rafaeldnbr@hotmail.com*

## Agradecimentos
- Two and a Half Men (série)
- Ultralytics (YOLOv8)
- Google Colab
