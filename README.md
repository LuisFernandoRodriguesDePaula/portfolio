# Luis Fernando — Portfólio

Portfólio de desenvolvimento de software com projetos, contexto de implementação e decisões técnicas. A apresentação prioriza uma leitura direta do trabalho, com aprofundamento para quem deseja avaliar o código.

**Estado atual:** primeira versão local, com identidade visual definida e Dieta Fácil como projeto em destaque. Formação, experiência, contatos adicionais e demais projetos estão em preparação. O site ainda não possui endereço público de demonstração.

## Projeto em destaque

### [Dieta Fácil](https://github.com/LuisFernandoRodriguesDePaula/dieta-facil)

Aplicação de planejamento alimentar construída com React, TypeScript, Java, Spring Boot e PostgreSQL. A base atual inclui autenticação, edição de perfil, demonstração de refeições e catálogo pessoal de alimentos. Estoque, compras e preparo fazem parte da evolução prevista.

O repositório do produto contém sua implementação, instruções de execução e documentação técnica. Este repositório contém o site que apresenta o trabalho.

## Implementação do portfólio

- HTML semântico e CSS responsivo, sem dependências externas.
- Apresentação, projetos, estudo de caso, tecnologias, trajetória e contato.
- Detalhes técnicos expansíveis, preservando uma leitura inicial concisa.
- Link para pular ao conteúdo, foco visível e respeito à preferência por movimento reduzido.
- Servidor Node.js opcional para prévia local, restrito a `127.0.0.1`.

A implementação estática atende ao escopo de apresentação. Não há necessidade de banco de dados ou de um framework para os recursos atuais.

## Executar localmente

É possível abrir `index.html` diretamente no navegador. Para usar uma prévia HTTP, com Node.js instalado:

```sh
node server.cjs
```

Acesse **http://127.0.0.1:4173**. Para encerrar, use `Ctrl+C`. Não é necessário instalar pacotes.

## Organização

```text
assets/                  Imagens utilizadas no site
index.html               Estrutura e conteúdo da página
styles.css               Identidade visual e regras responsivas
server.cjs               Servidor opcional de desenvolvimento local
docs/                    Planejamento e diretrizes de conteúdo
```

## Próximas entregas

1. Definir o posicionamento profissional e completar os contatos e o currículo.
2. Consolidar o estudo de caso do Dieta Fácil com contribuição, demonstração e evidências atualizadas.
3. Selecionar mais dois projetos reais, mantendo um quarto como opcional.
4. Concluir a revisão de acessibilidade, layout em diferentes telas e publicação.

Os espaços reservados da página pertencem à versão de trabalho. Serão substituídos ou removidos antes da publicação do site.

## Validação

Foram conferidos os arquivos locais, destinos de navegação interna e a sintaxe do servidor. A revisão visual completa em navegador e as verificações de acessibilidade e desempenho ainda estão pendentes. O site não possui testes automatizados de interface neste estágio.

## Documentação

- [Plano de evolução](docs/EVOLUCAO.md)
- [Guia de conteúdo e estrutura](docs/GUIA-DO-PORTFOLIO.md)
- [Identidade visual](docs/IDENTIDADE.md)
- [Prioridades de entrega e organização do GitHub](docs/PRIORIDADES.md)

O retrato usado no site foi editado com IA a partir de fotografia fornecida pelo titular e aprovado provisoriamente por ele. As funcionalidades dos projetos são descritas conforme seu estado documentado, sem métricas de uso ou resultados comerciais presumidos.
