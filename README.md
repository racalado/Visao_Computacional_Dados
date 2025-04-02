# Visão Computacional para Contagem de Dados

Este projeto utiliza técnicas de visão computacional para identificar e somar os valores de dados (dados de jogar) em uma imagem. Ele faz uso da biblioteca OpenCV para processamento de imagem e detecção de blobs, permitindo reconhecer os pontos nos dados e calcular sua soma total.

## Tecnologias Utilizadas
- Python 3
- OpenCV
- NumPy
- Matplotlib

## Funcionalidades
- Carregamento de imagem
- Conversão para escala de cinza
- Limiarização adaptativa para destacar os dados
- Detecção de contornos para identificar os dados
- Uso de detector de blobs para contar os pontos nos dados
- Soma total dos valores detectados

## Como Utilizar
1. Certifique-se de ter o Python 3 instalado em seu ambiente.
2. Instale as dependências necessárias:
   ```bash
   pip install opencv-python numpy matplotlib
   ```
3. Execute o script fornecendo o caminho de uma imagem contendo dados:
   ```python
   from visao_computacional_dados import count_dice_points

   image_path = "caminho/para/imagem.jpg"
   points = count_dice_points(image_path)
   print("Pontos em cada dado:", points)
   print("Soma total dos pontos:", sum(points))
   ```

## Exemplo de Uso
Caso a imagem contenha três dados com valores 3, 5 e 2, a saída será:
```
Pontos em cada dado: [3, 5, 2]
Soma total dos pontos: 10
```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Exemplo

![DADOS](red_dices.jpg)

