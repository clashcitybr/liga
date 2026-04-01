# ⚔️ Clash City BR - Portal de Convocação CWL

Este é o módulo de mobilização tática da Família Clash City BR. Um sistema de abas dinâmico projetado para informar a escalação oficial da Liga de Clãs de forma rápida e intuitiva.

> **Confira a lista:** [clashcitybr.github.io/liga/](https://clashcitybr.github.io/liga/)

## 🛠️ Arquitetura do Projeto
O sistema foi desenvolvido focado em **velocidade de resposta** e **clareza visual**:

* **Gerenciamento de Estado Simples:** Uso de objetos literais em JavaScript para mapear membros e links, permitindo atualizações de escalação em segundos.
* **Interface de Abas (Tabs UI):** Alternância instantânea entre clãs sem recarregamento de página, utilizando manipulação de DOM.
* **Design de Impacto:** Tipografia robusta (Montserrat) e esquema de cores de alta fidelidade para transmitir a importância da convocação.
* **Deep Linking:** Botões de ação direta que abrem o perfil do clã diretamente dentro do jogo Clash of Clans.

## 📋 Funcionalidades
- [x] Alternância entre Escalação Principal e Clã 3.
- [x] Numeração automática dos convocados.
- [x] Alerta visual para jogadores não apresentados.
- [x] Layout 100% responsivo para dispositivos móveis.

## 🧠 Conceitos de ADS Aplicados
* **Iteração de Arrays:** Uso do método `.map()` para renderizar componentes de interface de forma declarativa.
* **Event Handling:** Captura de cliques e propagação controlada para navegação suave.
* **Estilização Moderna:** Uso de `clamp()` para tipografia fluida e `sticky positioning` para menus.

---
*Escalação é destino. Preparem seus exércitos.*
