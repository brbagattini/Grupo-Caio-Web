# SocialConnect

**SocialConnect** é uma plataforma de rede social moderna que permite aos usuários criar perfis, compartilhar atualizações, seguir outras pessoas e interagir por mensagens privadas. O projeto visa oferecer uma experiência social fluida e intuitiva, tanto para desktop quanto para dispositivos móveis.

---

## 📌 Objetivo do Projeto

O objetivo deste repositório é manter e evoluir o site institucional da plataforma **SocialConnect**, resolvendo problemas visuais e funcionais, além de implementar novas funcionalidades solicitadas por usuários reais.

---

## 🔧 Funcionalidades

- ✅ Correção de imagens quebradas e padronização de cores conforme a identidade visual (#2980b9)
- ✅ Atualização do rodapé com ano correto e correção ortográfica
- ✅ Restauração do conteúdo correto da seção "Sobre nós"
- ✅ Adição do item “Projetos” ao menu de navegação
- 🚧 Nova seção "Equipe" com descrição sobre os colaboradores
- 🚧 Nova seção de "Contato" com telefone, e-mail e horário de atendimento
- 🚧 Inclusão de ícones de redes sociais (LinkedIn e Instagram) no rodapé

---

## 📂 Estrutura de Branches

Este projeto segue um fluxo de versionamento colaborativo com base em **Pull Requests**. Nenhum commit é feito diretamente na `main`.

- `main` → Protegida, somente via Pull Request
- `correcao-sobre-nos` → Recuperação do texto correto da seção Sobre nós
- `secao-equipe` → Criação da nova seção sobre a equipe (baseada em `correcao-sobre-nos`)
- `contato-rodape-redes` → Adição da seção de contato e redes sociais (baseada em correção do rodapé)
- Outras branches específicas para cada tarefa/funcionalidade

---

## 💡 Tecnologias Utilizadas

- HTML5
- CSS3
- Git & GitHub
- VS Code

---

## Nome dos integrantes:

- Ana Clara Ribeiro dos Santos
- Arthur Ferreira Alves dos Santos
- Bruno Bagattini Fernandes
- Nathália dos Santos Cordeiro
- Ulisses Ribeiro Abreu

Todos os commits seguem o padrão **Conventional Commits**, como por exemplo:

```bash
feat(menu): adiciona item "Projetos" ao menu principal

fix(rodape): corrige ano e letras faltando no rodapé
