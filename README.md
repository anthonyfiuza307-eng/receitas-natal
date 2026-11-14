# 🎄 Natal de Sobremesas Mágicas — Landing Page Premium

Landing page de altíssima conversão em funil vertical de coluna única para venda de receitas natalinas, projetada com psicologia da confeitaria natalina nobre, micro-interações táteis e fluxo inteligente de upsell/recall.

---

## 🎨 Paleta de Cores de Confeitaria Natalina Premium
- **Fundo Principal:** Creme Baunilha Quente (`#FBF7F0`) alternando com seções de alto impacto em **Verde Pinheiro Natalino Profundo (`#112A1E`)** com textos em Branco Pérola (`#FDFBF7`) e acabamentos em Dourado.
- **Títulos e Textos Principais:** Chocolate Ganache Escuro (`#1E110A`) e Marrom Café (`#452A18`).
- **Destaques e Acabamentos Nobres:** Dourado Ouro Velho / Caramelo (`#C58B17` / `#E5A93C`).
- **Ação & Escassez:** Vermelho Cereja / Natalino Intenso (`#B91C1C` com gradiente para `#881313`).

---

## 🚀 Hero Section Limpa e Otimizada
- **Mockup Transparente Integrado ao Fundo:** O mockup oficial da coleção ([mockup-hero-transparente.png](mockup-hero-transparente.png)) possui fundo 100% transparente (PNG alpha) recortado com precisão e sombras de contato naturais na base. Flutua organicamente sobre o fundo creme baunilha (`#FBF7F0`), com proporção natural sem cortes (`w-full max-w-[560px] h-auto object-contain`), sem bordas retangulares artificiais e com efeito suave de relevo via `filter: drop-shadow(0 18px 28px rgba(30, 17, 10, 0.18))` e leve micro-interação no hover (`hover:scale-[1.02]`).
- **Micro-selos Soltos no Fundo:** Logo abaixo da foto, uma linha sutil e discreta:
  `📖 30 Receitas Testadas • 👩‍🍳 100% Passo a Passo • 📱 PDF Alta Resolução`
- **Chamada Direta:** O botão principal `QUERO GARANTIR MINHAS RECEITAS AGORA` fica posicionado logo abaixo dos micro-selos, sem exibir preço na Hero Section, direcionando o foco do visitante para a rolagem e o valor da oferta.

---

## 💎 Bônus com Ancoragem e Soma Matemática
- Bônus 1 (Planilha de Precificação): De ~~R$ 47,00~~ por R$ 0,00
- Bônus 2 (Lista de Compras Inteligente): De ~~R$ 37,00~~ por R$ 0,00
- Bônus 3 (Guia de Embalagens e Apresentação): De ~~R$ 27,00~~ por R$ 0,00
- **Card de Resumo de Valor:** `DE R$ 111,00 POR R$ 0,00 (GRÁTIS SOMENTE HOJE)`.

---

## 🛒 Lógica de Checkout e Popup de Recall
- **Plano Completo (R$ 29,90):** Ao clicar, vai **diretamente para o checkout** sem abrir popup algum.
- **Plano Básico (R$ 17,90):** Ao clicar, abre o **Popup de Recall / Upgrade Inteligente** oferecendo o Plano Completo com os 3 Bônus de R$ 29,90 por **R$ 25,90** (ou link discreto de recusa para seguir no Básico de R$ 17,90).

---

## ⚙️ Configuração dos Links de Checkout
No final do arquivo `index.html` (dentro da tag `<script>`), personalize as variáveis com suas URLs:

```javascript
const LINK_CHECKOUT_BASICO_17_90   = "https://pay.kiwify.com.br/SEU_LINK_BASICO_17_90";
const LINK_CHECKOUT_COMPLETO_29_90 = "https://pay.kiwify.com.br/SEU_LINK_COMPLETO_29_90";
const LINK_CHECKOUT_UPGRADE_25_90  = "https://pay.kiwify.com.br/SEU_LINK_UPGRADE_25_90";
```

---

## 🎨 Histórico de Atualizações Recentes (Refinamento Visual & Conversão)
- **Neve Suave & Discreta na Hero (CSS Puro):** Flocos delicados e brilhos sutis dourados e brancos em baixa opacidade (`0.30 - 0.35`) com animação contínua e acelerada por hardware (`z-0` e `pointer-events: none`), posicionados estritamente atrás do conteúdo e do mockup.
- **Divisórias Natalinas Nobres:** Linhas finas em degradê dourado com ornamentos centrais minimalistas (`✦ ❄️ ✦`, `✦ ✨ ✦`, `✦ 🎁 ✦`, `✦ 🎄 ✦`), além de badges estilizados em formato pill de alta confeitaria.
- **Acabamento "Presente de Natal" nos Cards de Destaque:**
  - *Plano Completo:* Borda em ouro velho, brilho radial suave no topo (`blur-2xl`) e badge com laço/presente natalino (`🎁 MAIS ESCOLHIDO — 87% DAS CLIENTES ✨`).
  - *Resumo de Valor dos Bônus:* Brilho radial dourado no topo e selo festivo de presente.
- **Mockup Hero 100% Transparente & Orgânico:** O arquivo [mockup-hero-transparente.png](mockup-hero-transparente.png) recortado com precisão e sombras naturais na base, integrado perfeitamente ao fundo creme baunilha sem cortes ou caixas pretas.
- **Rastreamento Meta Pixel:** Meta Pixel Code (`1355838073247780`) integrado no `<head>` com evento de `PageView`.
- **Rastreamento de UTMs NexoFy:** Script inteligente na `<head>` com persistência em cookie e `localStorage` (`nexofy_utm`), injetando parâmetros (`utm_source`, `utm_campaign`, `fbclid`, `src`, etc.) dinamicamente em todos os links e botões de checkout.
- **Correção Total de Imagens & Proporções:**
  - Proporção harmoniosa `aspect-video` em todos os depoimentos visuais (sem faixas comprimidas).
  - 100% das fotos dedicadas a sobremesas natalinas reais e apetitosas.
- **Ícone Corrigido na Seção de Dores:** Substituído o ícone inexistente pelo `fa-solid fa-sack-dollar` no card "Deixar dinheiro na mesa em dezembro".
- **Remoção de Elementos Fora do Padrão:** Removido o bloco "Pessoas Ocupadas" para manter simetria e fluidez visual.
- **Rodapé Limpo e Centralizado:** Estrutura estrita de 3 linhas (Marca, Copyright © 2026 e Links Institucionais), eliminando avisos desnecessários de terceiros.
- **Codificação UTF-8 Blindada:** Zero artefatos de mojibake, acentuação e emojis nativos em português do Brasil impecáveis.
