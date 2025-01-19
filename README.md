# Phishing-com-o-Kali-Linux
Projeto de criação de phishing com o Kali Linux, uma ideia de projeto oferecido pelo Bootcamp Santander com apoio do DIO

O que foi utilizado:
- Virtual Box. (para rodar o linux)
- Kali Linux. (sistema usado para roda os comandos)
- setoolkit. (ferramenta principal para criação da interface do phishing)

Preparação da interface:
- para dar acesso ao root diretamente do terminal, precisamos digitar "sudo su".
- rodamos o "setoolkit" já no root.
- precisamos selecionar o tipo de ataque, nesse caso vamos usar "social-engineering attacks"
- o próximo passo é selecionar método de ataque "credential harvester attack method"
- logo após, podemos selecionar a forma que vamos projetar esse ataque, nesse caso vamos usar o "site cloner"

Pontos Importantes:
- para saber o ip da máquina (onde vai ser "hospedada" a url clonada", basta usar o ifconfig dentro do terminal"
- a url que vamos usar nesse exemplo: http://www.facebook.com/

Resultado:
- podemos ter acesso a todas as tentativas de login, contando com user e password dentro do root.
- podemos também ter acesso a todo tipo de atividade feita dentro da nossa página
![0](https://github.com/user-attachments/assets/b89929a9-e121-438e-bea1-5ae44297de17)

não usei o exemplo com email para não vazar as minhas informações.
