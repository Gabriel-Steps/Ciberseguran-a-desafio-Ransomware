# RansomwareTroll - Simulação de Criptografia e Descriptografia de Arquivo

Este projeto simula um processo básico de criptografia e descriptografia de arquivos utilizando a biblioteca `pyaes` em Python.

⚠️ **Este projeto tem fins exclusivamente educacionais. Não deve ser utilizado em ambientes reais ou contra arquivos que não sejam de sua propriedade.**

## 📁 Arquivos

- `encrypter.py`: Script responsável por criptografar o arquivo `teste.txt`.
- `decrypter.py`: Script responsável por descriptografar o arquivo `teste.txt.ransomwaretroll`.
- `teste.txt`: Arquivo de texto simples que será usado para testes.

## 🔐 Como funciona

### Criptografia (`encrypter.py`)

1. Abre o arquivo `teste.txt`.
2. Lê o conteúdo e o remove do sistema.
3. Criptografa os dados usando a chave `testeransomwares` com o modo `AES CTR`.
4. Salva o conteúdo criptografado como `teste.txt.ransomwaretroll`.

### Descriptografia (`decrypter.py`)

1. Abre o arquivo `teste.txt.ransomwaretroll`.
2. Descriptografa os dados usando a mesma chave.
3. Remove o arquivo criptografado.
4. Restaura o conteúdo original como `teste.txt`.

## 🛠️ Requisitos

- Python 3
- Biblioteca `pyaes`

### Instalando o `pyaes` em ambiente virtual

```bash
python3 -m venv venv
source venv/bin/activate
pip install pyaes
