# upload.ai (API)

Esse é o backend da aplicação upload.ai, desenvolvida durante o NLW IA da Rocketseat. 

A ideia é que o usuário faça upload de um vídeo e gere sugestões de título e descrição para o YouTube utilizando a tecnologia da OpenAI.

Para isso, o backend recebe o vídeo, extrai o áudio e envia para a API da OpenAI para receber a transcrição. Em seguida, usa essa transcrição para pedir sugestões de título ou descrição, a depender do que está especificado no prompt.

## Como executar?

0. Tenha o Node instalado
1. Faça o clone/download do repositório
2. Execute `npm i`
3. Execute `npx prisma db seed`
4. Execute `npm run dev`

## Como testar as rotas?

0. Instale a extensão REST Client para VSCode
1. Utilize o arquivo `routes.http` na raiz do projeto

ou utilize um cliente como o Postman ou Insomnia

## Como acessar o banco de dados?

O Prisma conta com um cliente para acessar o banco de dados. 

Para acessá-lo, execute `npx prisma studio` e aguarde uma nova aba ser aberta no navegador. 

O endereço é especificado no terminal.