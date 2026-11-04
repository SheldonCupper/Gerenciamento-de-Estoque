# Roteiro de testes manuais

Este sistema armazena os dados no `localStorage` do navegador. **Antes de executar os testes, utilize uma janela anônima ou um perfil de navegador separado**, para evitar mexer em registros reais.

## Cenários

- [ ] Abrir a [demonstração](https://sheldoncupper.github.io/Gerenciamento-de-Estoque/) em computador e celular e verificar a interface.
- [ ] Acessar **Adicionar/Gerenciar Produtos**, cadastrar um produto com nome, categoria e limite de estoque igual a 5 e verificar se aparece na lista.
- [ ] Atualizar a página e confirmar que o produto cadastrado permanece.
- [ ] Criar um produto com caracteres como `<teste> & "aspas"` no nome; conferir que eles aparecem como texto e **não** executam HTML.
- [ ] Testar rejeição de limites de estoque negativos ou inválidos.
- [ ] Registrar estoque inicial de 10 e final de 7. Gerar relatório do dia e conferir a estimativa de **3 unidades** vendidas.
- [ ] Testar rejeição de quantidades negativas e de estoque final maior que o inicial.
- [ ] Consultar um relatório por data e conferir que o lançamento aparece no dia local correto.
- [ ] Verificar aviso de estoque baixo quando o saldo final for menor ou igual ao limite cadastrado.
- [ ] Excluir um produto de teste e verificar sua remoção da lista.

## Limitações conhecidas

- Dados e relatórios ficam no dispositivo/navegador onde foram cadastrados; não há sincronização ou cópia automática.
- A estimativa de vendas é calculada a partir da diferença entre estoque inicial e final; reposições, perdas e outras movimentações não são consideradas.
- O projeto utiliza Tailwind CSS via CDN e outros recursos externos, portanto parte da apresentação depende de internet.
- Testes automatizados de interface ainda não estão configurados.

Ao encontrar um problema, registre a etapa, o resultado esperado, o resultado observado e, se possível, uma captura de tela em uma issue do repositório.
