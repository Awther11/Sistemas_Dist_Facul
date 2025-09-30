Atividade 2 - RabbitMQ

Descrição

Esta atividade tem como objetivo demonstrar o funcionamento de filas de tarefas utilizando RabbitMQ em Python. Foram desenvolvidos dois arquivos principais, responsáveis por enviar e processar mensagens em uma fila.

Ferramentas Utilizadas:

    Linguagem: Python
    Biblioteca: pika
    Servidor: RabbitMQ

Processo de Execução:

    Instalar a biblioteca necessária (pip install pika)

Certificar-se de que o servidor RabbitMQ está em execução.
Executar o arquivo worker.py para que ele fique aguardando mensagens na fila:

    python worker.py

Executar o arquivo new_task.py para enviar mensagens/tarefas para a fila:
python new_task.py "Mensagem da tarefa"

Arquivos Criados:

    new_task.py: Responsável por criar e enviar novas tarefas para a fila de mensagens.
    worker.py: Responsável por receber e processar as tarefas enviadas, exibindo-as no terminal.

Resultado Esperado:

    O resultado esperado envolvia o envio de mensagens pelo new_task.py e no recebimento e processamento dessas mensagens pelo worker.py. O comportamento foi confirmado em execução: as tarefas enviadas foram corretamente captadas e processadas pelo worker.
