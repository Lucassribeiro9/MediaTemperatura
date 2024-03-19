# MediaTemperatura

Este projeto realiza análise de dados de temperatura, permitindo carregar um arquivo de dados e exibir informações relevantes sobre as medições.

## Instalação

Para instalar e executar o projeto, siga as etapas abaixo:

1. Certifique-se de ter o Python instalado em seu ambiente.
2. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/seu-usuario/MediaTemperatura.git
   ```

3. Navegue até o diretório do projeto:

   ```bash
   cd MediaTemperatura
   ```

4. Instale as dependências necessárias:

   ```bash
   pip install -r requirements.txt
   ```

## Uso

Para utilizar o projeto e visualizar os dados, siga as etapas abaixo:

1. Execute o script `main.py` para carregar o arquivo de dados:

   ```bash
   python main.py
   ```

2. O arquivo será carregado e as informações serão exibidas no console.
3. Você também pode visualizar o DataFrame resultante usando o matplotlib:

   ```python
   import matplotlib.pyplot as plt
   plt.plot(dados['data'], dados['precip'])
   plt.xlabel('Data')
   plt.ylabel('Precipitação (mm)')
   plt.title('Gráfico de Precipitação')
   plt.show()
   ```

Este projeto é útil para análise e visualização de dados de temperatura. Sinta-se à vontade para contribuir e expandir suas funcionalidades!