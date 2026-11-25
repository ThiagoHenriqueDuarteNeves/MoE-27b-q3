# Experiência MoE — Q3

Criei a página **TerraIA — Nature na Modernidade IA Sustentável** para testar a capacidade de geração de uma landing page pelo modelo Inkling 2 Mini na faixa de quantização Q3.

O resultado é uma landing page conceitual responsiva sobre inteligência artificial e sustentabilidade, com HTML, CSS e JavaScript reunidos em um único arquivo. A página inclui animações de partículas em Canvas, contadores animados, gradientes, navegação por âncoras e um gráfico ilustrativo.

## Modelo usado no teste

O **Inkling 2 Mini** é um modelo multimodal de pesos abertos da Thinking Machines Lab, publicado sob a licença Apache 2.0. Ele recebe texto e imagens, gera texto e suporta até 1 milhão de tokens de contexto. A arquitetura *Mixture of Experts* (MoE) tem 26,4 bilhões de parâmetros no total e 3,4 bilhões ativos. Para cada token, o modelo executa as camadas intermediárias três vezes. [Ficha oficial do modelo](https://huggingface.co/thinkingmachines/Inkling-2-Mini)

Neste experimento, foi usada uma versão GGUF da faixa de quantização **Q3 (3 bits)**. A variante exata da quantização e o tamanho do arquivo não foram informados. [Distribuição GGUF da Unsloth](https://huggingface.co/unsloth/Inkling-2-Mini-GGUF)

## Comparação com Q4

O experimento anterior, com a quantização `UD-Q4_K_XL`, está em um repositório separado: [Experiencia-MoeE-27B](https://github.com/ThiagoHenriqueDuarteNeves/Experiencia-MoeE-27B).

O HTML deste teste foi preservado como recebido, sem correções de código ou de texto, para permitir a avaliação da saída original do modelo. Como os temas das páginas são diferentes, a comparação é qualitativa, não um benchmark controlado de quantização.

## Como visualizar

Baixe o arquivo [`index.html`](index.html) e abra-o no navegador. Não é necessário instalar dependências.

Os dados de impacto apresentados na página são ilustrativos, não oficiais.
