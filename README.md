# upload-AI
O Upload-AI é um projeto que utiliza as APIs da OpenAI para permitir o upload de vídeos e, por meio da inteligência artificial, criar automaticamente títulos chamativos e descrições com boa indexação.

Utilizei o shadcn/ui que é coleção de componentes reutilizáveis e personalizáveis ​​para copiar e colar em algumas partes desse projeto.

## Funcionalidades Principais
- **Upload de Vídeos:** Faça o upload de seus vídeos com facilidade.
- **Geração de Títulos Cativantes:** Utilize a IA para criar títulos atraentes com base no conteúdo do vídeo.
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
