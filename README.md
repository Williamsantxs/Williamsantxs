## William dos Santos

Desenvolvedor web em Ubatuba/SP. Construo sites institucionais para clientes
reais — do layout à publicação, incluindo domínio, hospedagem e manutenção.

Cursando Análise e Desenvolvimento de Sistemas na Universidade Cruzeiro do
Sul, com conclusão prevista para dezembro de 2026. **Buscando estágio ou
posição de desenvolvedor júnior.**

---

### Projetos

| Projeto | O que é | Situação | Links |
|---|---|---|---|
| **Rayton Casa Completa** | Tintas e material de construção, três lojas no Vale do Paraíba e Litoral Norte | Entregue e no ar | [site](https://lojasrayton.com) · [código](https://github.com/Williamsantxs/lojas-rayton) |
| **Terra Academia** | Academia de musculação em Ubatuba | Em desenvolvimento | [prévia](https://terra-academia.netlify.app) · [código](https://github.com/Williamsantxs/terra-academia) |
| **Ateliê do Automóvel** | Estética automotiva em Ubatuba | Em desenvolvimento | [prévia](https://atelie-estetica.netlify.app) · [código](https://github.com/Williamsantxs/atelie-estetica) |

Cada repositório tem um README explicando as decisões técnicas do projeto —
por que sem framework, como as fontes são servidas, o que foi preciso
configurar no servidor para o site funcionar.

---

### Stack

**Uso em projeto entregue:**
HTML · CSS · JavaScript · Git · WebP · Schema.org / JSON-LD ·
Netlify · IIS (`web.config`)

**Estudando:**
React · Next.js · Node.js · Supabase

Separo as duas listas de propósito. A primeira é o que já coloquei em
produção e sei explicar linha por linha. A segunda é o que estou aprendendo
e ainda não levei a cliente.

---

### O que já resolvi na prática

- Publicação em servidor Windows/IIS: registro de MIME para `.webp` e
  `.woff2` (sem isso o servidor recusa servir o arquivo), documento padrão e
  redirecionamento 301 do endereço antigo para não perder quem vinha do Google
- Fontes auto-hospedadas em `.woff2` com `unicode-range`, para o navegador
  baixar só o subconjunto que vai usar
- Diagnóstico de página de 11 MB causada por imagens e vídeo embutidos em
  base64 — extração para arquivos e queda para 31 KB
- Dados estruturados em JSON-LD com endereço e horário de funcionamento

---

### Contato

[LinkedIn](https://www.linkedin.com/in/william-dos-santos-) ·
[Instagram](https://instagram.com/williamsantxs) ·
williamdsantos.souza@gmail.com

