# ai-azure-vision-services

Objetivo: Utilizar a plataforma Azure da Microsoft para fazer reconhecimento de textos em imagens.

Passos:

1 - Entrar no portal Azure da Microsoft -> https://portal.azure.com

2 - Criar o "resource" - "Azure AI services"

3 - Entrar no portal Vision Studio -> https://portal.vision.cognitive.azure.com

4 - Selecionar o "resource" que foi criado no Portal Azure da Microsoft.

5 - Após selecionado o "resource", descer a página e clicar no link "Optical character recognition".

6 - Subir imagem com textos, aguardar o processamento e do lado direito verificar os textos que foram extraídos da imagem.

Veja abaixo alguns exemplos do reconhecimento:

Exemplo 1: O texto foi reconhecido 100% 

1 - Imagem selecionada para ser reconhecida.

![1-img-teste](https://github.com/marcuslinares/ai-azure-vision-services/assets/29169323/5c2b814a-f31b-4468-bcc1-f87abd4ad5e9)

2 - Resultado do processamento e do reconhecimento de texto.

![1-img-teste-reconhecimento-texto](https://github.com/marcuslinares/ai-azure-vision-services/assets/29169323/dc0b38e1-34e5-4ef3-9c0a-b2d1c637f4ee)



Exemplo 2: O texto não foi reconhecido 100% devido ao tipo de fonte utilizada.

1 - Imagem selecionada

![2-img-teste](https://github.com/marcuslinares/ai-azure-vision-services/assets/29169323/64c24485-86d3-4616-ade0-dad45e79ab52)

2 - Texto reconhecido na imagem

![2-img-teste-reconhecimento-texto](https://github.com/marcuslinares/ai-azure-vision-services/assets/29169323/bf0f5f6b-a164-4235-9b90-0928c7c7d2d0)


Conclusão:

Analisando os resultados é possível concluir que a ferramenta de reconhecimento funciona bem para textos sem utilização de fontes em formatos diferentes, porém o serviço se mostra muito útil e fácil de utilizar, na documentação da Microsoft é fácil encontrar exemplos de códigos e instruções de como utilizar o serviço em seus projetos.



Referências:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html

https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/quickstarts-sdk/image-analysis-client-library-40?tabs=visual-studio%2Clinux&pivots=programming-language-csharp
