# Azure-ML

Descrição

Este projeto demonstra o uso do Azure Machine Learning para realizar reconhecimento facial e transformar imagens em dados estruturados. O objetivo é extrair informações relevantes de imagens, como características faciais, que podem ser usadas em análises avançadas.

🛠️ Tecnologias Utilizadas

Azure Machine Learning: Plataforma para criação e gerenciamento de modelos de machine learning.

Python: Linguagem de programação principal do projeto.

azure-cognitiveservices-vision-face: Para integração com o serviço de reconhecimento facial do Azure.

pandas: Para manipulação de dados.

matplotlib: Para visualização de resultados.

🚀 Como Executar o Projeto

Instale as dependências:

pip install -r requirements.txt

Configure suas credenciais do Azure no script reconhecimento_facial.py.

Execute o script:

python scripts/reconhecimento_facial.py

🔍 Processo e Racional

Upload das Imagens: As imagens foram organizadas na pasta inputs/.

Configuração do Azure ML: Configuramos o serviço de reconhecimento facial para identificar características faciais como emoções, idade estimada, entre outros.

Extração de Dados: Os dados extraídos foram salvos em arquivos JSON na pasta output/.

Análise de Dados: Utilizamos Python para processar e visualizar os resultados.

💡 Insights e Possibilidades

O reconhecimento facial no Azure é eficiente para identificar múltiplas características faciais em diferentes cenários.

A combinação com Python permite automatizar o processo e realizar análises mais avançadas.

Possibilidades de uso incluem segurança, autenticação biométrica, e análise comportamental.

Projeto desenvolvido para fins de aprendizado e aprimoramento de habilidades em Machine Learning e Azure.
