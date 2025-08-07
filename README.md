# 📅 LifeSnap – Organizador Inteligente de Vida Pessoal por Fotos

🚀 Inteligência artificial para transformar suas fotos em uma linha do tempo semântica, emocional e organizada da sua vida — identificando momentos marcantes, pessoas próximas e sentimentos por trás das imagens.

---

📘 **Sumário**
- 🧩 Visão Geral
- ✨ Funcionalidades
- 🔬 Tecnologias Utilizadas
- 📱 Arquitetura
- 💡 Diferenciais
- 📈 Roadmap
- 🔐 Privacidade e Ética
- 🛠️ Como Contribuir
- 🚀 Como Executar Localmente
- 📄 Licença

---

## 🧩 Visão Geral

Milhares de fotos armazenadas em nossos dispositivos permanecem desorganizadas e subutilizadas. O **LifeSnap** foi criado para **dar sentido e contexto às suas memórias visuais**, organizando-as de forma inteligente em uma linha do tempo semântica da sua vida.

O sistema utiliza IA para escanear, agrupar e interpretar imagens com base em:

- Reconhecimento facial e de locais
- Análise de legendas e metadados
- Emoções faciais nas imagens
- Contextos de eventos e pessoas
- Agrupamento temporal e semântico

O resultado é uma **história visual da sua vida**, enriquecida com **insights emocionais**, momentos marcantes e relacionamentos próximos.

---

## ✨ Funcionalidades

| Funcionalidade                  | Descrição |
|-------------------------------|-----------|
| 🖼️ Análise de Fotos            | Scanner inteligente das fotos do usuário, com extração de metadados e conteúdo visual. |
| 😊 Detecção de Emoções Visuais | Identifica sentimentos com base em expressões faciais nas fotos. |
| 🏷️ Agrupamento Semântico       | Agrupa fotos por eventos, pessoas, localizações e sentimentos. |
| 🧑‍🤝‍🧑 Reconhecimento Facial     | Identifica e rotula pessoas próximas com histórico de aparições. |
| 🗺️ Timeline de Memórias        | Cria uma linha do tempo cronológica e temática das fotos. |
| 📖 História da Vida             | Geração automática de uma narrativa visual com base em fotos, com exportação futura. |
| 📊 Insights Emocionais         | Relatórios de emoções dominantes em diferentes fases da vida. |

---

## 🔬 Tecnologias Utilizadas

| Área              | Tecnologias |
|-------------------|-------------|
| Visão Computacional | OpenCV, YOLOv8, DeepFace |
| NLP               | spaCy, Transformers (BERT), CLIP |
| Backend           | .NET Core 9 |
| Frontend          | Angular 17 |
| Banco de Dados    | MongoDB, PostgreSQL |
| Armazenamento     | AWS S3 |
| DevOps            | Docker, GitHub Actions, Terraform (infra opcional) |
| Infra IA          | Python 3.11, PyTorch, FastAPI (NLP Engine) |

---

## 📱 Arquitetura

            +----------------------+
            |    Web / Mobile UI   |
            |      (Angular)       |
            +----------+-----------+
                       |
                       v
            +----------+-----------+
            |     API Gateway      |
            |    (.NET Core 9)     |
            +----+----------+------+
                 |          |
                 v          v
   +-------------+     +----+---------------+
   | NLP Service |     | Vision AI Engine   |
   |  (spaCy)    |     | (YOLO e DeepFace)  |
   +-------------+     +--------------------+

             +-----------------------------+
             |     MongoDB / PostgreSQL    |
             |      AWS S3 (Fotos)         |
             +-----------------------------+
---

## 💡 Diferenciais

✅ **Narrativa Emocional Pessoal**: primeira IA que transforma imagens em uma história de vida emocionalmente consciente.  
✅ **Organização Visual Sem Esforço**: zero intervenção manual.  
✅ **Análise Multidimensional**: fotos, rostos, sentimentos e contexto.  
✅ **Privacidade-First**: análise local, criptografia e controle total do usuário.

---

## 🔐 Privacidade e Ética

Fotos pessoais contêm dados sensíveis. O **LifeSnap** adota:

- 🔒 Criptografia ponta a ponta das imagens
- 👤 Reconhecimento facial local (não enviado à nuvem)
- ⚠️ Consentimento explícito antes de processar fotos
- ✅ Armazenamento sob total controle do usuário
- 🤝 Compromisso com ética, transparência e respeito à privacidade

---

## 🛠️ Como Contribuir

1. Fork este repositório  
2. Crie uma branch: `git checkout -b feature/nova-funcionalidade`  
3. Commit suas alterações: `git commit -m 'Adiciona nova funcionalidade'`  
4. Push para o seu fork: `git push origin feature/nova-funcionalidade`  
5. Crie um Pull Request

Contribuições de devs, designers, especialistas em IA, neurociência e UX são muito bem-vindas!

---

## 🚀 Como Executar Localmente

### Clone o repositório
```bash
git clone https://github.com/seu-usuario/dotnet-lifesnap-ai.git
cd dotnet-lifesnap-ai
Backend (.NET Core 9)
bash
Copy
Edit
cd src/backend
dotnet restore
dotnet run

**Frontend (Angular 17)**
cd src/frontend
npm install
ng serve

**NLP Engine (Python)**
cd src/nlp-engine
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python main.py
```
---

## ⚠️ Requisitos:
Node.js 18+
Python 3.11+
.NET Core 9 SDK
Docker
MongoDB local ou remoto

---

## 📄 Licença
Distribuído sob a licença MIT. Veja o arquivo LICENSE para mais informações.

---

## 💙 Agradecimentos
Esse projeto é inspirado pela importância de preservar e valorizar nossas memórias pessoais de forma inteligente, emocional e humana.

"As fotos não guardam apenas momentos. Elas guardam a gente."

Desenvolvido com carinho por Breno Assis 📸
