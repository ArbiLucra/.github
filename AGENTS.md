# Instruções locais — repositório público ArbiLucra

Este arquivo é a fonte canônica de regras para agentes neste repositório. Leia o README e os arquivos afetados antes de editar. `CLAUDE.md` referencia estas regras; não mantenha uma cópia divergente.

## Responsabilidade

- Manter apresentação pública, perfil da organização e templates genéricos de colaboração.
- Usar ArbiLucra como marca. Escrever de modo claro, sem prometer retorno, produto disponível, clientes ou funcionalidades implementadas sem evidência.
- Este repositório é independente. As regras essenciais devem funcionar no clone isolado; não depender de caminhos para outros clones.
- Instruções deste repositório não são automaticamente regras locais de outros repositórios da organização.

## Fronteira pública

- Todo conteúdo deve ser apropriado à publicação: não incluir topologia, nomes de ambientes, inventário, links privados, detalhes de acesso, runbooks, prompts operacionais, incidentes sensíveis ou configuração interna.
- Não copiar documentos privados para cá sem revisar e reduzir o conteúdo ao necessário para o público.
- Não registrar credenciais, dados de clientes, saldos, endereços pessoais ou evidências de vulnerabilidade que exponham terceiros. Usar exemplos sintéticos.
- A etapa documental não autoriza implementação, workflows, publicação, push, mensagens externas, compras, provisionamento ou operação financeira.

## Colaboração e veracidade

- Preserve alterações existentes. Inspecione status, branch e remote antes de editar; não una repositórios nem inicialize a pasta pai.
- Não invente comandos de aplicação, testes, serviços, canais de suporte ou controles remotos. Templates de issue/PR não habilitam checks ou proteções.
- Não publique contato de segurança sem confirmação do responsável. Siga o estado real descrito em `SECURITY.md`.
- Não declare pesquisa de marca, registro, domínio ou exclusividade para ArbiLucra a partir de sua escolha como nome.

## Verificação e entrega

Não há aplicação, suíte de testes ou workflows implementados neste repositório. Para documentos e templates, revise conteúdo público, links relativos, placeholders e diff. `git status --short --branch`, `git remote -v`, `git diff --check` e `git diff` são comandos Git de inspeção; não verificam controles remotos. Leia arquivos novos e revise também o diff do índice antes de um commit autorizado.

Relate alterações e verificações realmente executadas, com pendências. Não alegue lint, testes, automação ou proteção ativa sem evidência. Respeite o escopo local da tarefa e a configuração Git existente; commit não implica autorização de push.
