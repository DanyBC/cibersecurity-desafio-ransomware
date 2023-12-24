<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Desafio Ransomware do Bootcamp de Cibersecurity da DIO</span>
</h1>

O desafio era, reproduzir o código e executa-lo no Kali Linux, 
de forma que programa criptografe o arquivo de texto e depois descriptografe o mesmo, 
voltando à sua mensagem original.

O meu procedimento neste desafio foi:
*Executando através da linha de comando no terminal Linux:

- Criar o diretório Ransomware_Chalenge_DIO para conter os arquivos;
- criar o arquivo "decrypt" conforme as explicações do Cassio;
- criar o arquivo "encrypt" assim como o anterior;
- criar o arquivo de texto para ser encriptado pelo ransomware
- executar o encrypt, verificar se o mesmo criptografou o arquivo .txt 
- executar o decrypt e verificar se o arquivo .txt foi descriptografado.
- Os meus testes foram bem sucedidos, assim como efetuar todos os procedimentos acima
através da linha de comando no terminal do Kali Linux.

segue print da tela dos resultados para materializar o cumprimento da tarefa.

![resoluçãoi desafio ransomware](https://github.com/DanyBC/cibersecurity-desafio-ransomware/assets/119118430/d69504e0-df6c-4170-b158-31c51ac2459c)

Meus entendimentos:

O que pude compreender do código apresentado foi o seguinte: 

Primeiro foram baixadas as bibliotecas "os" e "pyaes" do Python,
para interagir com o sistema operacional e para efetuar a criptografia do arquivo, respectivamente. 
na sequência ele abre o arquivo de teste, lê e captura o conteúdo para poder criptografar e fecha o arquivo teste.
é introduzida a chave de criptografia que será usada para codificar o conteúdo do arquivo

então ele cria um novo arquivo criptografado com base na chave apresentada 
(no caso a chave: "testeransomwares" com 16 caracteres), utilizando a biblioteca pyaes.


