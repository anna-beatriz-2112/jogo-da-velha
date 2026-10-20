# Jogo da Velha em Python 🎮

Jogo da Velha moderno executado com um servidor local em Python.

## Funcionalidades
- Modo 2 Jogadores (Local).
- Modo Contra o Robô 🤖 com inteligência artificial para bloquear e buscar vitórias.
- Placar automático de vitórias (X, O) e empates.
- Destaque animado para a linha vencedora.
- Servidor web simples utilizando o módulo nativo `http.server`.

## Como Executar Localmente

1. Crie e ative o ambiente virtual (`venv`):
```bash
python -m venv venv
# No Windows (PowerShell):
.\venv\Scripts\Activate.ps1
# Ou no CMD:
.\venv\Scripts\activate.bat
```

2. Instale as dependências (se houver):
```bash
pip install -r requirements.txt
```

3. Inicie o servidor:
```bash
python server.py
```
Abra o navegador em: [http://localhost:8080](http://localhost:8080)
