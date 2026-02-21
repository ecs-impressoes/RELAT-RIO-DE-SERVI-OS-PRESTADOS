# 📋 Relatório de Serviços – Documento Online

Este é um modelo de relatório de serviços prestados, desenvolvido em HTML, CSS e JavaScript puro. Ele permite registrar os serviços realizados para uma empresa, calcular totais automaticamente, anexar uma foto do trabalho e gerar uma versão para impressão/PDF.

## 🚀 Funcionalidades

- **Dados gerais**: campos para nome da empresa, data de execução e colaborador responsável.
- **Anexo de foto**: upload de imagem com pré-visualização.
- **Tabela de serviços**:
  - Descrição do serviço
  - Quantidade
  - Valor unitário
  - Cálculo automático do total por linha (quantidade × valor unitário)
  - Botão para adicionar novas linhas
  - Botão para remover linhas (a última linha apenas é limpa)
- **Total geral** atualizado em tempo real.
- **Campo de observações**: para descrever detalhes adicionais sobre o que foi feito.
- **Botão de impressão**: gera uma versão limpa para impressão ou para salvar como PDF (oculta os botões e campos de edição).
- **Design responsivo**: funciona bem em computadores, tablets e celulares.
- **Pronto para hospedagem**: basta fazer o upload de um único arquivo HTML.

## 📸 Captura de tela

![Prévia do relatório](https://via.placeholder.com/800x400?text=Prévia+do+Relatório+de+Serviços)  
*(Substitua pela imagem real do seu projeto)*

## 🛠️ Como usar

1. **Preencha os campos**:
   - Nome da empresa/cliente
   - Data de execução
   - Nome do colaborador
2. **Anexe uma foto** clicando no campo de upload (opcional).
3. **Adicione os serviços** na tabela:
   - Descreva o serviço
   - Informe a quantidade e o valor unitário
   - O total da linha e o total geral são calculados automaticamente
4. **Adicione mais linhas** clicando no botão “Adicionar outro serviço”.
5. **Preencha observações** no campo inferior, se necessário.
6. **Imprima ou salve em PDF** usando o botão “Imprimir / Salvar PDF”. O layout será adaptado para impressão.

## 🌐 Hospedagem (como site)

Você pode disponibilizar este relatório online de forma gratuita:

### Opção 1 – GitHub Pages
1. Crie uma conta em [github.com](https://github.com).
2. Crie um novo repositório (ex.: `relatorio-servicos`).
3. Faça upload do arquivo `index.html` (ou o nome que preferir).
4. No repositório, vá em **Settings > Pages**.
5. Em "Branch", selecione `main` e salve.
6. Seu site estará disponível em `https://seuusuario.github.io/relatorio-servicos`.

### Opção 2 – Netlify Drop
1. Acesse [app.netlify.com/drop](https://app.netlify.com/drop).
2. Arraste a pasta com o arquivo `index.html` para a área indicada.
3. Pronto! Você receberá um link temporário (pode personalizar depois).

### Opção 3 – Uso local
Basta salvar o código em um arquivo com extensão `.html` e abri-lo diretamente no navegador. Todas as funcionalidades funcionam offline.

## 🎨 Personalização

- Altere cores, fontes ou textos no código HTML e CSS (dentro das tags `<style>`).
- Para adicionar seu logotipo, insira uma `<img>` no topo do documento.
- Para incluir campos adicionais, edite a seção `info-geral` no HTML.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se à vontade para usar, modificar e distribuir.

---

**Desenvolvido com ❤️ para facilitar a criação de relatórios de serviços.**