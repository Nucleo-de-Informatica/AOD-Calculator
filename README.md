# FIVEM Motorcycle Modifications Website

Este site permite aos utilizadores personalizar motos no FIveM, oferecendo várias opções de modificações, como ajustes de desempenho (full tune), personalização de jantes, cor primária e secundária, alteração de chaparias, etc... O site também inclui modificadores de preços baseados no tipo de relação do utilizador com o servidor: **parceria**, **comissão** ou **prospect**.

## Funcionalidades

### 1. **Opções de Modificação**
O utilizador pode personalizar a moto com diversas modificações, que incluem ajustes no desempenho, estilo e características exclusivas. Abaixo estão as opções disponíveis:

- **Full Tune:** Ajustes completos no desempenho da moto, com preço variável de acordo com a classe da moto:
  - Classe A: 45.000
  - Classe B: 75.000
  - Classe C: 105.000
  - Classe D: 135.000
  - Classe E: 165.000
  - Classe F: 200.000

- **Turbo:** Melhorias no sistema de turbo, com preço calculado com base no valor de `fullTune` (40% do preço de Full Tune).
  - Exemplo: Para Classe A, Turbo = 40% de 45.000 = 18.000.

- **Motor:** Upgrades no motor da moto, com preço também calculado com base no valor de `fullTune` (40% do preço de Full Tune).
  - Exemplo: Para Classe A, Motor = 40% de 45.000 = 18.000.

- **Transmissão:** Modificação na transmissão da moto, com preço calculado com base no valor de `fullTune` (40% do preço de Full Tune).
  - Exemplo: Para Classe A, Transmissão = 40% de 45.000 = 18.000.

- **Armadura (50.000):** Aumento da resistência da moto com armadura adicional.

- **Travões (15.000):** Melhoria nos travões da moto para um melhor desempenho em frenagens.

- **Primário (7.500):** Personalização da cor da moto com pintura primária.

- **Secundário (7.500):** Personalização da cor da moto com pintura secundária.

- **Perolado (7.500):** Adiciona um efeito perolado na pintura da moto.

- **Autocolante (10.000):** Adição de um autocolante decorativo.

- **Xenon (35.000):** Instalação de faróis de xenon.

- **Jantes (15.000):** Personalização das jantes da moto.

- **Cor das Jantes (5.000):** Alteração da cor das jantes.

- **Cor da Matrícula (7.500):** Personalização da cor da matrícula.

- **Pneus à prova de bala (50.000):** Pneus reforçados para maior resistência.

- **Buzina (3.000):** Instalação de uma buzina personalizada.

- **Fumaça (30.000):** Adição de fumaça personalizada nos pneus.

- **Vidro (30.000):** Alteração do vidro para um tipo mais resistente ou estilizado.

### 2. **Modificadores de Preço**
- **Parceria:** Se a modificação for feita para uma parceria, será aplicada uma redução percentual no preço.
- **Comissão:** Se o utilizador for uma comissão, será aplicada uma porcentagem adicional ao preço total.
- **Prospect:** Se for para um prospect, será aplicada uma redução adicional no preço.

### 3. **Cálculo do Preço Total**
O preço total será calculado com base nas modificações escolhidas e no tipo de relacionamento com o servidor, levando em conta os modificadores. O preço final será apresentado com e sem IVA de 16%, permitindo ao utilizador ver a diferença.

### 4. **Envio para o Discord**
Após calcular o preço total, o nome do utilizador e os detalhes da modificação serão enviados automaticamente para um servidor Discord via webhook, facilitando a comunicação com a equipe.

## Como Utilizar

1. Selecione as modificações desejadas para a sua moto.
2. Escolha o tipo de relação com o servidor (Parceria, Comissão ou Prospect).
3. O site calculará o preço total, com e sem IVA.
4. O seu pedido será enviado para o Discord, onde poderá ser processado pela equipe.

## Tecnologias Utilizadas
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express (ou outra stack de sua preferência)
- **Banco de Dados:** MySQL ou MongoDB (dependendo da sua escolha)
- **Webhook:** Integração com o Discord para envio de mensagens automáticas.

## AVISO

Este projeto está protegido por direitos autorais. Ao utilizar este código e conteúdo, o utilizador concorda em cumprir as leis de direitos autorais aplicáveis. Nenhuma parte do conteúdo ou código deste projeto pode ser reproduzida, distribuída, modificada ou utilizada para fins comerciais sem a devida autorização. O uso do código é restrito à finalidade pessoal ou acadêmica, sendo proibido utilizá-lo em projetos comerciais sem expressa permissão do detentor dos direitos autorais. 

Os utilizadores devem garantir que as suas utilizações do código não infrinjam os direitos de propriedade intelectual do autor. Qualquer violação dos direitos autorais pode resultar em ações legais.
