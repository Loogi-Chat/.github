# ![WhatsApp Image 2026-03-24 at 12 12 23](https://github.com/user-attachments/assets/a3650672-0963-4f94-a669-22c9f6a348d0)

🩺 BotClínicas — Seu WhatsApp e Instagram atendendo 24h para clínicas

**O bot que faz clínica nunca mais perder paciente por falta de resposta.**

Automatiza atendimento, agendamento, confirmações, lembretes e pós-atendimento via WhatsApp Business API + Instagram. Reduz faltas em até 80% e gera R$4.000–R$6.000 de receita extra por mês para a clínica.

Ideal para dentistas, clínicas gerais, fisioterapia, psicólogos e pequenas clínicas no Brasil.

---

## ✨ Principais funcionalidades (MVP V1)

- ✅ Conexão oficial WhatsApp Business API + Instagram em menos de 5 minutos
- ✅ 6 templates prontos por especialidade (Dentista, Clínica Geral, Fisioterapia, etc.)
- ✅ Fluxos personalizados (respostas automáticas, coleta de dados, agendamento)
- ✅ Integração Google Calendar (agenda cheia automaticamente)
- ✅ Lembretes automáticos (D-2, D-1, 2h antes) + confirmação
- ✅ Dashboard com **"Faltas evitadas em reais"** (o número que faz o cliente nunca cancelar)
- ✅ Inbox unificado (WhatsApp + Instagram) com transferência humana
- ✅ CRM simples de pacientes com histórico e documentos
- ✅ Campanhas de aniversário e marketing (limitadas por plano)
- ✅ Onboarding guiado em 7 passos (mesmo para quem odeia tecnologia)

**Preços**  
- Básico → R$197/mês  
- Profissional → R$297/mês (mais vendido)  
- Premium → R$497/mês

---

## 🛠️ Tecnologias (Stack completa)

**Frontend**  
- Next.js 15 (App Router)  
- TypeScript  
- Tailwind CSS + shadcn/ui  
- React Query + Zustand  
- Socket.io (conversas em tempo real)

**Backend**  
- Node.js + Express  
- Supabase (PostgreSQL + Auth + Storage)  
- Redis (filas e rate limit)  
- BullMQ (jobs de lembretes e campanhas)  
- WhatsApp Business API (via 360Dialog/Twilio)  
- Instagram Graph API  
- Google Calendar API

**Infra**  
- Sem Docker (roda com `npm install && npm run dev`)  
- Variáveis de ambiente em `.env`  
- Deploy fácil no Vercel (frontend) + Railway/Render (backend)

---

## 🚀 Como rodar localmente (super simples)

1. Clone o repositório
   ```bash
   git clone https://github.com/seuusuario/botclinicas.git
   cd botclinicas
