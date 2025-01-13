# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados
Teoricamente era para ser esse o resultado, porém não foi o que aconteceu, pelo que pesquisei o facebook atualmente tem uma defesa contra a Clonagem do site.

![Alt text](./passwd.png "Optional title")

## Outro Método
Em vez de selecionar o "Site Cloner" selecione o "Custom Import".

![image](https://github.com/user-attachments/assets/d7116b5b-2832-42a7-8e6a-34d9c65f5f23)

Só que antes você vai salvar a pagina do facebook no seu computador.

![image](https://github.com/user-attachments/assets/8384f26e-07a2-4440-8cad-bf8b06be5a55)

Aqui você deixa a opção de salvamento como "Web Page, complete".

![image](https://github.com/user-attachments/assets/643b94bf-bc89-45c4-8be6-0d5bc272a0b5)

Depois você vai copiar o código fonte da página do facebook colar no bloco de notas e exluir essa parte que está relacionada ao botão de login. Ai é só salvar essa arquivo como index.html e o colocá-lo dentro da pasta do facebook que você baixou.

![image](https://github.com/user-attachments/assets/a0057eaa-84ff-4dd5-b4ff-9ccbab6ae001)

![image](https://github.com/user-attachments/assets/3c6902b2-9488-458e-a925-2c8583eea2b0)


Voltando pro setoolkit vai ser pedido o caminho para a pasta do website que deseja clonar, copia a pasta que criou do facebook com o código fonte modificado e cole o caminho dentro do terminal.

![image](https://github.com/user-attachments/assets/8a162ee4-682a-4dab-85c3-9025a9bc6e25)


Selecione a opção 2 "Copy the entire folder", e logo depois coloque o url do facebook.

![image](https://github.com/user-attachments/assets/83246cf4-ea76-4928-8e08-b037dbb682fc)

## Resultado do Outro Método
![image](https://github.com/user-attachments/assets/907a2ad2-c33d-41e8-99d8-4576a8ded86a)






Repositório que me ajudou nesse outro método.
https://github.com/Weslley22Marques/cibersecurity-desafio-phishing?tab=readme-ov-file
