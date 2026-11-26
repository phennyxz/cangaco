# AGENTS.md — CANGAÇO

## Contexto e fontes de verdade
Leia README.md, docs/design.md e docs/i18n.md antes de alterar o projeto. Consulte story/base/ para contexto narrativo. Distinga requisitos aprovados, propostas e questões em aberto. Em caso de conflito, solicite decisão do responsável; não transforme sugestões em requisitos.

## Autoria narrativa
- story/base/ é espaço autoral reservado. Não sobrescreva, traduza, complete ou reinterprete histórias sem solicitação explícita.
- Preserve textos originais em português brasileiro. Adaptações executáveis devem ficar separadas dos originais.
- Não invente cânone, personagens, localidades ou finais definitivos. Identifique conteúdo de teste como provisório.
- Preserve a identidade cultural do Agreste e a liberdade narrativa: conquista de poder não implica degradação moral obrigatória; vitória e sobrevivência são independentes.

## Arquitetura e escopo
- FPS individual Web 3D, mundo aberto compacto e persistente, missões em cenários delimitados e independentes.
- Separe engine FPS, mundo, missões, diálogos, narrativa, NPCs, estado, salvamento e assets.
- Prefira conteúdo declarativo, IDs estáveis e condições de progressão independentes de apresentação.
- Preserve o mínimo territorial definido em docs/design.md. Não fixe dimensões, stack gráfica ou regras numéricas ainda não aprovadas.
- Priorize desempenho mobile e desktop, carregamento sob demanda e descarte de recursos.
- Consulte a especificação vigente em https://github.com/phennyxz/covil-game-spec antes de implementar integração VLG. Não invente capacidades do host; respeite isolamento e contratos publicados.

## Internacionalização
- i18n desde a fundação: nenhum texto exibido hardcoded na lógica.
- pt-BR é o original e fallback; en e es são metas iniciais.
- Use chaves estáveis, UTF-8 e catálogos separados. Preserve termos culturais quando adequado.
- Mantenha IDs, regras e saves independentes do idioma. Teste fallback, interpolação e chaves ausentes.
- Não apresente traduções automáticas como revisadas pelo autor.

## Engenharia e segurança
- Trabalhe incrementalmente; preserve alterações existentes e evite refatorações fora do escopo.
- Não adicione dependências sem justificativa. Registre origem e licença de assets; não use material sem autorização.
- Não inclua credenciais, segredos ou dados pessoais. Valide conteúdo externo e não execute código narrativo arbitrário.
- Não altere infraestrutura, visibilidade do repositório ou faça deploy sem autorização.
- Documente decisões arquiteturais relevantes e mantenha documentação coerente com a implementação.

## Validação e entrega
- Inspecione o estado do repositório antes de editar.
- Execute os testes, lint e build disponíveis conforme o escopo. Se inexistentes ou indisponíveis, informe; nunca declare aprovação sem execução.
- Ao implementar gameplay, valide controles desktop/mobile, transições de missão, persistência, checkpoints e retomada conforme aplicável.
- Prefira commits pequenos e descritivos. Para mudanças substanciais, use branch e PR para revisão; não faça merge sem autorização.
- Informe arquivos alterados, testes e resultados, limitações, decisões assumidas e pendências.
- Não declare uma funcionalidade concluída quando houver apenas documentação ou protótipo.

## Estado inicial
O projeto está em concepção. Não há engine implementada nem comandos de build/teste estabelecidos. Atualize esta seção quando a fundação técnica existir.
