# Site Juarez de Oliveira — juarezfeliz.com.br

## Estrutura do site

```
juarezfeliz/
├── hugo.toml              # Configuração principal
├── content/
│   ├── sobre.md           # Biografia completa
│   ├── contos-e-poesias/  # Contos e poesias (adicione aqui)
│   ├── letras/            # Letras musicais (adicione aqui)
│   ├── videos/            # Página de vídeos
│   └── declamadas/        # Página autor declamando
├── static/
│   ├── images/
│   │   └── juarez-perfil.png   # ← COLOQUE A FOTO AQUI
│   └── audio/                  # ← COLOQUE OS MP3 AQUI
└── assets/css/extended/
    └── custom.css         # Estilos literários
```

## Como publicar

### 1. Preparar os arquivos
- Copie `juarez_perfil_v2.png` para `static/images/juarez-perfil.png`
- Copie todos os arquivos MP3 para `static/audio/`

### 2. Subir no GitHub
1. Acesse github.com e faça login
2. Clique em "New repository"
3. Nome: `juarezfeliz`
4. Clique em "Create repository"
5. Faça upload de toda a pasta `juarezfeliz/`

### 3. Publicar no Vercel
1. Acesse vercel.com e crie conta com seu GitHub
2. Clique em "Add New Project"
3. Selecione o repositório `juarezfeliz`
4. Clique em "Deploy"

### 4. Conectar o domínio juarezfeliz.com.br
No Vercel:
1. Vá em Settings → Domains
2. Adicione `juarezfeliz.com.br`
3. O Vercel mostrará os DNS a configurar

No registro.br:
1. Acesse registro.br e faça login
2. Clique no domínio `juarezfeliz.com.br`
3. Vá em "Configurar DNS"
4. Adicione os registros que o Vercel indicar

## Como adicionar conteúdo depois

### Novo poema ou conto
Crie um arquivo `.md` em `content/contos-e-poesias/`:
```
---
title: "Título do Poema"
date: 2024-01-01
tipo: "poesia"
summary: "Primeiras linhas do poema..."
cover:
  image: "URL da ilustração do Unsplash"
---

Texto completo do poema aqui...
```

### Nova letra musical
Crie um arquivo `.md` em `content/letras/`:
```
---
title: "Nome da Música"
date: 2024-01-01
summary: "Primeiros versos..."
---

Letra completa aqui...
```
