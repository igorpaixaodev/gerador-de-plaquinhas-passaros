# 🐦 Gerador de Plaquinhas de Pássaros

Um aplicativo web simples, rápido e responsivo para gerar plaquinhas de identificação para gaiolas de pássaros, formatadas perfeitamente para impressão em papel A4.

## 💡 Motivação
Este projeto nasceu de uma necessidade real de casa: meu pai é criador de pássaros e sempre me pedia para montar essas plaquinhas personalizadas para as aves dele. Para automatizar o processo, dar autonomia a ele e facilitar a geração de novas tags de forma rápida, desenvolvi esta ferramenta!

## ✨ Funcionalidades
* **Preenchimento em Lote:** Defina o "Criador" e o "Registro" uma única vez e aplique a todos os cards simultaneamente.
* **Personalização Individual:** Insira Nome, Anilha, Espécie (Nome Popular e Científico) e Sexo para cada pássaro.
* **Upload de Imagens Inteligente:** Adicione fotos colando um link (URL) da internet ou fazendo **upload direto do seu dispositivo** clicando no preview da imagem (as fotos são processadas em Base64).
* **Auto-Salvamento:** Utiliza o `localStorage` do navegador para que você não perca os dados e as fotos enviadas caso feche a aba sem querer.
* **Pronto para Impressão:** CSS configurado com `@media print` para remover os menus e renderizar a folha A4 exata (8 plaquinhas por folha), sem margens indesejadas.
* **Mobile-Friendly:** Interface que se adapta a telas de celulares, transformando a tabela em cards empilhados para facilitar a digitação e o envio de fotos direto da galeria do smartphone.

## 🚀 Como Usar
1. Acesse a página do projeto via navegador (ou abra o arquivo `index.html` localmente).
2. Preencha as **Informações Coletivas** no painel superior e clique no botão para aplicar a todas as placas.
3. Insira as **Informações Individuais** de cada ave. Para adicionar a foto, você pode colar a URL no campo de texto ou **clicar no preview da imagem** para escolher um arquivo do seu computador/celular.
4. Clique em **Imprimir / Salvar PDF**. 
   * *Dica: Na tela de impressão do navegador, certifique-se de desmarcar a opção "Cabeçalhos e rodapés" (Headers and footers) para um acabamento perfeito e sem bordas brancas sobressalentes.*

## 🛠️ Tecnologias Utilizadas
* **HTML5** (Estrutura semântica)
* **CSS3** (Flexbox, CSS Grid, responsividade e formatação de impressão em milímetros)
* **JavaScript** (Vanilla JS para manipulação do DOM, FileReader para imagens em Base64 e persistência de dados local via LocalStorage)

---
*Desenvolvido por Igor Soares da Paixão, para seu pai doido por pássaros.* ☕🐦
