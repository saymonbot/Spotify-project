# 🎵 Spotify Project

Interface do Spotify criado com HTML, CSS e JavaScript.

## 🚀 Funcionalidades

- ✨ **Interface Responsiva**: Design adaptável para diferentes tamanhos de tela
- 🔎 **Busca de Artistas**: Sistema de pesquisa que filtra artistas em tempo real
- 🎯 **Navegação Intuitiva**: Sidebar com links para Home, Busca e Biblioteca
- 🎪 **Cards de Playlist**: Exibição de diferentes categorias musicais
- 🎨 **Visual Autêntico**: Interface que replica a experiência do Spotify

## 🛠️ Tecnologias Utilizadas

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
- ![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat&logo=fontawesome&logoColor=white)

## 📁 Estrutura do Projeto

```
📦 Spotify-project
├── 📄 index.html              # Página principal
├── 📄 script.js               # Lógica JavaScript
├── 📂 api-artists/
│   └── 📄 artists.json        # Base de dados dos artistas
└── 📂 src/
    ├── 📂 assets/
    │   ├── 📂 icons/           # Ícones da aplicação
    │   └── 📂 playlist/        # Imagens das playlists
    └── 📂 styles/
        ├── 📄 main-content.css  # Estilos do conteúdo principal
        ├── 📄 sidebar-footer.css # Estilos da sidebar e footer
        ├── 📄 media-queries.css # Consultas de mídia (responsivo)
        ├── 📄 reset.css        # Reset CSS
        └── 📄 vars.css         # Variáveis CSS
```

## 🎯 Como Usar

### 1️⃣ Clone o repositório
```bash
git clone https://github.com/saymonbot/Spotify-project.git
cd Spotify-project
```

### 2️⃣ Inicie um servidor local
Para que a funcionalidade de busca funcione, você precisa servir o arquivo JSON:

**Opção 1 - JSON Server (recomendado):**
```bash
# Instale o json-server globalmente
npm install -g json-server

# Inicie o servidor na pasta api-artists
cd api-artists
json-server --watch artists.json --port 3000
```

**Opção 2 - Python (alternativa):**
```bash
# Para Python 3
python -m http.server 8000

# Para Python 2
python -m SimpleHTTPServer 8000
```

### 3️⃣ Abra o projeto
- Abra o arquivo `index.html` em seu navegador preferido
- A aplicação estará disponível em `http://localhost:8000` (se usar Python)

## 🎨 Características Visuais

- 🟢 **Cores**: Paleta de cores oficial do Spotify (verde, preto, branco)
- 🔤 **Tipografia**: Fontes modernas e legíveis
- 📱 **Responsividade**: Adaptação para dispositivos móveis
- 🎭 **Animações**: Transições suaves entre estados

### ⚖️ Considerações Legais

- 🚨 **Aviso Importante**: Este projeto é para fins educacionais e de demonstração
- 🎯 **Não possui afiliação oficial** com Spotify AB ou suas subsidiárias
- 🎨 **Assets e design**: Inspirados na interface do Spotify para fins educativos
- 🔐 **Marcas registradas**: Spotify® é marca registrada da Spotify AB

### 📚 Licenças de Dependências

| Dependência | Licença | Uso |
|-------------|---------|-----|
| Font Awesome | [SIL OFL 1.1](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL) | Ícones |
| Google Fonts | [SIL OFL 1.1](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL) | Tipografia |

## 💡 Próximas Melhorias

- 🎵 Adicionar player de música funcional
- 👤 Sistema de login/cadastro
- 💾 Salvar playlists favoritas
- 🔊 Controles de volume
- 📊 Histórico de reprodução

---

## 👨‍💻 Autor

**saymonbot** - [GitHub](https://github.com/saymonbot)

---