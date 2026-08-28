# Projeto API — Leitor de Texto por Câmera (OCR)
 
Aplicação web que usa a câmera do dispositivo para capturar imagens e extrair o texto contido nelas, utilizando a API externa **Tesseract.js** (OCR).
 
## Como funciona
 
1. Ao abrir a página, a câmera do dispositivo é ativada automaticamente.
2. O usuário clica em **"Ler Texto"**.
3. A imagem atual do vídeo é capturada em um `canvas`, com filtros de contraste e escala de cinza aplicados para melhorar a leitura.
4. A imagem é enviada para o **Tesseract.js**, que reconhece o texto (configurado para português).
5. O texto identificado é exibido na tela.
## Tecnologias
 
- HTML5 / CSS3
- JavaScript
- [Tesseract.js](https://github.com/naptha/tesseract.js) (API de OCR)
- `getUserMedia` (API nativa do navegador para acesso à câmera)
## Como rodar
 
1. Clone o repositório:
```bash
   git clone https://github.com/FIAP-EngSoft-ZackDev/ProjetoApi.git
```
2. Abra o arquivo `index.html` no navegador (recomendado usar uma extensão como *Live Server*, já que o acesso à câmera exige um contexto seguro em alguns navegadores).
3. Permita o acesso à câmera quando solicitado.
4. Aponte a câmera para um texto e clique em **"Ler Texto"**.
## Autor
 
**Isac Oliveira**
[GitHub](https://github.com/zackdevbr) · [LinkedIn](https://www.linkedin.com/in/isac-oliveira-6a711a3a2/)
 
