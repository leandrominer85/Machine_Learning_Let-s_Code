# Machine_Learning_Let-s_Code
 
Pi 373 - Módulo 7 - Machine Learning
Crédito para Veículos - Especificação do Projeto
Deadline

    Dia 12/10/2020, às 23h50.

Contextualização

A PyCoders Ltda., cada vez mais especializada no mundo da Inteligência Artificial e Ciência de Dados, foi procurada por uma fintech para desenvolver um projeto de concessão de crédito para veículos. Nesse projeto, espera-se a criação de valor que discrimine ao máximo os bons pagadores dos maus pagadores. Para isso, foi disponibilizada uma base de dados com mais de 185 mil casos de empréstimos do passado com diversas características dos clientes. Devem ser entregues um modelo. Por questões contratuais, o pagamento será realizado baseado no desempenho (gini) do modelo ao longo do tempo.
Base de Dados

Será utilizada uma base de dados com informações cadastrais e histórico de crédito de clientes indianos. O conjunto de dados está dividido em treino e teste sem variável resposta, todos no formato pickle comprimido com gzip. Para leitura, basta executar df = pd.read_pickle('nome_do_arquivo.pkl.gz'). Toda a modelagem e validação deve ser feita em cima do conjunto de treino, subdividindo tal base como a squad achar melhor. Existe também os metadados das variáveis explicativas, para ajudar no desenvolvimento do projeto.
