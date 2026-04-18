# Layout-de-fabrica-
link: https://loadix7.github.io/Layout-de-fabrica-

Esse editor nasceu de uma necessidade real do jogo de empresa Engenho Treinamentos: montar layouts de chão de fábrica de forma visual, sem ferramentas pesadas. É um único arquivo HTML — abre no navegador, sem instalação. Arrasta peças, conecta fluxos, salva automático.
Engenho Editor — Layout Interativo de Chão de Fábrica

Projeto de estudo desenvolvido por Kaique Mota — 9º Semestre, Engenharia de Produção

Sobre o projeto
Esse editor nasceu de uma necessidade real: o jogo de empresa Engenho Treinamentos simula uma fábrica, e eu precisava de uma forma visual e interativa de montar e apresentar layouts de chão de fábrica sem depender de ferramentas pesadas como AutoCAD ou Visio.
O resultado é um editor 2D completo, que roda direto no navegador, sem instalação. Você arrasta peças no grid, define zonas de produção, conecta máquinas com setas de fluxo e o layout fica salvo automaticamente — mesmo que você feche a aba.
É um arquivo HTML. Só isso. Abre no navegador e funciona.

Funcionalidades__>

Grid interativo de 34×26m com snap por célula
Drag & drop de peças — máquinas, operadores, estoques, produtos
Redimensionamento por alças nas bordas de qualquer elemento
Zonas demarcadas (ex: Área de Produção, Estoque) com cor e opacidade configuráveis
Setas de fluxo animadas conectando peças — mostra o caminho do produto
Seleção em área — selecione, mova ou delete um grupo inteiro de uma vez
Menu de contexto (botão direito) com duplicar, editar e remover
Ícones customizados — carregue uma imagem PNG em qualquer peça ou zona
Fornecedores laterais configuráveis com nome e cor
Métricas em tempo real — utilização do grid, capacidade total, colisões
Zoom de 40% a 300% via slider ou Shift+scroll
Autosave automático — o layout é salvo no localStorage a cada mudança
Slots nomeados — salve versões com nome e carregue quando quiser
Responsivo — adapta o tamanho das células para mobile, tablet e desktop


Tecnologias
Por quê HTML + CSS inlineZero dependências externas, roda em qualquer lugarReact 18 (via CDN)Gerenciamento de estado reativo sem buildBabel StandaloneJSX no navegador, sem compilaçãolocalStoragePersistência real sem backendSVGRenderização das setas de fluxo animadas
Sem Node. Sem npm. Sem Webpack. Um arquivo, um double-click, funciona.

#Como usar
# Abra o arquivo no navegador
open engenho-editor.html
Ou simplesmente baixe o engenho-editor.html e abra direto. Não precisa de servidor.

Como utilizar o projeto/funcionalidades:
Ação Como Mover peça,Arrastar,Redimensionar Alças nas bordas,Menu (duplicar ATALHO_TECLA(D), editar, remover TECLA DEL/BACKSAPCE) Botão direito pressionado e arrastar selecionando Excluir, Botão esquerdo mouse seleciona e arrasta para selecionar e mover  fluxo Seleção em área(atalho tecla numero ´´3´´ ativa e desativa selecionador) ZoomShift + scrollCancelarEsc

Contexto acadêmico
Esse projeto faz parte das atividades práticas do curso de Engenharia de Produção. O jogo Engenho Treinamentos é uma simulação de supply chain e produção industrial — esse editor serve como ferramenta de apoio para montar e apresentar cenários de layout antes de rodar a simulação.
A ideia era algo que qualquer aluno ou instrutor conseguisse abrir no próprio computador, sem precisar instalar nada ou entender de programação.

Licença
Projeto de uso acadêmico. Fique à vontade para adaptar e usar como referência.
