# Password Generator
- Este é um gerador de senhas interativo desenvolvido com React no front-end e Node.js no back-end. Ele permite criar senhas fortes e personalizadas, com várias opções para atender às suas necessidades.

## Demonstração

### Recursos
- Definir o comprimento da senha.
- Adicionar letras maiúsculas e minúsculas.
- Incluir números e símbolos.
- Interface limpa e responsiva.
- Desenvolvido usando React e estilizado para uma experiência de usuário moderna.
### Tecnologias Utilizadas
### Front-end:
- React: Para criar a interface de usuário interativa.
- CSS/FontAwesome: Para estilização e ícones.
### Back-end:
- Node.js: Para processamento de regras de geração de senhas.
### Pré-requisitos
- Node.js (v16 ou superior)
- npm ou yarn
## Como Executar Localmente
### Clone o repositório:
- git clone https://github.com/seu-usuario/password-generator.git
- cd password-generator

### Instale as dependências:
- npm install
### Inicie o servidor de desenvolvimento:
- npm start
- A aplicação estará disponível em http://localhost:3000.

### Inicie o servidor Node.js:
Em uma aba separada no terminal, vá para o diretório do back-end e execute:
- node server.js
### Estrutura do Projeto
password-generator/
├── public/             # Arquivos públicos estáticos
├── src/                # Código-fonte React
│   ├── components/     # Componentes reutilizáveis
│   ├── styles/         # Arquivos de estilo (CSS)
│   ├── App.js          # Componente principal
│   └── index.js        # Ponto de entrada React
├── server/             # Código do back-end Node.js
│   ├── server.js       # Servidor Node.js
├── package.json        # Configurações do projeto e dependências
├── README.md           # Este arquivo
└── .gitignore          # Arquivos ignorados pelo Git
### Próximos Passos
Implementar suporte para salvar configurações de senha.
Adicionar suporte para exportar senhas geradas (em texto ou arquivo).
Melhorar a responsividade em dispositivos móveis.
### Contribuições
#### Contribuições são bem-vindas! Siga estas etapas para colaborar:
- Faça um fork do repositório.
- Crie um branch para sua feature (git checkout -b feature/sua-feature).
- Commit suas alterações (git commit -m 'Adicionei minha feature').
- Envie seu branch para o repositório (git push origin feature/sua-feature).
- Abra um Pull Request.