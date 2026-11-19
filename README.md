# Cesta Certa

**Compre melhor. Alimente-se melhor. Desperdice menos.**

O **Cesta Certa** é um protótipo acadêmico desenvolvido para a Global Solution da FIAP, no eixo CitizenTech. A proposta é apoiar o planejamento das compras e o aproveitamento dos alimentos em casa, reunindo informações sobre orçamento, comparação de mercados, planejamento de refeições e organização da despensa.

O projeto parte de um desafio cotidiano: fazer escolhas de consumo mais econômicas e conscientes, aproveitando melhor os alimentos e reduzindo o desperdício.

## Objetivo

Facilitar o planejamento alimentar e das compras domésticas por meio de uma ferramenta que considera não apenas o preço dos produtos, mas também o custo e o tempo de deslocamento até os mercados, os alimentos disponíveis em casa e a prioridade de consumo de cada item.

## Funcionalidades do protótipo

- **Planejamento de compras:** criação de uma lista de produtos e quantidades, considerando o número de pessoas e o orçamento informado.
- **Comparação de mercados:** visualização de estimativas que consideram os preços dos itens, a distância e o custo de deslocamento.
- **Detalhamento da escolha:** consulta aos valores e às informações da opção selecionada.
- **Planejamento de refeições:** sugestões de preparações a partir dos alimentos disponíveis e dos itens da lista.
- **Organização da despensa:** registro dos alimentos e acompanhamento de estimativas de vida útil, para ajudar a identificar o que deve ser consumido primeiro.

## Estrutura do protótipo

A experiência está organizada em seis telas:

1. **Início:** apresentação da proposta e configuração do perfil, com informações como número de pessoas, orçamento e região.
2. **Lista de compras:** inclusão e organização dos produtos que compõem a compra.
3. **Mercados:** apresentação e comparação das estimativas de custo das opções disponíveis.
4. **Detalhes:** informações da opção selecionada e detalhamento dos valores.
5. **Cardápio:** sugestões de refeições para aproveitar os ingredientes disponíveis.
6. **Despensa:** registro dos alimentos e acompanhamento da prioridade de consumo.

> **Sobre os dados:** esta é uma versão demonstrativa, com dados simulados de produtos, preços, distâncias e sugestões. O protótipo não consulta preços em tempo real, não realiza compras e não está conectado a serviços externos. A integração com fontes reais de dados e o uso de inteligência artificial são possibilidades de evolução do projeto, não recursos conectados nesta versão.

## Tecnologias utilizadas

- **HTML5:** estrutura e conteúdo das telas.
- **CSS3:** identidade visual, estilos e adaptação da interface a diferentes tamanhos de tela.
- **JavaScript:** navegação, interações e lógica do protótipo.
- **LocalStorage:** armazenamento local dos dados do protótipo e das preferências no navegador.
- **Google Fonts:** utilização das famílias tipográficas Bowlby One e Public Sans.

A aplicação está concentrada no arquivo `index.html` e não exige instalação de dependências ou configuração de backend para ser executada. As fontes do Google Fonts são carregadas externamente quando há conexão com a internet.

## Como acessar

### Versão online

Acesse o protótipo publicado pelo GitHub Pages:

**https://mariccmaci.github.io/cesta-certa/**

### Execução local

1. Clone o repositório ou faça o download dos arquivos.
2. Abra o arquivo `index.html` em um navegador atualizado.
3. Explore as telas e interações.

Para clonar o repositório pelo terminal:

```bash
git clone https://github.com/mariccmaci/cesta-certa.git
cd cesta-certa
```

Em seguida, abra o arquivo `index.html` no navegador.

## Acessibilidade e experiência do usuário

O protótipo incorpora recursos para tornar a navegação mais clara e acessível, como:

- Layout responsivo para diferentes tamanhos de tela.
- Link para pular diretamente ao conteúdo principal.
- Indicadores visíveis de foco para navegação por teclado.
- Estrutura semântica e identificação de áreas da interface.
- Mensagens de status anunciadas por tecnologias assistivas.
- Controle para ampliar os textos e aplicar ajustes de contraste.

## Identidade visual

A identidade visual aproxima a interface do universo das feiras livres e da cultura alimentar brasileira. A paleta combina verde, amarelo, azul e vermelho sobre um fundo claro. A Bowlby One dá personalidade aos títulos, enquanto a Public Sans favorece a leitura dos textos e elementos de interface.

## Autoria

**Mariana Costa Cruz Maciel**  
RM: 570455  
FIAP — Global Solution | CitizenTech

## Licença e finalidade

Projeto desenvolvido para fins acadêmicos, como parte da Global Solution da FIAP.
