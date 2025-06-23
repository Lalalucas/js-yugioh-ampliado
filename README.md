<h1 align="center">🃏 Yu-Gi-Oh! – Projeto Ampliado com JavaScript, HTML5 e CSS3</h1>
<p align="center">
  <strong>Versão profissional e reestruturada do desafio original da DIO.me</strong><br>
  Desenvolvido por <a href="https://github.com/Lalalucas">Lucas Gabriel de Morais</a> • 
  <a href="mailto:lucasescobarmorais@gmail.com">Contato</a> • 
  <a href="https://linkedin.com/in/lucasgdm">LinkedIn</a> • 
  Signal: MoraisLGM
</p>

---

## 🎯 Objetivo  
Este projeto visa reestruturar e expandir o jogo de cartas Yu‑Gi‑Oh! original da DIO.me, aplicando estrutura modular com foco em **escala, interatividade**, melhores práticas de front‑end e código limpo.

---

## ⚔️ Comparativo com o Projeto Original

| Característica                     | Original (`js‑yugioh‑assets`) | Ampliado (`js‑yugioh‑ampliado`) |
|-----------------------------------|-------------------------------|---------------------------------|
| Organização do Código             | Plana e centralizada           | MVC simplificado e modular       |
| Modularidade                      | Baixa                          | Alta: assets, components, views...|
| Estilização                       | Básica, não responsiva         | CSS moderno, responsivo         |
| Interatividade                    | Limitada                       | Eventos, efeitos visuais        |
| Reusabilidade                     | Baixa                          | Componentes reutilizáveis       |
| Expansão de conteúdo              | Manual                         | Preparado para novas cartas     |
| Documentação                      | Resumida                       | Completa: guia técnico + regras |
| Recursos visuais e sonoros        | Mínimos                        | Pronto para BGM, vídeos, fontes|

---

## 📦 Estrutura do Projeto


---

## 🧠 Detalhes Técnicos

### Linguagens e Frameworks
- **HTML5**: marcação semântica.
- **CSS3**: layout responsivo, transições, hover, variáveis customizadas.
- **JavaScript (ES6+)**: modularização por arquivos; DOM API, `addEventListener`, classes, módulos.
- **Audio e Visual**: suporte a BGM, efeitos sonoros, cursores e favicon personalizados.
- **Arquitetura**: MVC simplificado, separação lógica, views e models.

### Estrutura Modular
- `components/`: cria elementos visuais com JS (ex: cards dinâmicos).
- `views/`: organiza telas principais (campo, menu, modal).
- `controllers/`: implementa lógica principal (abrir cartas, comparar, contadores).
- `models/`: define configuração de cartas, estados de jogo.
- `utils/`: funções comuns como shuffle, delay, formatação de tempo.

---

## 🕹️ Mudanças na Jogabilidade

1. **Cartas dinâmicas**: todas criadas em runtime via JS.
2. **Efeitos visuais**: estilo hover, flip e transição suave.
3. **Layout responsivo**: centralizado, adaptável à tela do dispositivo.
4. **Contadores de tempo e movimentos** integrados futuramente via controllers.
5. **Preparado para melhorias**:
   - Modos de jogo (Campanha, Duelo local)
   - Pontuação, Rankings, Efeitos visuais e auditivos
   - Expansão de cartas e temas

---

## 🔧 Como Executar Localmente

```bash
git clone git@github.com:Lalalucas/js-yugioh-ampliado.git
cd js-yugioh-ampliado
termux-open index.html  # ou abra manualmente no navegador