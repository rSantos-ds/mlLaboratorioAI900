# mlLaboratorioAI900
Laboratorio AI900 de machine learning do link https://aka.ms/ai900-auto-ml

Passos para realizar as atividades do laboratório:

1 - Acessar o portal do azure em https://portal.azure.com
2 - Acessar o serviço do Azure Machine Learning (localizar no painel vertical ou realizar pesquisa pelo nome do serviço)

![image](https://github.com/user-attachments/assets/7c37ebca-a0cf-4d51-9456-43d135598b49)

3 - Criar um novo workspace

![image](https://github.com/user-attachments/assets/30bb47b4-b9df-48ef-a0e7-fc6475014e9a)

4 - Preencher os campos de acordo com os dados mencionados na documentação do exercício

![image](https://github.com/user-attachments/assets/ed5c029b-5cd2-427f-8c0c-19009d39fbd9)

5 - Clicar na aba review + create, sera avaliado se está tudo ok, estando com status liberado continuar clicando em create.

![image](https://github.com/user-attachments/assets/8144ba25-e9e9-4122-8865-6d2b4ce6a952)

6 - Aguardar a criação do workspace.

![image](https://github.com/user-attachments/assets/817209e3-7515-485b-96e6-f35bf041fccd)

7 - No painel configurar permissões de IAM, clicando em adicionar e na barra de pesquisa procurar por Microsoft.MachineLearningServices/workspaces/datastores/listsecrets/action, selecionar Azure AI Administrator e clicar em next.

![image](https://github.com/user-attachments/assets/09ce87e8-fda2-45cf-9e16-de91cc6e665c)

![image](https://github.com/user-attachments/assets/9114762f-b97b-4a34-b1f7-365b2ecc8f3c)


8 - Em membros clicar em + Select Members e procurar pelo email associado a conta em que esta associada a subscrição utilizada e selecionar, entao clicar em select. Depois clicar em next.

 ![image](https://github.com/user-attachments/assets/fdf50cff-53cc-4838-aa10-f94da2c4ef58)

 9 - em Review + Assign clicar no botao "Review + Assign" para atualizar as configurações.

 
 10 - Voltar a aba Overview e clicar para ir ao machine learning studio, devera ja abrir no workspace criado, caso não apenas selecionar o mesmo.

![image](https://github.com/user-attachments/assets/df47061d-ddfb-450d-afb5-fe8367f40bb3)

![image](https://github.com/user-attachments/assets/e77d1fc4-81c6-4d30-ad89-7e076ed9d854)


11 - Selecionar no painel lateral a opção ML Automatizado, depois clicar em "Novo trabalho de ml automatizado" e preencher conforme mencionado no documento, campo nome do trabalho foi mantido o que foi gerado automaticamente.

![image](https://github.com/user-attachments/assets/d3fad8ae-57ea-4a77-8457-0146811e327d)


12 - Selecionar a tarefa como regressão e cicar para criar ativos de dados, escolhendo de acordo com o mencionado no documento a opção  Table (mltable).

![image](https://github.com/user-attachments/assets/ccf6f028-dce1-4fe1-816b-3ff219a546a3)

13 - Na fonte de dados escolher "de arquivos locais", será preciso baixar os arquivos disponibilzados no link https://aka.ms/bike-rentals para seleciona-los depois. clicando em avançar, na próxima tela escolher a opção  Azure Blob Storage em tipo de armazenamento e selecionar workspaceblobstore na lista.

![image](https://github.com/user-attachments/assets/24120640-9fbb-4286-bd64-c9db2968884a)

14 - clicar em carregar pasta e escolher a pasta contendo os arquivos que foram baixados.

![image](https://github.com/user-attachments/assets/a2b0a940-5995-4405-b3e5-5898f869d980)

15 - Clicar em criar na próxima tela.

 clicar no nome permitira visualizar os dados.

![image](https://github.com/user-attachments/assets/2d10f3ad-cc98-40bd-ba18-c0b22b444791)

![image](https://github.com/user-attachments/assets/902b8cdc-8de8-4d49-924b-219beaa5af43)

16 - Clicando em avançar, na tela seguinte em "coluna de destino", escolher "rentals (integer)", clicar em configurações adicionar e preencher conforme itens abaixo do documento:

![image](https://github.com/user-attachments/assets/821c5681-1294-4b5c-8103-e62ddcc55351)

![image](https://github.com/user-attachments/assets/42a778fe-223b-4ac8-9d03-e655af6e9b74)

os limites e tipo de validação configurar conforme documento.

![image](https://github.com/user-attachments/assets/12394469-4c9c-437c-96fa-2ccaa9729a6b)


17 - Próxima tela também configurar de acordo com o documento.

![image](https://github.com/user-attachments/assets/c419ed76-3609-4527-ae96-acd7aa19ce40)

18 - por fim clicar em "Enviar trabalho de treinamento" e aguardar até que seja concluido, estarar concluido quando for indicado no campo apontado abaixo.

![image](https://github.com/user-attachments/assets/f1b09bcb-de65-467f-b677-5f6fd3639b20)

19 - após concluido clicar no nome do algoritmo para visualizar os detalhes do modelo.

![image](https://github.com/user-attachments/assets/cef9061c-ffc0-4606-a025-a814d4512a0a)

![image](https://github.com/user-attachments/assets/7be13831-4d54-434e-b469-9f5aea108093)

é possivel visualizar detalhes das metericas clicando em "exibir todas as outras métricas", sera de forma resumida ou é possivel selecionar a aba "Métricas"

![image](https://github.com/user-attachments/assets/5ddab3b1-64d2-4f84-aad9-8442ad6f2d24)


20 - Na aba "Modelo" clicar em "Implantar", escolher "Terminal em tempo real" e configurar conforme mencionado no documento:

IMPORTANTE: A PARTIR DESTE PONTO NÃO FOI POSSÍVEL PROSSEGUIR (TALVEZ DEVIDO A ALGUMA LIMITAÇÃO DO PLANO TRIAL), TEM APRESENTADO O PROBLEMA ABAIXO SEGUINDO OS PASSOS DO DOCUMENTO, NÃO PERMITINDO ESCOLHER A OPÇÃO REQUIRIDA E AO UTILIZAR OUTRA OPÇÃO RETORNA FALHA AO TENTAR CRIAR.

![image](https://github.com/user-attachments/assets/346fc8cd-66d2-4838-ab19-a23b9af054b1)









