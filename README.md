[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/gustavo89587/oka-mp-starter&project-name=oka-mp-starter&repository-name=oka-mp-starter)

# Oka MP Starter 🚀  
Next.js + Supabase + Mercado Pago (assinaturas / preapproval)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/gustavo89587/oka-mp-starter&project-name=oka-mp-starter&repository-name=oka-mp-starter)

---

## ✨ O que vem incluso
- **Next.js 14** (pasta `/pages`)
- Integração **Supabase** (`supabaseClient.ts` e `supabaseAdmin.ts`)
- Rotas API:
  - `/api/mp/create-preapproval` → cria assinatura no Mercado Pago
  - `/api/mp/webhook` → recebe webhooks, valida HMAC e atualiza Supabase
- **SQL pronto** (`/sql/supabase_mp.sql`): tabelas, RLS, índices, views e funções
- UI simples em `/` para criar assinatura vinculada ao `user_id`

---

## ⚡ Como usar

### 1. Rodar o SQL no Supabase
No **Supabase Studio → SQL Editor**, cole o conteúdo de:

