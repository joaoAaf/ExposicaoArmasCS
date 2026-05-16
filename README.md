# Meu Primeiro Ambiente VR

## Descrição Geral
Este projeto é uma experiência simples em Realidade Virtual desenvolvida na Unity com o Meta XR SDK. O ambiente virtual criado simula uma pequena exposição de armas clássicas do jogo Counter-Strike (AWP, M4 e Deagle), além de um easter egg característico (uma galinha), organizados de forma coerente para a livre navegação do usuário.

## Configuração Técnica
* **Engine:** Unity (Versão compatível com Meta SDK).
* **SDK:** Meta XR SDK devidamente instalado e configurado via XR Plugin Management.
* **Plataforma Alvo:** Android (Build Settings otimizados e preparados para o headset Meta Quest).
* **Movimentação:** O projeto utiliza o **Meta XR Simulator**, para realizar a movimentação inicial e os testes de navegação diretamente no PC (teclado e mouse), sem a necessidade obrigatória dos óculos VR durante esta fase de testes.

## Características do Ambiente
A cena foi montada cumprindo todos os requisitos estabelecidos:
* **Terreno e Limites:** Um piso plano texturizado para caminhada, cercado por paredes de pedra que delimitam a exposição.
* **Skybox:** Configurado adequadamente para exibir o céu e o ambiente ao redor, visível por cima das paredes.
* **Objetos 3D:**
  * Mostruários (criados com Prefabs), compostos por bases de concreto e cúpulas com material translúcido simulando vidro.
  * Armas em exposição: AWP, M4 e Deagle, utilizando texturas próprias dos modelos.
  * Modelo 3D de galinha posicionado livremente no cenário.

## Instruções de Uso
1. Instale o Unity versão 6.3 LTS (6000.3.13f1) com os módulos de *Android Build Support*.
2. Clone este repositório e abra a pasta do projeto através do Unity Hub.
3. Abra a cena principal localizada na sua pasta de cenas dentro de `Assets`.
4. Para simular a experiência no computador: acesse as ferramentas do Meta XR, inicie o **Meta XR Simulator** e clique em *Play* no editor.
5. Utilize os controles simulados na interface para interagir com a câmera, andar pelo cenário e visualizar os detalhes das armas nos mostruários.
