# upload-AI
O Upload-AI é um projeto que utiliza as APIs da OpenAI para permitir o upload de vídeos e, por meio da inteligência artificial, criar automaticamente títulos chamativos e descrições com boa indexação.

Utilizei o shadcn/ui que é coleção de componentes reutilizáveis e personalizáveis ​​para copiar e colar em algumas partes desse projeto.

## Funcionalidades Principais
- **Upload de Vídeos e converter em áudio:** Faça o upload de seus vídeos com facilidade e converte em áudio usando a IA.
- **Prompt de transcrição:** Coloque algumas paralvras chaves, técnicas para ajudar na hora da IA detectar as palavras ditas no vídeo na hora da transcrição.
- **Prompt de base:** Prompts que são basicamente umas instruções para a nossa IA gerar materias com base no vídeo que fizemos upload. Ao selecionar qual o modelo de prompt você quer ele mostrará um template já pronto e editável (Se caso for editar o prompt já pronto não tire a variáve ```{transcription}``` pois essa variável incluio texto gerado a partir da transcrição do vídeo carregado.).
- **Temperatura:** A tempertura determina o nível de criatividade e ao mudar ela a IA retorna uma respostas mais criativas porém com mais chances de erros.
- **Fácil de Usar:** Uma interface amigável e intuitiva torna a experiência de upload e geração de metadados rápida e simples.

## Tecnologias usada no Front-End
- ReactJS
- TypeScript
- Axios
- lucide-react
- TailwindCSS
- shadcn/ui

## Tecnologias usada no Back-End
- prisma
- TypeScript
- Fastify
- openai
- zod
 

## Instalação e Uso
- Instale as dependências:
  ```npm install```
- Configure suas credenciais da OpenAI no seu backend na pasta .env:
  ```OPENAI_API_KEY=sua-chave-de-api-aqui```
- Inicie a aplicação:
  ```npm run dev```
