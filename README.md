# 🧩 Mini SPA Acessível - Thiago Rodrigues Guedes

Este repositório contém um projeto de exemplo para **entrega final** da disciplina — SPA em JavaScript com foco em acessibilidade (WCAG 2.1 AA), controle de versão e otimização para produção.

## Autor
**Thiago Rodrigues Guedes**  
Desenvolvedor Front-End | Estudante de Tecnologia  
📧 thiagorodriguesguedes18@gmail.com  
🔗 Perfil GitHub: https://github.com/thiagorodriguesguedes18-ai

---

## Tecnologias
- HTML5 semântico
- CSS3 (com foco em contraste e foco acessível)
- JavaScript (Vanilla ES6+)
- Git/GitHub (recomenda-se GitFlow para versionamento)

---

## Como executar
1. Baixe ou clone o repositório:
```bash
git clone https://github.com/thiagorodriguesguedes18-ai/spa-javascript-projeto.git
```
2. Abra `index.html` no navegador.

---

## Acessibilidade
- Skip link para pular ao conteúdo principal
- Navegação por teclado nas links do menu
- Labels e atributos `aria-*` em campos e mensagens
- Mensagens de status com `role="status"` e `aria-live`
- Alto contraste ativável

---

## Otimização
Na pasta `css/` e `js/` incluí versões simplificadas (minified) dos arquivos que você pode usar em produção.

---

## Estrutura do projeto
```
meu-projeto-spa-final/
├── index.html
├── css/
│   ├── style.css
│   └── style.min.css
├── js/
│   ├── spa.js
│   ├── validation.js
│   ├── main.js
│   └── main.min.js
└── img/
```

---

## Recomendações para nota máxima
1. **Git:** crie branches `develop`, `feature/acessibilidade`, faça commits semânticos e abra Pull Requests para `develop`. Marque releases (`v1.0.0`) no GitHub.
2. **README:** mantenha o README atualizado (este arquivo já está pronto).
3. **Acessibilidade:** faça testes com a tecla Tab, leitores de tela (NVDA/VoiceOver) e verifique contraste.
4. **Otimização:** comprima imagens e use as versões `.min.*` dos arquivos para produção.
5. **Documente:** em Issues explique o que foi feito e crie um milestone “Entrega Final”.

---

## Licença
MIT

---

Boa sorte! Se quiser, eu gero o ZIP com tudo pronto e posso também criar um `CHANGELOG.md` e um exemplo de `ISSUE`/`PULL_REQUEST_TEMPLATE.md`. Quer que eu adicione esses arquivos também?
