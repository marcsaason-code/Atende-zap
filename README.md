# Atende +Zap

Plataforma de atendimento via WhatsApp com agente de IA.

## Arquivos

- `index.html` — App do cliente (login com CNPJ + senha)
- `admin.html` — CRM do suporte interno

## Deploy na Vercel

1. Faça o push desses arquivos para um repositório GitHub
2. Importe o repositório na Vercel (vercel.com/new)
3. Framework Preset: `Other`
4. Clique em Deploy

## Configuração

- **Supabase URL**: https://rhraigbapgpzvmcjbett.supabase.co
- **Supabase Key**: configurada nos arquivos
- **Evolution API**: configurada por cliente no CRM admin

## URLs após deploy

- `/` → App do cliente
- `/admin.html` → CRM do suporte

## Atualizações

```bash
git add .
git commit -m "descrição"
git push
```
A Vercel atualiza automaticamente.
