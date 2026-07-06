# 📊 Stack Tecnológico — GTGroup · Gröwnt

Dashboard de gestão do stack tecnológico do GTGroup e Gröwnt. Centraliza custos, riscos, renovações e governança de todas as ferramentas numa interface web com dados em tempo real.

**🔗 Produção:** https://techstack-grownt-v3.vercel.app

---

## Stack

| Camada | Tecnologia |
|---|---|
| Frontend | HTML5 + CSS3 + JavaScript (SPA autocontida) |
| Gráficos | Chart.js 4.4.1 |
| Base de dados | Supabase (PostgreSQL 17.6) |
| Autenticação | Supabase Auth — Email + Password |
| Hosting | Vercel (Hobby) |
| CI/CD | GitHub → Vercel (auto-deploy) |

---

## Deploy

Qualquer push para `main` faz deploy automático via Vercel.

```bash
# Clonar e editar
git clone https://github.com/AndreGodinho96/techstack-grownt.git
cd techstack-grownt

# Editar index.html
# ...

# Publicar
git add index.html
git commit -m "descrição da alteração"
git push origin main
# ✅ Vercel faz deploy em ~30 segundos
```

---

## Acesso

Restrito a emails `@grownt.tech` e `@gtgroup.tech`.  
Edição restrita a utilizadores autorizados na política RLS do Supabase.

---

## Documentação completa

Ver `techstack_documentacao_ti.docx` — inclui schema completo, RLS, arquitectura, troubleshooting e roadmap.

---

*RevOps · Gröwnt · 2026*
