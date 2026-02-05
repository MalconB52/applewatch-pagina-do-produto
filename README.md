# ⌚ Página do Produto - Apple Watch

**Uma réplica interativa e responsiva da página de um produto Apple Watch. Desenvolvida com HTML5, CSS3 e JavaScript para criar uma experiência próxima do original.**

<img width="1470" height="1262" alt="image" src="https://github.com/user-attachments/assets/fa5cd570-3bda-4081-a500-23c9cfa9c5df" />

## 📋 Sobre
Clone interativo da página de apresentação de um Apple Watch. Este projeto foi além do design estático, implementando **funcionalidades dinâmicas com JavaScript** para simular a experiência real de customização de produto da Apple.

## 🚀 Demonstração & Código
- **🌐 Site Online:** (https://applewatch-pagina-do-produto-mb.vercel.app/)
- **📂 Código Fonte:** (https://github.com/MalconB52/applewatch-pagina-do-produto)

## 🛠️ Stack Tecnológica
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Funcionalidades Implementadas
### 🎨 **Interatividade com JavaScript**
- **Seletor de Cores:** Troca dinâmica da imagem do relógio e dos elementos de UI conforme a cor selecionada.
- **Galeria Interativa:** Navegação entre imagens do produto (próximo/anterior) ou por thumbnails.
- **Modais/Overlays:** Exibição de informações detalhadas ou imagens ampliadas.

### 🖼️ **UI/UX & Design**
- **Design Fiel:** Réplica precisa do layout, espaçamento e tipografia da Apple.
- **Responsividade Total:** Adaptação impecável para mobile, tablet e desktop.
- **Transições Suaves:** Animações CSS para troca de cores e imagens.

## 📁 Estrutura do Projeto
applewatch-pagina-do-produto/
├── index.html # Estrutura principal
├── style.css # Estilos e animações
├── script.js # Lógica de interatividade (seletor, galeria)
└── assets/
├── img/ # Imagens do produto (por cor e ângulo)
└── icons/ # Ícones SVG

text

## 🔧 Como Executar
```bash
# 1. Clone o repositório
git clone https://github.com/MalconB52/applewatch-pagina-do-produto.git

# 2. Abra o arquivo index.html no navegador
# A interatividade com JavaScript funcionará diretamente.
💻 Trecho de Código - Seletor de Cores (Exemplo)
javascript
// Exemplo simplificado da lógica de troca de cor
function selecionarCor(cor) {
  // Atualiza a imagem principal do relógio
  document.getElementById('imagem-principal').src = `assets/img/watch-${cor}.jpg`;
  
  // Atualiza a cor ativa no seletor visual
  document.querySelectorAll('.opcao-cor').forEach(opcao => {
    opcao.classList.toggle('ativa', opcao.dataset.cor === cor);
  });
  
  // Atualiza o nome da cor exibida na página
  document.getElementById('nome-cor').textContent = corFormatada;
}
🎯 Competências Demonstradas
Front-end Completo: Integração de HTML (estrutura), CSS (estilo) e JavaScript (lógica).

DOM Manipulation: Alteração dinâmica de elementos da página.

Gestão de Eventos: Resposta a cliques e interações do usuário.

Lógica de Aplicação: Implementação de funcionalidades complexas do zero.

Desenvolvido por Malcon Barbosa
Estudante de Análise e Desenvolvimento de Sistemas | Foco em Front-end e UI/UX
