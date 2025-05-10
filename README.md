# 🔍 Insith Log

**Insith Log** é uma ferramenta inteligente de análise automatizada de logs Java, com foco na plataforma **Fluig**. Permite aos usuários categorizar erros, facilitar a leitura dos logs e obter resumos automáticos com ajuda de IA. Ideal para equipes de suporte, desenvolvedores e analistas de sistemas.

![Insith Log Banner](https://via.placeholder.com/1000x300.png?text=Insith+Log) <!-- Substitua com sua imagem de capa -->

---

## ✨ Funcionalidades

- ✅ Cadastro de usuários com confirmação por e-mail
- ✅ Criação de categorias personalizadas de erro (nome, cor, descrição e termos)
- ✅ Upload de arquivos de log (limite de 50MB por upload no plano gratuito do Supabase)
- ✅ Resumo inteligente com IA (Google Cloud AI)
- ✅ Filtragem de erros por categorias
- ✅ Histórico de importações anteriores

---

## 🧪 Tecnologias Utilizadas

### Frontend

- [Next.js 14](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)

### Backend / BaaS

- [Supabase](https://supabase.com/)
  - Autenticação de usuários
  - Banco de dados PostgreSQL
  - Envio de e-mails
  - Armazenamento de arquivos

### IA

- [Google Cloud AI](https://cloud.google.com/ai) – para resumo automático dos logs

---

## ⚙️ Como Usar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/insith-log.git
cd insith-log
