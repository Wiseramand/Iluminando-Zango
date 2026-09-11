# Cruzada Iluminando Zango – Gerador de Avatar

Aplicação web moderna e interativa para personalização do cartaz oficial da **Cruzada Iluminando Zango** (Christ Embassy · Grupo Angola). Permite que os participantes carreguem a sua foto, façam ajustes intuitivos de zoom e posicionamento (arrastar e soltar), e façam o download instantâneo do cartaz em alta resolução com o nome **`iluminando zango.png`** ou **`iluminando zango.jpg`**.

---

## 🌟 Funcionalidades

- **Cartaz Oficial de Alta Resolução (1024×1024 px)** com moldura dourada e faixa original sobreposta à foto.
- **Upload Simplificado**: suporte a ficheiros PNG, JPG, JPEG e WebP (via botão, clique na área do avatar ou arrastar e soltar).
- **Controle de Enquadramento**:
  - Zoom de 30% a 400% através do slider, botões `+`/`−` ou roda do mouse.
  - Arraste interativo para centralizar perfeitamente o rosto (mouse e toque no celular).
- **Pré-visualização em Modal** antes de baixar.
- **Download Seguro e Sem Erros**:
  - Geração nativa com `toBlob`.
  - Salva diretamente como `iluminando zango.png` ou `iluminando zango.jpg`.
  - Compatível com Windows, macOS, Android e iOS.
- **Pronto para Hospedagem na Vercel**: 100% estático, sem necessidade de build complexo.

---

## 🚀 Como Hospedar na Vercel

1. Crie um novo repositório no **GitHub** (ex: `cruzada-iluminando-zango`).
2. Envie os ficheiros deste projeto para o GitHub.
3. No painel da **[Vercel](https://vercel.com)**:
   - Clique em **Add New...** > **Project**.
   - Selecione o repositório importado do GitHub.
   - Deixe o **Framework Preset** como **Other** (ou deixe detectar automaticamente como estático).
   - Clique em **Deploy**.
4. Em segundos o seu link estará ativo e pronto para partilha!

---

## 📁 Estrutura de Ficheiros

- `index.html`: Interface da aplicação, estilos CSS e lógica em JavaScript.
- `flyer_template.png`: Cartaz oficial com transparência no círculo.
- `vercel.json`: Configurações de cabeçalhos e URLs amigáveis na Vercel.
- `.gitignore`: Ficheiros ignorados pelo Git.
