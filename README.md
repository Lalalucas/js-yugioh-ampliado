<h1 align="center">🃏 Yu-Gi-Oh! - Projeto Ampliado com JavaScript, HTML5 e CSS3</h1>
<p align="center">
  <strong>Versão profissional e reestruturada do desafio original da DIO.me</strong><br>
  Desenvolvido por <a href="https://github.com/Lalalucas">Lucas Gabriel de Morais</a> • 
  <a href="mailto:lucasescobarmorais@gmail.com">Contato</a> • 
  <a href="https://linkedin.com/in/lucasgdm">LinkedIn</a>
</p>

---

## 🎯 Objetivo

Este projeto visa reestruturar e expandir o jogo de cartas Yu-Gi-Oh! proposto no desafio da DIO.me, aplicando uma abordagem moderna com foco em **organização modular, escalabilidade, interatividade**, e melhores práticas de desenvolvimento front-end.

---

## ⚔️ Comparativo com o Projeto Original

| Característica                     | Repositório Original (`js-yugioh-assets`)     | Esta Versão Ampliada (`js-yugioh-ampliado`)  |
|----------------------------------|-----------------------------------------------|----------------------------------------------|
| Organização do Código            | Estrutura plana com HTML e JS no mesmo nível  | Arquitetura modular (MVC simplificado)       |
| Modularidade                     | Baixa                                          | Alta: assets, components, views, controllers |
| Estilização                      | Básica, pouco responsiva                      | CSS moderno, layout responsivo               |
| Interatividade                   | Limitada                                      | Efeitos visuais, eventos otimizados          |
| Reusabilidade de Código          | Baixa                                          | Componentes reutilizáveis                    |
| Expansão de conteúdo             | Manual e limitada                             | Preparado para novas cartas, modos e temas   |
| Documentação (README, Regras)   | Resumida                                      | Completa, com guia técnico e estrutura detalhada |
| Recursos visuais e sonoros      | Parcial                                       | Estrutura pronta para BGM, vídeos, fontes    |

---

## 📦 Estrutura do Projeto

---

## 🧠 Detalhes Técnicos da Implementação

- **JavaScript**: lógica separada, uso de `addEventListener`, criação dinâmica de cartas via DOM.
- **CSS3**: layout responsivo, hover effects, escurecimento de fundo, transições suaves.
- **HTML5**: semântica aprimorada, separação de responsabilidades entre conteúdo e estilo.
- **Preparação para expansões**: fácil inserção de novas cartas, trilhas sonoras, temas e personagens.

---

## 🕹️ Mudanças na Jogabilidade

- ✅ **Cards dinâmicos**: criados em tempo real via JS, com efeito `hover`.
- ✅ **Melhor visualização**: layout centralizado, adaptável para mobile e desktop.
- ✅ **Separação de lógica**: facilita leitura e manutenção do código.
- 🔜 **Expansão futura planejada**:
  - Sistema de duelos interativo
  - Modos de jogo (Campanha, Multiplayer local)
  - Pontuação e efeitos visuais avançados

---

## 🧪 Como Executar Localmente

```bash
git clone git@github.com:Lalalucas/js-yugioh-ampliado.git
cd js-yugioh-ampliado
termux-open index.html  # ou abra manualmente via navegador