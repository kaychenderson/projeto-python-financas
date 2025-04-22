# Projeto - Controle de Finanças Pessoais com Python Puro  

## Configuração do Ambiente

* Primeiro devemos criar o ambiente virtual:  

**Linux**  
```bash
python3 -m venv venv
```
**Windows**  
```bash
python -m venv venv
```

## Ativação do ambiente virtual:

**Linux**
```bash
source venv/bin/activate
```
**Windows**
```bash
venv\Scripts\Activate
```

Caso algum comando retorne um erro de permissão no Windows:
```bash
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

## Instalação de Dependências
```bash
pip install sqlmodel  
pip install matplotlib
```
