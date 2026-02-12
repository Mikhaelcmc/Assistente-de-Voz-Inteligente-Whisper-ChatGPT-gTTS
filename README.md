Este projeto é um sistema de conversação multi-idiomas que utiliza inteligência artificial para ouvir, entender e responder por voz. Desenvolvido como parte do desafio prático da DIO (Digital Innovation One).

🚀 Tecnologias Utilizadas
Whisper (OpenAI): Reconhecimento Automático de Fala (ASR) robusto para transcrição.

GPT-3.5/4 (OpenAI): O "cérebro" que processa o texto e gera respostas contextuais.

gTTS (Google Text-to-Speech): Sintetizador de voz para transformar a resposta da IA em áudio.

SpeechRecognition: Para captura de áudio em tempo real via microfone.

🧠 Diferenciais deste Projeto
Diferente de implementações básicas, este repositório foca em:

Memória de Contexto: O assistente lembra o que foi dito anteriormente na conversa.

Segurança: Implementação de variáveis de ambiente para proteção de chaves de API.

Robustez: Ajuste automático de ruído ambiente para melhor captação de áudio.

🛠️ Como Instalar e Rodar
1. Pré-requisitos
Além do Python, você precisará do ffmpeg instalado no seu sistema para o Whisper processar áudios.

Windows: choco install ffmpeg ou via download oficial.

Linux: sudo apt install ffmpeg

2. Instalação das Bibliotecas
Bash
pip install openai-whisper openai gTTS SpeechRecognition PyAudio python-dotenv
3. Configuração da API Key
Este projeto utiliza a API da OpenAI. Nunca exponha sua chave publicamente.

Crie um arquivo .env na raiz do projeto.

Adicione sua chave no arquivo:

Snippet de código
OPENAI_API_KEY=seu_token_aqui
4. Execução
Bash
python main.py


🤝 Contribuição
Fique à vontade para abrir uma Issue ou enviar um Pull Request com melhorias (como uma interface gráfica ou suporte a novos idiomas).

Desenvolvido com ☕ por Mikhael - Conecte-se comigo no LinkedIn! https://www.linkedin.com/in/mikhael-casteliano-443b97246/
