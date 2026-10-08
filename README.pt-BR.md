# UI Design for Devs

Uma coleção de ferramentas, referências, boas práticas e recursos de UI/UX voltados para desenvolvedores.

A ideia deste repositório é reunir conteúdos úteis em um único lugar, facilitando consultas durante o desenvolvimento de interfaces e compartilhando esse conhecimento com a comunidade.

## Ferramentas e Referências

### Miro

Miro é um quadro colaborativo usado para brainstorming, organização de ideias, criação de fluxos, wireframes e moodboards. É especialmente útil nas etapas iniciais de planejamento e exploração visual.

[https://miro.com](https://miro.com)

### Adobe Color

Adobe Color é uma ferramenta para explorar paletas de cores prontas e criar combinações para projetos de interface. Vá até a seção **Explore**, pesquise termos como *dark*, *finance*, *food* ou *technology* e utilize as cores HEX da paleta escolhida.

[https://color.adobe.com/](https://color.adobe.com/)

### Adobe Contrast Checker

Ferramenta para verificar se as cores de texto e fundo possuem contraste adequado para acessibilidade e se atendem aos critérios da WCAG.

[https://color.adobe.com/br/create/color-contrast-analyzer](https://color.adobe.com/br/create/color-contrast-analyzer)

### Dribbble

Plataforma para buscar referências e inspiração de UI/UX, incluindo aplicativos, sites, dashboards, componentes e conceitos visuais.

[https://dribbble.com/](https://dribbble.com/)

### Mobbin

Biblioteca de referências baseada em interfaces reais de aplicativos e produtos conhecidos. Útil para estudar fluxos como login, onboarding, checkout, navegação e pagamentos.

[https://mobbin.com/](https://mobbin.com/)

### Google Fonts

Biblioteca gratuita de fontes para sites, aplicativos e outros projetos de interface.

- **Legibilidade:** escolha fontes que funcionem bem em diferentes tamanhos e telas.
- **Personalidade:** fontes como Roboto, Lato, Open Sans, Montserrat e Poppins ajudam a definir o tom da interface.
- **Emoção:** fontes serifadas costumam transmitir uma sensação mais tradicional, enquanto fontes decorativas podem parecer mais informais.
- **Combinações:** use a tipografia para criar hierarquia visual e, de preferência, limite a interface a **1 ou 2 famílias de fontes**.

[https://fonts.google.com/](https://fonts.google.com/)

### Unsplash

Fotos de alta qualidade para sites, aplicativos e projetos de UI.

[https://unsplash.com/](https://unsplash.com/)

### Pixabay

Fotos, ilustrações, vetores e vídeos gratuitos para projetos criativos.

[https://pixabay.com/](https://pixabay.com/)

### Pexels

Fotos e vídeos gratuitos para sites, aplicativos e apresentações.

[https://www.pexels.com/](https://www.pexels.com/)

### Freepik

Fotos, vetores, ilustrações, ícones e outros recursos gráficos. Alguns conteúdos exigem atribuição ou licença premium.

[https://br.freepik.com/](https://br.freepik.com/)

### Phosphor Icons

Biblioteca de ícones limpos e consistentes para projetos de interface, disponíveis em SVG e em diferentes estilos e espessuras.

[https://phosphoricons.com/](https://phosphoricons.com/)

## Análise Heurística

Uma análise heurística é uma avaliação estruturada da interface utilizando princípios de usabilidade como referência.

No caso das **Heurísticas de Nielsen**, são analisados pontos como feedback do sistema, clareza das informações, consistência, prevenção de erros e controle do usuário.

O objetivo é identificar problemas de usabilidade antes mesmo de realizar testes com usuários reais.

## Contexto de Produto e UX

Antes de avaliar uma interface, também é importante entender o contexto do produto:

- Quais são os principais objetivos da aplicação?
- Quem é o público-alvo?
- Quais são suas necessidades e preferências?
- Como o produto se diferencia da concorrência?
- Quais são os principais fluxos de usuário?
- Como o modelo de negócio influencia a experiência e a interface?

## Problemas Comuns de UI

**Profundidade excessiva de navegação:** muitas camadas até chegar a uma funcionalidade importante podem tornar a experiência confusa.

**Navegação confusa:** conexões pouco claras entre seções dificultam encontrar informações.

**Redundância de conteúdo:** conteúdos semelhantes ou duplicados podem gerar confusão e dificultar a navegação.

## Heurísticas de Usabilidade de Nielsen — Exemplos em PDV

- **Visibilidade do status do sistema:** Mantenha o usuário informado sobre o que está acontecendo.
  - **Exemplo:** Após enviar um pedido para a cozinha, mostre status como **Enviando** ou **Pronto**.

- **Correspondência entre o sistema e o mundo real:** Use linguagem, conceitos e convenções familiares ao usuário.
  - **Exemplo:** Use termos como **Mesa**, **Pedido**, **Cozinha**, **Conta** e **Dividir pagamento**, evitando termos técnicos do sistema.

- **Controle e liberdade do usuário:** Permita desfazer, cancelar ou voltar facilmente.
  - **Exemplo:** Se um garçom adicionar um item errado, permita removê-lo antes de confirmar o pedido.

- **Consistência e padrões:** Mantenha padrões, ícones, termos e comportamentos consistentes.
  - **Exemplo:** Botões como **Confirmar**, **Cancelar**, **Pagar** e **Voltar** devem manter o mesmo comportamento em todo o PDV.

- **Prevenção de erros:** Crie interfaces que ajudem o usuário a evitar erros.
  - **Exemplo:** Impeça o fechamento de uma mesa enquanto ainda existir saldo pendente.

- **Reconhecimento em vez de memorização:** Mostre opções e informações em vez de obrigar o usuário a lembrar delas.
  - **Exemplo:** Exiba categorias, números de mesa, formas de pagamento e produtos mais usados diretamente na tela.

- **Flexibilidade e eficiência de uso:** Atenda tanto usuários iniciantes quanto experientes.
  - **Exemplo:** Novos funcionários podem usar menus visíveis, enquanto usuários experientes podem utilizar atalhos e favoritos.

- **Design estético e minimalista:** Evite informações desnecessárias e excesso visual.
  - **Exemplo:** Durante o lançamento de um pedido, mostre apenas as informações e ações necessárias para aquela tarefa.

- **Ajude o usuário a reconhecer, diagnosticar e corrigir erros:** Mostre mensagens claras e possíveis soluções.
  - **Exemplo:** Em vez de **"Erro de pagamento 105"**, mostre **"Pagamento recusado. Tente outro cartão ou forma de pagamento."**

- **Ajuda e documentação:** Forneça orientação quando necessário.
  - **Exemplo:** Ofereça ajuda contextual para operações como dividir uma conta, transferir itens entre mesas ou cancelar um pagamento.

  
## Padrões de UI já Estabelecidos

Uma boa interface muitas vezes utiliza padrões já consolidados em outros produtos.

Usuários desenvolvem expectativas com base nas interfaces que já conhecem, e seguir essas convenções reduz o esforço cognitivo.

Por exemplo, aplicativos de e-commerce normalmente posicionam o ícone do carrinho no canto superior direito, geralmente acompanhado de um indicador com a quantidade de itens.

O objetivo não é copiar outro produto, mas utilizar padrões que os usuários já reconhecem.

## Testes de Usabilidade

Testes de usabilidade consistem em observar pessoas utilizando um site, aplicativo ou sistema para identificar dificuldades, dúvidas e pontos de fricção.

### Como Fazer

- Defina o que deseja testar.
- Escolha participantes semelhantes aos usuários reais.
- Prepare tarefas específicas.
- Observe sem interferir.
- Analise padrões e dificuldades recorrentes.

**Exemplo:** em um aplicativo de receitas, peça ao usuário para encontrar uma receita específica. Se vários participantes tiverem dificuldade, a navegação, organização ou busca provavelmente precisa ser melhorada.

Os testes de usabilidade fazem parte do **Design Centrado no Usuário**, abordagem focada em criar produtos úteis, fáceis de usar e alinhados às necessidades reais das pessoas.
