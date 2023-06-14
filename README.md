# Instalação do Whisper AI no Windows

## Pré-requisitos:

- Python
- PyTorch
- Chocolatey
- FFMPEG
- Whisper AI

## Etapas de Instalação

### 1. Instalando o Python
- Baixe a versão mais recente do Python (3.7 - 3.10) do site oficial.
- Marque a opção 'add python.exe to path' durante a instalação.

### 2. Instalando o PyTorch
- Baixe a versão correspondente do PyTorch do site oficial, adequada ao seu sistema operacional e versão do Python.
- Escolha a plataforma de cálculo de acordo com a configuração do seu computador.

### 3. Instalando o Chocolatey
- Abra o PowerShell como administrador e copie o comando do site do Chocolatey para instalação.
- Cole o comando no PowerShell e execute.

### 4. Instalando o FFMPEG
- Digite 'choco install ffmpeg' no PowerShell e execute.

### 5. Instalando o Whisper AI
- Abra o prompt de comando e digite 'pip install -U openai-whisper'. Execute o comando.

## Uso do Whisper AI

- Para transcrever um arquivo de áudio, digite 'whisper [nome do arquivo]' no prompt de comando.
- O Whisper AI pode transcrever múltiplos arquivos de uma vez e suporta vários formatos de arquivo.
- Cinco modelos diferentes podem ser escolhidos para transcrição com qualidade e tempo de processamento variáveis. Utilize o comando '--model' após o nome do arquivo para especificar um modelo.
- O Whisper AI também pode transcrever áudio em outros idiomas e traduzir para o inglês.
- Vários argumentos estão disponíveis para personalizar o comportamento de transcrição do Whisper AI. Para obter a lista completa de argumentos, digite 'whisper --help' no prompt de comando.

###### Fonte: 
https://youtu.be/ABFqbY_rmEk
