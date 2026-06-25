# greenLAB // Complexo Cultural Urbano
Diferentes subculturas. O mesmo teto de concreto.
Manifesto vivo de um ecossistema industrial que gerencia, abriga e potencializa marcas líderes em seus nichos de identidade, estética e arte urbana.

// O PROJETO
O site da greenLab funciona como a plataforma central e o mural digital do galpão. Desenvolvido sob uma estética brutalista e street, o projeto atua como um hub de convergência: centraliza a comunicação da marca mãe e distribui de forma direta as conexões de agendamento para cada um dos estúdios independentes que dividem o complexo industrial.

💻 Estúdios Integrados na Banca:
ESTÚDIO 01 // DAMASIO: Alta performance em estética automotiva e procedimentos avançados de tratamento de elite.

ESTÚDIO 02 // YELLOW.INK: O santuário da modificação corporal e caligrafia urbana autoral por Tatuadesson.

ESTÚDIO 03 // BROOKLYN AFRO: Especialistas em tranças de impacto, cortes cirúrgicos e exaltação da identidade preta urbana.

// ARQUITETURA DE DESIGN & FEATURES
Layout Invasivo (Floating Frames): Quadros de fotografia analógica que invadem as bordas laterais do site através de profundidade em camadas (z-index).

Efeito Parallax Intercalado: Transições limpas com imagens fixas de fundo (background-attachment: fixed) que quebram as seções de conteúdo e se estendem até o rodapé de forma contínua.

Calhas Laterais Dinâmicas: Textura escura de tijolos aparentes vazando sutilmente apenas nas duas extremidades fixas da tela, separadas por linhas sólidas de marcação.

Responsividade Brutal: Layout totalmente flexível com grades inteligentes (CSS Grid e Flexbox) que recalculam textos (clamp) e empilham seções perfeitamente em dispositivos móveis, desativando elementos flutuantes para garantir a usabilidade.

Pontos de Conversão Flutuantes: Botões de ação rápida e fixos do WhatsApp e Instagram para contato direto com a curadoria geral do galpão.

// ESTRUTURA DOS ARQUIVOS
O projeto foi construído em arquitetura limpa (Vanilla Web), sem dependências de frameworks pesados:

Bash
├── index.html          # Estrutura semântica e blocos dos estúdios
├── style.css           # Estilização brutalista, tipografias e Media Queries
├── main.js            # Motor JavaScript para transição dinâmica de conteúdo
└── media/              # Diretório local de identidades visuais e fotografias

// COMO RODAR LOCALMENTE
Clone o repositório para a sua máquina:

Bash
git clone https://github.com/seu-usuario/greenlab.git
Navegue até a pasta do projeto:

Bash
cd greenlab
Abra o arquivo principal:

Basta dar um duplo clique no arquivo index.html ou utilizar a extensão Live Server no VS Code para rodar com atualização em tempo real.

// PROTOCOLO DE DESENVOLVIMENTO (GIT)
Para manter o repositório organizado seguindo a nossa colinha de produção, utilize o fluxo padrão:

Bash
# 1. Crie uma branch para o ajuste necessário
git checkout -b feature/ajuste-estudio

# 2. Adicione as alterações e firme o ponto com commits curtos
git add .
git commit -m "feat: adicionado cor da borda customizada no bloco afro"

# 3. Empurre para o servidor
git push origin feature/ajuste-estudio
// LICENÇA & DIREITOS
Projetado na cultura de rua. Código estruturado para a aliança greenLab Complexo. Todo o conteúdo textual e organização de marca operam sob regras de propriedade intelectual da sociedade criativa do galpão.
