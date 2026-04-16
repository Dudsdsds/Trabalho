# AquaTec DF

Site de monitoramento hídrico do Distrito Federal. Permite que moradores acompanhem o status do abastecimento na sua RA, recebam alertas e registrem denúncias diretamente para os órgãos responsáveis.

## 🚀 Deploy no GitHub Pages

1. Faça upload deste repositório para o GitHub:
   ```bash
   git init
   git add .
   git commit -m "first commit"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/aquatec-df.git
   git push -u origin main
   ```

2. No repositório, vá em **Settings → Pages**

3. Em **Source**, selecione a branch `main` e a pasta `/ (root)`

4. Clique em **Save** — em alguns minutos o site estará em:  
   `https://SEU_USUARIO.github.io/aquatec-df/`

## 📁 Estrutura

```
/
└── index.html   ← site completo (HTML + CSS + JS em um único arquivo)
└── README.md
```

## ✅ Funcionalidades

- Navegação com scroll suave entre seções
- Menu mobile responsivo
- Formulário de denúncia funcional com validação
- Animações de scroll reveal
- Contadores animados nas estatísticas
- Layout responsivo (mobile, tablet, desktop)

## 🛠️ Tecnologias

- HTML5 semântico
- CSS3 (variáveis, grid, flexbox, animações)
- JavaScript vanilla (sem dependências)
- Google Fonts (DM Sans + DM Serif Display)
