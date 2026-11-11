# Novara Kwanza Bookshop

Cria um website moderno, profissional e responsivo para uma livraria digital chamada NOVARA BOOKS.

1. Objetivo da plataforma

A plataforma deve permitir que o administrador publique livros para venda, defina os preços e receba pedidos de compra dos clientes.

O site deve funcionar como uma loja virtual de livros, com uma experiência simples, elegante e intuitiva.

2. Design e identidade visual

Nome: NOVARA BOOKS.

Estilo: minimalista, moderno, sofisticado e profissional.

Cores principais: preto, branco e dourado.

Design adaptado para telemóveis, tablets e computadores.

Animações suaves e navegação rápida.

Interface semelhante à de uma livraria digital profissional.

3. Página inicial

Criar:

Logótipo NOVARA BOOKS.

Menu de navegação.

Barra de pesquisa de livros.

Banner principal com uma mensagem apelativa.

Secção de livros em destaque.

Secção de novidades.

Secção de livros mais vendidos.

Botão para explorar todos os livros.

4. Catálogo de livros

Cada livro deve apresentar:

Imagem da capa.

Título.

Autor.

Descrição.

Categoria.

Preço em kwanzas (Kz).

Botão “Comprar agora”.

Botão “Mais informações”.

Criar categorias como:

Desenvolvimento pessoal.

Finanças e negócios.

Psicologia.

Romance.

Educação.

Religião.

Tecnologia.

5. Painel administrativo

Criar um painel privado, acessível apenas pelo administrador.

O administrador deve conseguir:

Adicionar novos livros.

Carregar imagens das capas.

Inserir título e autor.

Escrever a descrição.

Escolher a categoria.

Definir e alterar o preço.

Editar livros publicados.

Eliminar livros.

Publicar ou retirar livros da loja.

Consultar os pedidos recebidos.

Acompanhar o histórico de vendas.

Não colocar o painel administrativo acessível aos clientes.

6. Sistema de compras

Implementar duas possibilidades:

OPÇÃO A — Compra automática

O cliente seleciona um livro, adiciona ao carrinho e finaliza a compra.

Criar uma estrutura preparada para integrar pagamentos digitais em Angola, através de um provedor compatível, com confirmação do pagamento e registo da encomenda.

O dinheiro deve ser encaminhado para a conta do comerciante através do provedor de pagamentos configurado.

Não simular pagamentos nem apresentar transações fictícias como reais.

OPÇÃO B — Compra por contacto

Quando o cliente clicar em “Comprar pelo WhatsApp”, deve ser redirecionado para uma conversa com o administrador.

A mensagem deve ser preenchida automaticamente com:

“Olá! Tenho interesse em comprar o livro [NOME DO LIVRO], que custa [PREÇO] Kz. Gostaria de saber como posso efetuar o pagamento.”

Criar também um botão para copiar os dados da encomenda.

7. Gestão de pedidos

O administrador deve visualizar:

Nome do cliente.

Livro solicitado.

Preço.

Data do pedido.

Estado do pedido.

Estados possíveis:

Pendente.

Aguardando pagamento.

Pago.

Entregue.

Cancelado.

8. Base de dados

Utilizar Supabase para:

Autenticação do administrador.

Armazenamento dos livros.

Imagens das capas.

Registo de encomendas.

Gestão dos dados dos clientes.

Implementar regras de segurança para impedir que visitantes alterem livros, preços ou encomendas.

9. Rodapé

Adicionar:

Sobre a NOVARA BOOKS.

Contactos.

WhatsApp.

Instagram.

Política de privacidade.

Termos e condições.

10. Requisitos finais

Todo o site deve estar em português.

Utilizar o kwanza (Kz) como moeda.

O site deve funcionar perfeitamente em telemóveis.

Criar uma experiência simples para comprar livros.

Não utilizar dados fictícios como se fossem vendas reais.

Criar uma plataforma funcional, não apenas uma demonstração visual.

Prioridade: desenvolver primeiro o catálogo, o painel administrativo e o sistema de pedidos por WhatsApp. Deixar a estrutura preparada para pagamentos automáticos.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://novara-kwanza-bookshop.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/11c41c8e-5db9-5bb1-b846-a566566b0cac).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
