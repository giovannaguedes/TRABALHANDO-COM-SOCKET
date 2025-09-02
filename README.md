# TRABALHANDO-COM-SOCKET
Código montando um socket em python. Automatizado.

⚠️ Uso exclusivo para fins educacionais • Desenvolvido por M!ss s3c

📝 Guia: Criando e executando um script Python com socket

Esse script vai tentar se conectar a um endereço IP e porta informados pelo usuário.
Ele não invade nada: apenas testa se a porta está aberta ou fechada.

1. Criar o arquivo do script

No terminal:

nano script4.3.py

2. Código Python (corrigido e explicado)

Cole o código provido

3. Dar permissão de execução (opcional)

Se quiser rodar como programa direto:

chmod +x script4.3.py

4. Executar o script
   
./script4.3.py

6. Exemplo de execução
M!ss s3c - Teste de Porta
Digite o IP: 127.0.0.1
Digite a porta: 22
Porta 22 aberta no host 127.0.0.1


Ou:

M!ss s3c - Teste de Porta
Digite o IP: 127.0.0.1
Digite a porta: 8080
Porta 8080 fechada no host 127.0.0.1

👉 O que você aprendeu aqui

import socket → biblioteca para trabalhar com rede em Python.

socket.socket() → cria um socket TCP.

connect_ex() → tenta conexão; retorna 0 se deu certo (porta aberta).

Timeout (settimeout) → evita que o script congele.

Fechar o socket (close()) → sempre importante liberar recursos.
