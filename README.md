O UniCode é uma plataforma completa e moderna para a criação, personalização e análise de QR Codes. Inspirado no popular qr-code-styling, o UniCode eleva a experiência do usuário ao integrar Inteligência Artificial e ferramentas de análise em tempo real, tudo dentro de uma interface Dark Mode sofisticada e responsiva.

🚀 Recursos Principais

🎨 Personalização Extrema
Estilização de Pontos e Cantos: Escolha entre diversos formatos (Square, Rounded, Extra Rounded, Classy, etc.).
Gradientes Avançados: Suporte a gradientes lineares e radiais para pontos, cantos e fundo.
Integração de Logo: Adicione sua marca ao centro do QR Code com controle total de tamanho e margem.

🤖 Inteligência Artificial (AI Assistant)
Geração por Linguagem Natural: Use o assistente integrado (Gemini AI) para criar conteúdos complexos como vCards, configurações de WiFi ou links dinâmicos apenas descrevendo o que você precisa.

📊 Scannability Intelligence
Análise em Tempo Real: Um algoritmo proprietário avalia o contraste e a complexidade do seu design, fornecendo uma pontuação de escaneabilidade e dicas para garantir que o código funcione em qualquer dispositivo.

📸 Scanner & Importação
Decodificador Integrado: Use sua câmera ou faça upload de uma imagem para escanear QR Codes existentes. O UniCode extrai os dados e permite que você os reestilize instantaneamente.

⚡ Presets de Estilo
Galeria de Temas: Aplique designs profissionais (como Cyberpunk Neon ou Golden Luxury) com apenas um clique.

🛠️ Tecnologias Utilizadas
React 19 & TypeScript - Base robusta e tipada para a aplicação.
Tailwind CSS - Estilização moderna e responsiva com foco em performance.
qr-code-styling - Biblioteca principal para renderização de alta fidelidade.
Google Gemini AI (@google/genai) - Motor de inteligência artificial para o assistente de conteúdo.
jsQR - Processamento de imagem e decodificação de QR Codes no lado do cliente.
Lucide React - Conjunto de ícones minimalistas e consistentes.
Vite - Build tool ultra-rápida para o desenvolvimento front-end.

🌟 Diferenciais
Diferente de geradores comuns, o UniCode foca na experiência do designer e na segurança do dado:
Privacidade Total: O escaneamento e a geração ocorrem localmente no navegador.
UX Premium: Interface organizada em painéis sanfonados (accordions) para manter o foco no preview em tempo real.
Exportação Versátil: Suporte para PNG, JPEG e SVG (vetorial).

💡 Como rodar o projeto

- Clone o repositório:

code
Bash
git clone https://github.com/seu-usuario/unicode.git
- Instale as dependências:

code
Bash
npm install

- Configure sua chave da API do Gemini no arquivo .env:

code
Env
GEMINI_API_KEY=sua_chave_aqui

- Inicie o servidor de desenvolvimento:

code
Bash
npm run dev
