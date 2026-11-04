# Gerenciamento de Estoque e Vendas

Aplicação web de controle de estoque diário e relatórios, desenvolvida com **HTML, JavaScript e Tailwind CSS**. Projeto de portfólio.

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

O projeto também pode ser hospedado como site estático no GitHub Pages, após tornar o repositório público e configurar **Settings → Pages → Deploy from a branch → main / (root)**.

> **Atenção:** os dados ficam apenas no navegador/dispositivo em uso; não há banco de dados remoto, autenticação ou sincronização entre aparelhos. Limpar os dados do site pode remover os registros. A estimativa de vendas é baseada nas quantidades informadas e não considera reposição ou perdas.

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
