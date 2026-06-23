
---

## 🚀 Como Executar

1. **Baixe** o arquivo `index.html`.
2. **Abra** em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).
3. **Jogue** diretamente no navegador — sem necessidade de servidor ou instalação.

---

## 🎮 Modos de Jogo

O jogo possui **7 modos** que alteram a experiência:

| Modo | Descrição |
|------|-----------|
| **Clássico** | Base fixa com bots, expressões, humor e mini-missões. |
| **Gotas Especiais** | Gotas raras (ouro, velocidade, verniz, cura, tinta preta) aparecem. |
| **Trepadeiras BR** | Zona segura que encolhe e trepadeiras drenam massa. |
| **Rastros de Tinta** | Blobs deixam rastros que dão impulso ou deixam o chão escorregadio. |
| **Eventos Vivos** | Eventos temporários: chuva, vento, florada, chá e manchas. |
| **Power-ups** | Ferramentas temporárias (pincelada, carimbo, cola, etc.). |
| **Zonas do Mapa** | Regiões com regras próprias (jardim, lago, bosque, etc.). |
| **Personalizado** | Combine mecânicas ativando/desativando cada modo. |

---

## 🧩 Mecânicas Fixas (sempre ativas)

- Bots com personalidades (covarde, guloso, caçador, etc.)
- Expressões faciais e humor visual
- Mini-missões dinâmicas com recompensas
- Divisão de célula (Espaço)
- Ejeção de massa (W)
- Dash (Shift)
- Vírus que explodem células grandes
- Bordas elásticas
- Sistema de ranking e massas

---

## 🕹️ Controles

| Tecla / Ação | Função |
|--------------|--------|
| `Mouse` / `Toque` | Movimento |
| `Espaço` | Dividir célula |
| `W` | Ejetar massa |
| `Shift` | Dash (impulso) |
| `P` | Pausar |
| `ESC` | Voltar ao menu |
| `Toque` (mobile) | Joystick + botões (dividir, ejetar, dash, pausa) |

---

## 🎨 Interface

- **Menu principal**: seleção de modo, ajustes (bots, comidas, stop motion, trepidação, FPS visual)
- **HUD durante o jogo**: massa, posição, mini-missão, leaderboard, minimapa, status do modo
- **Modal de seleção de modo**: descrição detalhada e toggles para customização
- **Tela de Game Over**: exibe massa final e missões completadas

---

## ⚙️ Personalização

No menu principal, você pode ajustar:

- Número de bots (`5 a 70`)
- Quantidade de comidas (`120 a 1300`)
- Ativação de **stop motion** (efeito visual)
- FPS visual (`6 a 30`)
- Intensidade da trepidação (`0 a 4`)
- Controles touch (forçar ativação em desktop)

---

## 🧠 Lógica do Jogo

### 📦 Classes principais

- `Cell`: representa qualquer blob (jogador, bot)
- `Food`: itens consumíveis (normais ou especiais)
- `Virus`: obstáculo que explode células grandes
- `PowerUp`: ferramentas temporárias
- `Decoy`: cópias falsas (do power-up "carimbo")
- `Zone`: regiões com efeitos especiais

### 🧬 Personalidades dos Bots

| Personalidade | Comportamento |
|---------------|---------------|
| Covarde | Foge de ameaças |
| Guloso | Prioriza comida |
| Caçador | Persegue presas |
| Bobo | Movimento errático |
| Gigante Lento | Grande, mas devagar |
| Nervosinho | Rápido e imprevisível |

---

## 🧪 Eventos Especiais (Modo 4)

- **Chuva de tinta**: chove comida
- **Vento de papel**: empurra todos os blobs
- **Florada**: manchas de flores geram comida
- **Hora do chá**: deixa todos mais calmos
- **Manchas pretas**: desaceleram e sujam a visão

---

## 🧰 Power-ups (Modo 5)

| Nome | Efeito |
|------|--------|
| Pincelada | Dash + velocidade |
| Carimbo | Cria cópias falsas |
| Aquarela | Absorve comida em área |
| Solvente | Reduz massa de rivais próximos |
| Cola | Aura que desacelera rivais |

---

## 🗺️ Zonas do Mapa (Modo 6)

| Zona | Efeito |
|------|--------|
| Jardim de Papel | Mais comida e movimento suave |
| Lago de Tinta | Desacelera e suja a visão |
| Bosque das Trepadeiras | Prende blobs grandes |
| Mesa do Pintor | Mais power-ups |
| Mancha Seca | Drena massa lentamente |

---

## 📊 Estado e Progresso

- **Massa total** do jogador
- **Ranking** entre todos os blobs
- **Mini-missões** com barra de progresso
- **Histórico**: comidas, especiais, power-ups, bots absorvidos, tempo em eventos, etc.

---

## 📱 Suporte Mobile

- Joystick virtual
- Botões dedicados (dividir, ejetar, dash, pausa)
- Interface adaptável

---

## 🧪 Testes e Depuração

- Modo "calmo" e "caótico rápido" para testes
- Opção de forçar controles touch no desktop
- Feedback visual via toasts e vibração (em dispositivos compatíveis)

---

## 🛠️ Tecnologias Utilizadas

- HTML5 + CSS3 (estilos modernos com gradientes, blur, bordas arredondadas)
- JavaScript puro (sem bibliotecas externas)
- Canvas 2D (renderização do jogo)
- CSS Grid e Flexbox (layout responsivo)
- Pointer Events (suporte a mouse e toque)

---

## 📄 Licença

Este projeto é de uso livre para fins educacionais e de estudo. Modificações e distribuição são permitidas com atribuição ao autor original.

---

## ✨ Créditos

Desenvolvido como um exemplo de jogo web interativo com foco em interface visual, mecânicas modulares e comportamento orgânico de NPCs.

---

**Divirta-se pintando o mundo! 🎨**