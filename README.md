# MAML-work-in-progress

INGREDIENTES:

python==2.7 numpy tensorflow==1.3.0. matplotlib (creio que os demais pacotes já sejam internos aos python 2.7)

INSTRUÇÕES:

As instruções pra rodar o código estão no topo do arquivo main.py. Esse código possui um sistema de FLAGS que modifica as variáveis do código de acordo os comandos dados na execução.

Você precisará baixar o dataset miniimagenet e copia-lo para o diretório data/miniImagenet. Você pode baixá-lo como três arquivos .csv que pode ser pré-processado com o arquivo que já está dentro desse diretório "proc_images.py" ou, pode baixa-lo já como um conjunto de pastas separadas por classe dentro de três pastas "train", "val" e "test" (que é o que o proc_images tem intuito de fazer). Estando nesse formato, você consegue rodar a rede.

Infelizmente não consigo me lembrar de onde achei, e acaba sendo um número grande de dados pra fazer upload aqui. Procurei pela rede pelo local exato de onde achei e não vi, mas talvez possa ter sucesso num desses links:
https://github.com/yaoyao-liu/mini-imagenet-tools
https://drive.google.com/file/d/0B3Irx3uQNoBMQ1FlNXJsZUdYWEE/view
https://drive.google.com/file/d/16V_ZlkW4SsnNDtnGmaBRq2OoPmUOc5mY/view
https://www.kaggle.com/whitemoon/miniimagenet

Encontrei problemas pra rodar o proc_images.py e, depois de falhar algumas vezes pra rodá-lo, acabei realizando a extração manualmente até ficar nesse formato (três pastas "train", "val" e "test").

A propósito, você tem acesso a algum cluster? Acho que talvez a rede possa ser meio pesada pra rodar na máquina.
