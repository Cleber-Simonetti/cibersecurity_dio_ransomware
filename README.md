## Desafio Ransomware DIO CyberSec
---

- Sistema: Kali Linux
- Editor de Texto: Nano
- IDE: ViM
- CLI

---
Este repositório é composto de:

- 2 Scripts em Python
- 1 Arquivo de Texto
- 5 Screenshots
---
## Esse desafio consiste em:

1 - Escrever dois Scripts em Python;

2 - Um Script é para Encriptar arquivos de Texto, tornando-os ilegíveis (Trollware);

3 - Um Script é para Desencriptar arquivos Encriptados anteriormente, retornando-os ao estado original;

* Esse tipo de ataque pode ser realizado para exigir suborno/resgate de arquivos, diretórios ou até dispositivos.

* NOTA: não foi usado a Interface Gráfica para criação, manipulação e edição dos arquivos e diretórios. Tudo realizado em CLI.
---

Relato ilustrado da prática:


<img width="1360" height="661" alt="SS1_DIR" src="https://github.com/user-attachments/assets/95bbc991-4699-46a7-84db-2bed4a0061ef" />
Através do terminal, foram criados os diretórios e arquivos.


#
<img width="1360" height="661" alt="SS2_CAT_LOREM" src="https://github.com/user-attachments/assets/470d3f1a-c8d7-4c96-b62d-d250002fc933" />
Leitura do Conteúdo de loremipsum.txt


#
<img width="1360" height="661" alt="SS3_ENCRYPT" src="https://github.com/user-attachments/assets/e127f0c6-6409-4563-ae18-b14824f91191" />
Encriptação do Conteúdo de loremipsum.txt e leitura, demonstrando a criptografia.


#
<img width="1360" height="661" alt="SS4_KEY_ERROR" src="https://github.com/user-attachments/assets/1dd5eed0-ecb9-40c4-b348-b35a26c0739a" />
Erro ao tentar a Descriptografia no arquivo loremipsum.txt. Motivo: a chave não era composta de 16 caracteres. A chave foi alterada para "testesransomware"

<img width="1360" height="661" alt="SS5_DECRYPT_CAT_LOREM" src="https://github.com/user-attachments/assets/45814416-4432-4ebc-bbec-89f212f35b88" />
Descriptografia bem sucedida e leitura do conteúdo de loremipsum.txt

---

Criado em: 06/Ago/25
