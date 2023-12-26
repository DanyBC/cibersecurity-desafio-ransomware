<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Desafio Ransomware do Bootcamp de Cibersecurity da DIO</span>
</h1>

<h2>
Descrição:
</h2>

escrever e executar o código apresentadado, utilizando a linha de comando do  Kali Linux. 
o programa deve: critografar o arquivo de teste e depois descriptografar o mesmo, 
voltando à sua mensagem original.

<h3>
Os meus procedimentos neste desafio foram:
</h3>

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

<h2>
Minha compreensão sobre o desafio proposto:
</h2>

<h3>
- Encrypter:
</h3>
Primeiro foram baixadas as bibliotecas "os" e "pyaes" do Python,
para interagir com o sistema operacional e para efetuar a criptografia do arquivo, respectivamente. 
na sequência ele abre o arquivo de teste, lê e captura o conteúdo na variável de nome "file_data" para poder criptografar;
o programa então, após capturar as informações contidas no arquivo, fecha e remove o arquivo original.
utilizando a chave de criptografia apresentada, ele criptografa o conteúdo do arquivo que foi capturado anteriormente
então ele cria um novo arquivo criptografado, onde o usuário não consegua acessar as informações do seu próprio arquivo,
esse arquivo no caso está sendo salvo com o nome: "teste.txt.ransomwaretroll".
<h3>
- Decrypter:
</h3>
inicia da mesma forma, baixando as bibliotecas necessárias e abrindo o arquivo criptografado para capturar as informações.
o programa então, com a mesma chave utilizada para criptografar o arquivo, reverte o processo deixando o arquivo novamente
acessível ao usuário original.
na sequência é feita a exclusão do arquivo criptografado e um novo arquivo é criado, com o conteúdo original antes do ransomware
ser executado. 
<h3>
- Conclusão:
</h3>
De forma simples e objetiva, o exercício proposto mostra o funcionamento de um mecanismo simplificado de Ransomware, 
uma das ameaças cibernéticas mais significativas da atualidade, usado por cybercriminosos para extorquir pessoas, empresas, 
bancos e até mesmo instituições governamentais. 
Muito bom para se compreender na prática o funcionamento do mecanismo, ainda mais sendo ele feito em python, linguagem bastante 
utilizada por hackers mal intencionados pela facilidade de automatização do próprio Python.
