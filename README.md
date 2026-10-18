# ⚡ Cyber Beacon | HTML5 & CSS3 Master Vault

> O guia definitivo, compiladão nervoso e mostruário visual de HTML5 Semântico e CSS3 Vanilla moderno.

---

## 🌟 O que está incluído

1. **`index.html` (Master Vault - Guia Completo):**
   - Mais de 3.400 linhas de código limpo e componentes práticos.
   - Semântica pura, Anatomia do `<head>`, Acessibilidade (AOM), Tabelas Responsivas.
   - Mestria em Formulários HTML5 nativos (validação regex, datalists, color picker).
   - Componente realista de Menu de Setup (com abas nativas, upload de avatar e persistência).
   - Guia moderno de CSS3: Flexbox, Grid auto-fit, clamp() fluido, Glassmorphism, :has() e Modais `<dialog>`.
   - Links diretos integrados para todos os laboratórios e para a Vitrine Bate-Olho.

2. **`tutoriais.html` (Vitrine Bate-Olho HTML):**
   - Mostruário visual ultrarrápido com todas as tags, inputs e seletores nativos.
   - Filtro interativo instantâneo por pílulas (Textos, Números, Datas, Escolhas, Interativos).
   - Botões de cópia rápida de snippets em 1 clique.
   - *Nota de compatibilidade:* Também mantido como `HTML TUTORIAIS.html` para compatibilidade retroativa absoluta.

3. **`exemplos/` (Laboratório de Protótipos):**
   - Coleção de tutoriais e testes interativos isolados (CRUD MVC com JSON, LocalStorage v2, Modais bloqueantes, Testes de Favicon SVG, etc.).

4. **Configuração de Produção para Vercel & GitHub (`vercel.json`):**
   - `cleanUrls: true`: URLs limpas e elegantes (ex: `/tutoriais` em vez de `/tutoriais.html`).
   - `rewrites`: Redirecionamento automático e transparente para `/tutoriais`, `/vitrine`, `/bate-olho` e `/HTML TUTORIAIS.html`.
   - `404.html`: Página personalizada de erro 404 estilizada com a identidade visual Cyber Beacon.
   - `sitemap.xml` & `robots.txt`: Indexação completa de ambas as páginas para o Google e motores de busca.

---

## 🚀 Como Rodar Localmente (No Disco Local)

Você tem duas formas simples e livres de dependências:

### Modo 1: Direto no Navegador (Zero Instalação)
Basta dar um duplo clique em `index.html` ou em `tutoriais.html`. Todos os links e caminhos são relativos e funcionam 100% offline.

### Modo 2: Servidor Local Rápido
Se tiver o Node instalado:
```bash
npx serve .
```
Ou usando npm:
```bash
npm run dev
```

---

## 📦 Como Subir para o GitHub e Vercel

O repositório Git local já foi inicializado com a branch `main` e commit inicial! Para publicar:

### Passo 1: Criar o Repositório no GitHub
1. Acesse [github.com/new](https://github.com/new).
2. Dê o nome de `cyberbeacon` (público ou privado).
3. **Não** marque "Add a README file" ou ".gitignore" (já criamos tudo aqui).
4. Clique em **Create repository**.

### Passo 2: Conectar e Enviar o Código
No seu terminal dentro da pasta `cyberbeacon`:
```bash
git remote add origin https://github.com/SEU_USUARIO/cyberbeacon.git
git push -u origin main
```

### Passo 3: Conectar na Vercel
1. Acesse [vercel.com](https://vercel.com) e faça login com seu GitHub.
2. Clique no botão **"Add New..."** -> **"Project"**.
3. Encontre o repositório **`cyberbeacon`** e clique em **"Import"**.
4. A Vercel detectará automaticamente o projeto como estático (com nosso `vercel.json`).
5. Clique em **"Deploy"**.

Pronto! Seu site estará no ar em segundos com:
- Home: `https://cyberbeacon-seu-usuario.vercel.app/`
- Vitrine: `https://cyberbeacon-seu-usuario.vercel.app/tutoriais`
- Redirecionamento: `https://cyberbeacon-seu-usuario.vercel.app/vitrine`
