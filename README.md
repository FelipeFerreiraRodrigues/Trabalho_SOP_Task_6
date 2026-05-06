# Relatório sobre a Atividade 6 - Segurança e Redes | 🛡️

### Por Felipe, Breno, Eduardo e Lívia M. - 06/05/26

## Introdução | 📄

Esse projeto ns foi designado com foco em testes de penetração e segurança ofensiva. O objetivo é compreender como a vulnerabilidade em credenciais e lógica de software podem ser exploradas por equipes especializadas em ataques, utilizando da distro Kali Linux com ambiente de testes controlados.

## Objetivos | 🎯

### - Compreender técnicas de quebra de hashes e ataques de força bruta
### - Compreender os fundamentos da engenharia reversa em binário simples
### - Analisar ferramentas padrão do mercado (John the Ripper, Hashcat, Hydra)
### - Propor boas práticas de segurança

## Ferramentas utilizadas | 🖥️

### John the Ripper

- Função principal: Quebra de senhas offline (Detecção automática em Hashes).

### Criptografia md5sum

- Função principal: Transformar textos em Hashes.

### Kali Linux

- Função principal: Distro Linux que permite usar funções de criptografia e cybersegurança.

## Instalação | 💽

### Instalação Tools Kit
<img width="798" height="597" alt="image" src="https://github.com/user-attachments/assets/47315cee-8392-4aef-9c6e-5ffb95e40067" />

### Selecionando língua
<img width="795" height="596" alt="Captura de tela 2026-05-06 081657" src="https://github.com/user-attachments/assets/ee6323a5-8859-49d9-9082-c737158af5a6" />

### Particionamento de disco
<img width="798" height="594" alt="Captura de tela 2026-05-06 082000" src="https://github.com/user-attachments/assets/300e67ef-ecc6-4dda-97be-bc6bb4170f35" />
<img width="798" height="594" alt="Captura de tela 2026-05-06 082051" src="https://github.com/user-attachments/assets/354f3179-1d46-44a7-8e63-e71898a9b5fa" />

### Instalação do Grub
<img width="794" height="594" alt="image" src="https://github.com/user-attachments/assets/b246760b-9447-4afd-aea9-cc4a50ab31c5" />

### Tela inicial do Kali Linux
<img width="1919" height="996" alt="image" src="https://github.com/user-attachments/assets/b2172dc9-6bd6-433d-8a2a-f801bd477345" />

### Tela inicial do Hydra
<img width="1919" height="941" alt="image" src="https://github.com/user-attachments/assets/4e1629b1-eb38-48f5-af27-2f56f0fd586d" />

### Senhas Salvas
<img width="1919" height="791" alt="image" src="https://github.com/user-attachments/assets/0d1631b7-dd21-4c1f-a9e9-14274323ac80" />

### Gerações de Hash
- Base md5sum
<img width="1919" height="795" alt="image" src="https://github.com/user-attachments/assets/fc09bff3-479f-411d-898e-01a739f9d562" />
- Base sha256sum
<img width="1456" height="786" alt="image" src="https://github.com/user-attachments/assets/dbe9234c-a919-4eec-b307-0cf473e43e2e" />

### Hashes e código John Ripper
<img width="1919" height="471" alt="image" src="https://github.com/user-attachments/assets/540220c6-5484-4d5c-9622-daf346eea39d" />

### Código e quebra feita
<img width="728" height="373" alt="image" src="https://github.com/user-attachments/assets/5521876c-d0b4-42f9-8928-13551aa95666" />

### Senhas e Hash
<img width="1919" height="388" alt="image" src="https://github.com/user-attachments/assets/a5ff1353-888c-47fc-abbe-f40aa5d73fcb" />

## Análise de risco - Senhas Fracas | ❗

- Senhas fracas ou uso de criptografia frágil tendem a serem facilmente quebradas como mostrado acima. Portanto, é importante que se crie boas práticas de cybersegurança em ambiente particular e em ambiente de trabalho pra evitar problemas futuros.

## Guia de boas práticas | ✅

- Propomos um guia de boas práticas na criação de senha e escolha de criptografia, estas práticas ajudam na melhora de segurança do usuário e empresa.

### - Criação de senhas com no mínimo 12 carácteres
### - Evitar o uso de nomes, dados pessoais, número telefonico e palavras comuns
### - Usar palavras-chave
### - Não reutilizar senhas em locais distintos
### - Utilizar de gerenciador de senhas
### - Ativar verificação em dois fatores
### - Limitar tentativas de login (Bloquear após pelo menos 3 tentativas)
### - Utilizar de Hashes seguros
