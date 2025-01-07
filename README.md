# Gerenciador de Projetos

O **Gerenciador de Projetos** é uma ferramenta interativa desenvolvida em Python com interface gráfica para gerenciar arquivos ZIP baseados no tipo e linguagem de projeto. Este projeto permite que o usuário escolha as configurações desejadas, copie o arquivo ZIP adequado para um diretório de destino e o extraia automaticamente.

## Funcionalidades

- Seleção do tipo de projeto: Backend, Frontend ou Mobile.
- Seleção da linguagem do projeto: Java, Python ou Ruby.
- Cópia automática do arquivo ZIP adequado para o diretório de destino.
- Extração do conteúdo do arquivo ZIP no diretório especificado.
- Apaga automaticamente o arquivo ZIP após a extração.

## Requisitos

- Python 3.7 ou superior
- Bibliotecas:
  - `tkinter`
  - `os`
  - `shutil`
  - `zipfile`

## Instalação

Para instalar o **Gerenciador de Projetos** como um pacote do PyPI, siga os passos abaixo:

1. **Instalar o pacote**:
   ```bash
   pip install gerenciador-projetos
   ```

2. **Executar o programa**:
   ```bash
   python -m gerenciador_projetos
   ```

## Estrutura do Projeto

O projeto segue a seguinte estrutura de diretórios:

```
.
├── gerenciador_projetos/
│   ├── __init__.py
│   ├── app.py
│   ├── utils/
│   │   ├── file_manager.py
│   │   └── decision_manager.py
├── setup.py
├── README.md
└── dist/
```

- `gerenciador_projetos/`: Contém o código-fonte do projeto.
- `utils/`: Módulos auxiliares para gerenciamento de arquivos e tomada de decisões.
- `setup.py`: Script para configuração do pacote PyPI.
- `dist/`: Diretório gerado após o build do pacote.
