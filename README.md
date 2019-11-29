# chat-online-shell_script
Para o funcionamento do chat, é necessário que o servidor possua o subpacote ncat presente no pacote do nmap e o cliente possua o pacote tmux.

Como executar o servidor:

./servidor_in.sh --------- Servidor que irá receber as mensagens de todos os clientes que estão no chat; 

./servidor_out.sh ----------------- Servidor que irá enviar as mensagens para todos os clientes que estão no chat;

ps: Ambos servidores devem ser executados na mesma máquina. 

Como executar o cliente: 

./tela.sh ------------- Máquina onde o cliente irá executar. 

ps: Após executar o cliente, o mesmo deve passar o ip do servidor e porta( que por padrão é a 9000) que o servidor irá escutar para conectar-se aos clientes. 

