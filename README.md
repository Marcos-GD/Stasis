# Stasis — Interactive Digital Control & Plane Mapping Tool

Stasis é um aplicativo desktop leve e de alta performance projetado para o estudo, visualização e simulação de sistemas de controle digital em tempo real. Desenvolvido com Tauri, React e Rust, o software permite o mapeamento interativo e simultâneo entre os planos complexos S (Analógico) e Z (Digital) através da manipulação dinâmica de polos e zeros.

## Funcionalidades Principais

* Mapeamento em Tempo Real: Arraste polos e zeros no Plano S e veja instantaneamente o impacto e o mapeamento correspondente no círculo unitário do Plano Z (\(z = e^{sT}\)).
* Gráficos Interativos: Suporte nativo a pan, zoom e interações fluidas do mouse para edição geométrica.
* Motor Matemático Robusto: Cálculos de estabilidade, funções de transferência e transições de domínio executados de forma ultraveloz no backend em Rust.
* Leve e Portável: Executável nativo para Windows sem o peso de navegadores embutidos, com inicialização instantânea.
