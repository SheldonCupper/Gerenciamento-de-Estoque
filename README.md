# Gerenciamento de Estoque e Vendas

Aplicação web de controle de estoque diário e relatórios, desenvolvida com **HTML, JavaScript e Tailwind CSS**. Projeto de portfólio.

**[🚀 Abrir demonstração online](https://sheldoncupper.github.io/Gerenciamento-de-Estoque/)** · **[💻 Ver código-fonte](https://github.com/SheldonCupper/Gerenciamento-de-Estoque)**

## Funcionalidades

- Cadastro e exclusão de produtos organizados por categoria e subcategoria.
- Definição de limite para identificação de estoque baixo.
- Registro diário dos estoques inicial e final de cada produto.
- Relatório de vendas estimadas (diferença entre estoque inicial e final).
- Consulta de relatórios por data.
- Persistência local usando `localStorage` do navegador.

## Executar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Cadastre produtos e registre os lançamentos.

O projeto está publicado no **GitHub Pages**. Para utilizar no navegador, abra a [demonstração online](https://sheldoncupper.github.io/Gerenciamento-de-Estoque/).

Para atualizar a demonstração, publique alterações na branch `main`; o workflow `.github/workflows/pages.yml` prepara o site estático para o GitHub Pages.

> **Atenção:** os dados ficam apenas no navegador/dispositivo em uso; não há banco de dados remoto, autenticação ou sincronização entre aparelhos. Limpar os dados do site pode remover os registros. A estimativa de vendas é baseada nas quantidades informadas e não considera reposição ou perdas.

## Testes

Antes de usar o sistema como demonstração profissional, consulte o [roteiro de testes manuais](docs/TESTES.md). Os testes de cadastro, relatórios e responsividade devem ser confirmados em um navegador.

## Tecnologias

- HTML5, CSS e JavaScript (sem framework).
- Tailwind CSS via CDN.
- API `localStorage` para persistência.

## Segurança e privacidade

- Dados informados pelo usuário são escapados antes de aparecerem em trechos de HTML gerado dinamicamente.
- O sistema não deve armazenar dados sensíveis ou ser usado como solução corporativa sem controles adicionais.
- Bibliotecas e recursos visuais externos exigem acesso à internet.

## Autor

[Gabriel Alves](https://github.com/SheldonCupper)
