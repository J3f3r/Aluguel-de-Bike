# Aluguel de Bike
## Aprendizado de máquina automatizado para previsão de aluguel de bicicletas

Foi usado um conjunto de dados históricos de aluguel de bicicletas para treinar um modelo. O modelo prevê o número de aluguéis de bicicletas esperados num determinado dia, com base em características sazonais e meteorológicas .

## Etapas

No portal do Azure foi criado um recurso do Azure Machine Learning com minha assinatura de estudante, foi criado um nome exclusivo e mantendo a região dos EUA. Depois de revisado e criado o espaço de trabalho foi iniciado o Studio ML para utilizar algumas funcionalidades para gerar um aprendizado de máquina automatizado para prever futuros aluguéis de bike com base em histórico de dados.
Foi selecionado o tipo de tarefa Regressão, tipo de dados Tabular, fonte de dados de arquivos da Web coma URl ---. Os modelos selecionados foram RandonmForest e LightGBM. Foi configurado Tarefa, Limites e Validação de Testes.
Após implantar e testar o serviço em Endpoints, foi utilizado um código JSON para obter um número previsto de aluguéis


## 📄 Documentação utilizada
[Documentação Microsoft] (https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)

## 🔍 Referências 
- [Digital Inovation One](https://web.dio.me/).
