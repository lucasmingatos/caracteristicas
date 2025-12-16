Conceitos Fundamentais de CSS

Este conteúdo faz parte dos meus estudos e revisões de CSS, com foco na compreensão de conceitos essenciais para a construção de layouts consistentes, responsivos e bem estruturados.

Os tópicos abordados servem como base para evoluir no uso do CSS de forma consciente e organizada.

Objetivo dos Estudos

Entender como o CSS decide qual regra aplicar

Aprender a usar corretamente unidades de medida

Compreender diferentes formas de trabalhar com cores

Reforçar conceitos importantes para responsividade

Herança, Especificidade e Cascata

No CSS, as regras seguem uma ordem de prioridade, que define qual estilo será aplicado quando há conflitos:

Ordem de prioridade (do menor para o maior):

Arquivo CSS externo (style.css)

CSS interno (<style>)

CSS inline (style="")

Esses conceitos ajudam a entender por que algumas regras sobrescrevem outras.

Unidades de Medida
Unidades Absolutas

Não sofrem alterações conforme o contexto:

px

pt

in

cm

mm

Unidades Relativas à Fonte

Muito utilizadas para responsividade:

em → baseada no elemento pai (pode se multiplicar em cascata)

rem → baseada no tamanho da fonte do elemento raiz (html)

Outras Unidades Relativas

% → relativo ao espaço disponível

ex → baseado na altura do caractere "x" (pouco confiável)

ch → largura de um caractere (útil em fontes monoespaçadas)

Unidades Baseadas no Viewport

Relacionadas ao espaço visível da tela:

vh → altura da viewport

vw → largura da viewport

vmin → menor valor entre altura e largura

vmax → maior valor entre altura e largura

Herança Forçada

inherit → força o elemento a herdar a propriedade do elemento pai (uso específico)

Trabalhando com Cores no CSS
Tipos de Definição de Cores

Nomes: cores com nome definido (red, blue, etc.)

Hexadecimal: #RRGGBB

RGB: rgb(0–255, 0–255, 0–255)

HSL: tonalidade, saturação e luminosidade em porcentagem

currentColor

Variável que reutiliza a cor do elemento pai, facilitando a padronização visual

Observações

Este material tem finalidade educacional, sendo parte do meu processo contínuo de aprendizado em CSS.

Conteúdo desenvolvido para estudo e reforço dos fundamentos de CSS.
