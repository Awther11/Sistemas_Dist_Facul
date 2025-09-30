Atividade 1 - RabbitMQ

Descrição

    Esta atividade tem como objetivo demonstrar a comunicação entre processos utilizando RabbitMQ em Python. Foram implementados scripts simples de envio e recebimento de mensagens.

Antes da criação dos arquivos, foi gerado um ambiente virtual para que as dependências não fossem instaladas em toda a máquina (python -m venv venv). Em seguida, em uma pasta fora do ambiente virtual, foram desenvolvidos os arquivos do projeto.

Ferramentas Utilizadas:

    Linguagem: Python
    Biblioteca: pika (para integração com RabbitMQ)
    Servidor de Mensageria: RabbitMQ
    Ambiente Virtual: venv
    Processo de Execução
    Criar e ativar o ambiente virtual:
    python -m venv venv


Instalar dependências:

    pip install pika

Certificar-se de que o servidor RabbitMQ está em execução.
Executar o arquivo send.py para enviar mensagens:

    python send.py

Executar o arquivo received.py para receber e exibir mensagens no terminal:

    python received.py

Arquivos Criados:

    send.py: Responsável por enviar dados/mensagens, neste caso um "Hello World".
    received.py: Responsável por receber as informações enviadas em tempo de execução, exibindo no terminal a mensagem pela quantidade de vezes em que for enviada.
    Resultado Esperado

O resultado esperado consistia no envio e recepção de mensagens entre os dois scripts, o que foi realizado com sucesso. Ao rodar o sistema, as mensagens enviadas pelo send.py foram corretamente captadas e exibidas pelo received.py.

