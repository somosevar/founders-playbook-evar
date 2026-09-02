# EVAr — Manual dos Fundadores

<!-- EVAR_PROJECT_STATUS: OPERATIONAL -->

Manual prático para fundadores da EVAr, publicado pelo repositório `somosevar/founders-playbook-evar`.

## Estado atual

**OPERATIONAL** — o conteúdo está publicado e acessível. O estado detalhado, as evidências e as restrições de governança são registrados em `PROJECT_STATUS.md`.

Mudanças que alterem estágio, readiness, gate, bloqueio, condição de publicação ou conclusão do projeto devem atualizar `README.md` e `PROJECT_STATUS.md` no mesmo Pull Request, conforme a Política de Sincronização do Status dos Projetos da EVAr.

## Estrutura e publicação

O conteúdo público é disponibilizado por meio do arquivo `index.html` e publicado com GitHub Pages.

## Governança

O check `project-status-sync` valida que `README.md` e `PROJECT_STATUS.md` possuem o mesmo marcador `EVAR_PROJECT_STATUS` e que alterações de status permaneçam sincronizadas.

A existência de CI verde isoladamente não autoriza elevar o estado operacional ou declarar novos gates concluídos sem evidência correspondente.
