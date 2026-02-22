markdown
# 🐳 Projeto Docker - Capacita iRede

## 👨‍🎓 Aluno
**Jeronimo do Nascimento Sales**

## 📋 Sobre o projeto
Este projeto é uma aplicação containerizada usando Docker e Nginx, desenvolvida para o curso Capacita iRede - Computação em Nuvem.

## 📁 Arquivos do projeto
| Arquivo | Descrição |
|---------|-----------|
| `Dockerfile` | Configuração do container com Nginx |
| `index.html` | Página web institucional |

## 🔗 Links importantes
- **📓 Google Colab** (código fonte e explicações):  
  [Acessar notebook no Colab](https://colab.research.google.com/drive/1J7o0_GCNyFnypxKsAGq7Z9KdBziYR1bY?usp=sharing)

## 🚀 Como executar localmente

### Pré-requisitos
- Docker instalado no computador

### Passos
1. Clone este repositório ou baixe os arquivos
2. No terminal, execute:

```bash
# Construir a imagem
docker build -t minha-app-capacita .

# Executar o container
docker run -d -p 8080:80 --name meu-container minha-app-capacita
Acesse no navegador:
👉 http://localhost:8080

📸 Resultado
O container roda uma página web com a mensagem:

"Mini Projeto Containerizado - Capacita iRede - Computação em Nuvem"
