# Conversor de Áudio para Texto

Este projeto é uma solução avançada que transforma arquivos de áudio em texto utilizando a poderosa **API Google Cloud Speech-to-Text**. Com alta precisão e suporte a múltiplos formatos de áudio, esta aplicação é ideal para transcrições automáticas, anotações e muito mais.

---

## 🚀 Funcionalidades

- **Conversão de áudio em texto** com alta precisão.
- Suporte a **diversos formatos de áudio** (MP3, WAV, etc.).
- **Detecção automática de idioma**, proporcionando flexibilidade.
- Pronto para uso em **projetos de grande escala**.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Python
- **API**: Google Cloud Speech-to-Text
- **Bibliotecas**:
  - `speech_recognition`
  - `google-cloud-speech`
  - `pydub` (manipulação de áudio)

---

## ⚙️ Pré-requisitos

Certifique-se de que você tem:

- **Python 3.8 ou superior**
- Uma conta no [Google Cloud Platform](https://cloud.google.com/)
- Configuração da API Google Speech-to-Text
- Dependências instaladas via `requirements.txt`:

```bash
pip install -r requirements.txt
```

---

## 📝 Como Configurar

### 1. Configurar o Google Cloud

1. Acesse o [Google Cloud Console](https://console.cloud.google.com/).
2. Crie um novo projeto.
3. Ative a API **Speech-to-Text**.
4. Gere uma **chave JSON** de autenticação e faça o download.

### 2. Configurar a Variável de Ambiente

Defina o caminho para a chave JSON como uma variável de ambiente:

```bash
export GOOGLE_APPLICATION_CREDENTIALS="caminho/para/sua/chave.json"
```

### 3. Clonar o Repositório

Clone este repositório para sua máquina local:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
```

### 4. Instalar Dependências

Use o `pip` para instalar todas as bibliotecas necessárias:

```bash
pip install -r requirements.txt
```

---

## 💻 Como Usar

1. **Adicione um arquivo de áudio** à pasta indicada no projeto.
2. Execute o script principal:

```bash
python main.py
```

3. **Resultado**: O texto será exibido no terminal e/ou salvo em um arquivo de texto na pasta do projeto.

---

## 📂 Estrutura do Projeto

```plaintext
/
├── main.py                # Script principal
├── requirements.txt       # Dependências do projeto
├── README.md              # Documentação do projeto
└── /audio                 # Pasta para os arquivos de áudio
```

---

## 📊 Exemplo de Uso

### Entrada:
Arquivo: `audio.wav`

### Saída:
```plaintext
Texto transcrito do áudio.
```

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature ou correção: `git checkout -b minha-feature`
3. Envie suas alterações: `git commit -m "Descrição da alteração"`
4. Submeta um pull request.

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---

💡 **Dica**: Se tiver dúvidas ou sugestões, abra uma issue no repositório. Ficaremos felizes em ajudar!
