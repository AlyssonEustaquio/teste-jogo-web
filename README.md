<a href="https://alyssoneustaquio.github.io/teste-jogo-web/">
  <img src="https://img.shields.io/badge/JOGAR%2520AGORA-FF6B6B?style=for-the-badge&logo=gamejolt&logoColor=white&labelColor=2C2C2C&logoWidth=30" alt="Jogar Agora" />
</a>

🌲 Animalysson.io
https://img.shields.io/badge/%F0%9F%8C%90_Acesse_o_Portal_Animalysson.io-00aa00?style=for-the-badge&logo=github

Jogos de Simulação 3D no Navegador

Animalysson.io é uma coleção de jogos de simulação 3D desenvolvidos com Three.js, rodando diretamente no navegador. Explore mundos interativos, gerencie florestas e molde terrenos com ferramentas realistas.

🎮 Jogos Disponíveis
1. Sistema de Árvores (silvicultura.html)
Um simulador de manejo florestal com sistema completo de crescimento de árvores.

Características:

🌳 3 tipos de árvores (Carvalho, Pinheiro, Bétula) com modelos 3D

🪓 Sistema realista de corte com machado animado

🌰 Plantio de sementes e crescimento progressivo

📊 Sistema de inventário (madeira, sementes)

💾 Salvamento automático no localStorage

💬 Chat integrado para comunicação

⚡ Renderização otimizada para performance

Mecânicas:

Cada árvore tem estágios de crescimento (Semente → Muda → Jovem → Adulto)

Sistema de saúde/dureza das árvores

Animação realista do machado com física de partículas

Efeitos visuais ao cortar (lasquinhas de madeira)

2. Terraformação (terraplanagem.html)
Um simulador de modificação de terreno com ferramentas de construção e mineração.

Características:

⛰️ Mapa 50×50 com sistema de grid

🥄 Pá para terraformação (cavar/colocar terra)

⛏️ Picareta para mineração de rochas

💧 Sistema de água realista com shader personalizado

🗺️ Exportação/importação de mapas (JSON)

📈 Sistema de tipos de terreno (grama, terra, areia, argila, rocha)

🔢 Labels de grid para precisão na construção

Mecânicas:

Altura variável do terreno (até 20 unidades)

Sistema de rocha base abaixo do solo

Diferenças de inclinação e altitude

Efeitos de partículas ao cavar/minerar

Natação em corpos d'água

🚀 Como Executar
Método 1: Portal Web (Recomendado)
Abra o arquivo index.html em qualquer navegador moderno

Clique no card do jogo desejado

O jogo será aberto em uma nova janela

Método 2: Direto
Abra silvicultura.html para o Sistema de Árvores

Abra terraplanagem.html para Terraformação

🎯 Controles Comuns
Movimentação
W/A/S/D: Movimentar-se

Espaço: Pular (ou nadar para cima na água)

Shift: Correr

Mouse: Olhar ao redor

Scroll: Trocar ferramenta/slot

1/2/3: Selecionar ferramenta

Interação
Clique Esquerdo: Usar ferramenta atual

Clique Direito: Ação secundária (depende da ferramenta)

Enter: Abrir/fechar chat

ESC: Menu principal

Interface
F11: Tela cheia (via menu)

Menu: Salvar/carregar, configurações

🛠️ Tecnologias Utilizadas
Three.js r128: Renderização 3D no navegador

HTML5/CSS3/JavaScript: Base do projeto

WebGL: Aceleração gráfica

localStorage: Salvamento de dados local

Shader Personalizado: Para efeitos de água

📁 Estrutura de Arquivos
text
animalysson/
│
├── index.html              # Portal principal
├── silvicultura.html       # Sistema de Árvores
├── terraplanagem.html      # Terraformação
│
├── README.md               # Este arquivo
│
└── assets/                 # (Opcional) Diretório para recursos futuros
    ├── textures/
    ├── models/
    └── sounds/
🔧 Requisitos do Sistema
Navegador moderno (Chrome 90+, Firefox 88+, Edge 90+)

WebGL habilitado

Resolução mínima: 1024×768

Conexão com internet (apenas para carregar Three.js do CDN)

💾 Sistema de Salvamento
Sistema de Árvores
Salva automaticamente a cada 30 segundos

Dados salvos: posição do jogador, inventário, árvores

Chave no localStorage: animalysson_forest_save

Terraformação
Salva automaticamente após modificações

Dados salvos: mapa de altura, tipo de terreno, inventário

Chave no localStorage: animalysson_world_save

Exportação para arquivo JSON disponível

🎨 Personalização
Alterar Nome do Jogador
No console do navegador:

javascript
// Sistema de Árvores
player.name = "NovoNome";
document.getElementById('player-name-display').textContent = player.name;

// Terraformação  
player.name = "NovoNome";
document.getElementById('player-name-display').textContent = player.name;
Modificar Configurações
Edite diretamente nos arquivos HTML:

MAP_SIZE: Tamanho do mapa

TILE_SIZE: Tamanho de cada tile

BASE_MOVE_SPEED: Velocidade do jogador

WATER_HEIGHT: Nível da água

⚠️ Problemas Conhecidos
Performance em dispositivos antigos: Reduza a resolução do navegador

Pop-ups bloqueados: Permita pop-ups para abrir jogos do portal

WebGL não suportado: Verifique suporte do navegador

🔮 Melhorias Futuras
Planejadas:
Sistema multiplayer

Mais tipos de árvores/terreno

Ferramentas adicionais

Clima e ciclo dia/noite

Sons e música ambiente

Missões/objetivos

Em Consideração:
Exportação de modelos 3D

Modo criativo/sandbox

Suporte a texturas personalizadas

Modding API

🤝 Contribuindo
Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/NovaFuncionalidade)

Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade')

Push para a branch (git push origin feature/NovaFuncionalidade)

Abra um Pull Request

📝 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para detalhes.

👤 Autor
Animalysson.io
Desenvolvido com ❤️ para entusiastas de simulação 3D

🙏 Agradecimentos
Equipe do Three.js pela incrível biblioteca

Comunidade de desenvolvimento de jogos web

Todos os testadores e contribuidores

Nota: Este é um projeto educacional/demonstrativo. Recursos avançados podem exigir servidor backend para funcionalidades completas.

Divirta-se explorando e criando! 🎮✨

https://img.shields.io/badge/%F0%9F%8C%90_Acesse_o_Portal_Animalysson.io-00aa00?style=for-the-badge&logo=github
