# CANGAÇO — Direção narrativa e implicações de gameplay

## Status e fontes
Este documento consolida decisões autorais posteriores à fundação e distingue propostas de implementação. O texto autoral em [story/base/README.md](../story/base/README.md) permanece intacto e é a referência principal dos acontecimentos. A premissa inicial anterior está superada quanto à morte de toda a família: Maria sobrevive. Complementa [design.md](design.md), sem alterar os demais requisitos.

## Decisões autorais estabelecidas
- Severino tem 16 anos, é nordestino do Agreste e franzino. Maria é sua irmã mais velha por 14 meses (aproximadamente 17 anos e 2 meses se ele acaba de completar 16). Datas de nascimento não definidas.
- O prólogo apresenta a vida familiar, a amizade com João e Jorge, a morte de Raimundo, a omissão policial, a pressão fundiária do coronel, a partida dos amigos e a invasão e incêndio do rancho. José e Ana morrem; Severino e Maria sobrevivem.
- Severino procura ajuda policial e é preso sob falsas acusações de matar os pais, incendiar a casa após suposta venda das terras e manter a irmã sob coerção e abuso. Maria, traumatizada, não fala e teme homens desconhecidos; a polícia a considera louca, o que não constitui diagnóstico.
- A campanha começa com Severino amarrado ao cavalo de um integrante de uma patrulha de três policiais, Maria caminhando atrás. A primeira missão é escapar mantendo Maria viva. O método de fuga e o destino da patrulha permanecem abertos.
- A sobrevivência e a proteção da irmã motivam inicialmente Severino. O ingresso no cangaço não é automático: a reputação decorrente das falsas acusações cria uma barreira importante, e ele precisa demonstrar que a história divulgada não corresponde à realidade.
- Maria evolui ao longo da campanha na direção dos possíveis finais. Pode voltar a ser uma moça radiante e sociável ou tornar-se uma mulher implacável que impõe sua vontade pela força. Não são classes rígidas nem uma dicotomia obrigatória.
- Maria funciona como leitura do eu profundo de Severino: os irmãos compartilham a experiência traumática, mas expressam sua vulnerabilidade de maneiras diferentes. A violência defensiva de Severino pode exteriorizar o medo que Maria manifesta de forma visível. Sua evolução torna perceptível a relação do protagonista com segurança, confiança e poder.
- A ascensão não exige degradação moral. Vitória e sobrevivência permanecem independentes; caminhos políticos, territoriais, de temor e apoio popular podem combinar-se.

## Direção narrativa
Maria é personagem com identidade e agência próprias, não mero medidor de moralidade. Sua recuperação emocional não equivale automaticamente à bondade, nem o trauma determina violência futura. O espelhamento é um recurso narrativo, não diagnóstico psicológico nem obrigação de concordar com o irmão. O contraste entre a voz alegre do prólogo e o silêncio inicial da campanha é central. A transformação pode mostrar se Severino encontrou segurança na confiança ou na capacidade de impor medo, inclusive quando dois jogadores alcançam objetivos externos semelhantes.

## Propostas de design a validar
### Ingresso no cangaço
Arco de sobrevivência, perseguição e reconstrução de credibilidade: primeiro contato, desconfiança, busca de testemunhos ou evidências, convivência, reconhecimento e possível aceitação. João, Jorge, familiares, vizinhos e feirantes são candidatos a testemunhas circunstanciais, não testemunhas inventadas do ataque. Seus destinos e participação futura dependem do autor. Não exigir absolvição universal. Reputações por grupo e município, rumores e versões divergentes são propostas; nenhuma pontuação ou limiar aprovado.

### Evolução de Maria
Representar mudanças gradualmente por fala, postura, iniciativa, vínculos, confiança, vestuário e decisões próprias. Estados intermediários são possíveis. Retorno da fala, cenas específicas, participação em missões, vestido como motivo recorrente e eventual liderança são propostas, não acontecimentos canônicos. Não reduzir Maria a acompanhante indefesa permanente. Evitar que sua evolução seja função exclusiva de contagem de mortes: considerar contexto, finalidade e consequências das decisões. Evitar barras visíveis de moralidade ou sanidade; interface ainda sujeita a validação.

### Gameplay e validação
- Prototipar primeiro controles FPS responsivos desktop/mobile, câmera, movimentação, interação, combate, feedback e desempenho Web 3D.
- Validar a primeira missão com objetivos legíveis, comportamento de Maria, proteção sem frustração artificial, checkpoints e retomada. Alternativas de fuga e resolução sem mortes são hipóteses, não requisitos fechados.
- Validar ciclo mundo explorável → missão delimitada → retorno com consequências persistentes; integrar narrativa e reputação sem bloquear arbitrariamente a exploração.
- Separar eventos narrativos, estado regional, evolução de personagens e apresentação; IDs estáveis, salvamento independente do idioma e conteúdo declarativo conforme design e i18n. Não definir fórmulas psicológicas ou stack adicional antes de prototipar.
- Testar se jogadores compreendem o contraste entre violência defensiva e domínio pelo medo sem depender de explicações ou placares; testar agência de Maria, coerência de consequências, diferentes trajetórias e ausência de associação automática entre trauma e crueldade.
- Tratar violência e trauma com sobriedade, sem exploração gráfica; classificação etária e apresentação final ainda precisam de revisão.

## Pendências
Datas de nascimento, intervalo entre incêndio e prisão, extensão jogável do prólogo, resolução da fuga, destinos dos amigos, provas e ingresso no bando, regras de reputação e evolução de Maria, finais específicos, validação histórica de moeda e costumes, classificação etária, controles e desempenho. Nenhuma mecânica aqui está implementada ou testada. A autoria de cenas, diálogos e acontecimentos futuros permanece com o responsável.
