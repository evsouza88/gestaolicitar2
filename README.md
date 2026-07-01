# Gestão Licitar ERP — Next.js

Projeto profissional preparado para Vercel.

## Publicação na Vercel

1. Crie um repositório no GitHub chamado `gestao-licitar-erp` ou `gestaolicitar`.
2. Envie todos os arquivos desta pasta para o repositório.
3. Entre na Vercel.
4. Add New → Project.
5. Importe o repositório.
6. Framework Preset: Next.js.
7. Clique em Deploy.

A Vercel gerará um link, por exemplo:

https://gestaolicitar.vercel.app

## Rodar localmente

```bash
npm install
npm run dev
```

Acesse:

http://localhost:3000

## Supabase

O projeto já inclui:

- `src/lib/supabase.ts`
- `.env.example`
- `supabase/schema.sql`

Para ativar banco online:

1. Crie conta em https://supabase.com.
2. Crie um projeto.
3. Rode o SQL em `supabase/schema.sql`.
4. Copie URL e anon key.
5. Configure na Vercel as variáveis:

```env
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

## Aplicativo celular

Depois de publicado na Vercel:

- Android/Chrome: menu → Instalar app.
- iPhone/Safari: compartilhar → Adicionar à Tela de Início.

## Observação

Esta versão é a base profissional. A próxima etapa é substituir os estados locais por integração Supabase persistente, login, storage de arquivos e permissões.
