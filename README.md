# 🌲 Animalysson.io

[![Acesse o Portal Animalysson.io](https://img.shields.io/badge/%F0%9F%8C%90_Acesse_o_Portal_Animalysson.io-00aa00?style=for-the-badge&logo=github)](https://alyssoneustaquio.github.io/teste-jogo-web/)

**Jogos de Simulação 3D no Navegador**

Animalysson.io é uma coleção de jogos de simulação 3D desenvolvidos com Three.js, rodando diretamente no navegador. Explore mundos interativos, gerencie florestas e molde terrenos com ferramentas realistas.

---

## 🎮 Jogos Disponíveis

### Sistema de Árvores (`silvicultura.html`)
Um simulador de manejo florestal com sistema completo de crescimento de árvores.

**Características:**
* 🌳 3 tipos de árvores (Carvalho, Pinheiro, Bétula) com modelos 3D
* 🪓 Sistema realista de corte com machado animado
* 🌰 Plantio de sementes e crescimento progressivo
* 📊 Sistema de inventário (madeira, sementes)
* 💾 Salvamento automático no localStorage
* 💬 Chat integrado para comunicação
* ⚡ Renderização otimizada para performance

**Mecânicas:**
* Cada árvore tem estágios de crescimento (Semente → Muda → Jovem → Adulto)
* Sistema de saúde/dureza das árvores
* Animação realista do machado com física de partículas
* Efeitos visuais ao cortar (lasquinhas de madeira)

### Terraformação (`terraplanagem.html`)
Um simulador de modificação de terreno com ferramentas de construção e mineração.

**Características:**
* ⛰️ Mapa 50×50 com sistema de grid
* 🥄 Pá para terraformação (cavar/colocar terra)
* ⛏️ Picareta para mineração de rochas
* 💧 Sistema de água realista com shader personalizado
* 🗺️ Exportação/importação de mapas (JSON)
* 📈 Sistema de tipos de terreno (grama, terra, areia, argila, rocha)
* 🔢 Labels de grid para precisão na construção

**Mecânicas:**
* Altura variável do terreno (até 20 unidades)
* Sistema de rocha base abaixo do solo
* Diferenças de inclinação e altitude
* Efeitos de partículas ao cavar/minerar
* Natação em corpos d'água

---

## 🚀 Como Executar

### Método 1: Portal Web (Recomendado)
1.  Abra o arquivo `index.html` em qualquer navegador moderno.
2.  Clique no card do jogo desejado.
3.  O jogo será aberto em uma nova janela.

### Método 2: Direto
* Abra `silvicultura.html` para o Sistema de Árvores.
* Abra `terraplanagem.html` para Terraformação.

---

## 🎯 Controles Comuns

**Movimentação**
* **W/A/S/D:** Movimentar-se
* **Espaço:** Pular (ou nadar para cima na água)
* **Shift:** Correr
* **Mouse:** Olhar ao redor

**Interação**
* **Scroll:** Trocar ferramenta/slot
* **1/2/3:** Selecionar ferramenta
* **Clique Esquerdo:** Usar ferramenta atual
* **Clique Direito:** Ação secundária (depende da ferramenta)
* **Enter:** Abrir/fechar chat
* **ESC:** Menu principal

**Interface**
* **F11:** Tela cheia (via menu)
* **Menu:** Salvar/carregar, configurações

---

## 🛠️ Tecnologias Utilizadas

* **Three.js r128:** Renderização 3D no navegador
* **HTML5/CSS3/JavaScript:** Base do projeto
* **WebGL:** Aceleração gráfica
* **localStorage:** Salvamento de dados local
* **Shader Personalizado:** Para efeitos de água

---

## 📁 Estrutura de Arquivos

```text
animalysson/
├── index.html          # Portal principal
├── silvicultura.html   # Sistema de Árvores
├── terraplanagem.html  # Terraformação
