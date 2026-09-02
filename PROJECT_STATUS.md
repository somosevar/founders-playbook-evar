# EVAr — Manual dos Fundadores — Project Status

<!-- EVAR_PROJECT_STATUS: OPERATIONAL -->

Atualizado em 2026-09-02.

## Estado operacional

- Branch de verdade: `main`.
- Estado canônico: `OPERATIONAL`.
- O Manual dos Fundadores está publicado por GitHub Pages.
- A governança de status está adotando o padrão corporativo `EVAr Project Status Sync`.

## Escopo deste estado

`OPERATIONAL` significa que o conteúdo publicado está disponível. Não significa, por si só, ausência absoluta de dívida técnica, revisão editorial definitiva, certificação de segurança ou autorização para mudanças de publicação sem os gates aplicáveis.

## Governança obrigatória

Qualquer mudança que altere estágio, readiness, gate, bloqueio, condição de publicação ou conclusão deve atualizar este arquivo e `README.md` no mesmo Pull Request.

Os dois arquivos devem manter exatamente o mesmo marcador `EVAR_PROJECT_STATUS`.

O workflow `EVAr Project Status Sync` deve validar essa sincronização em Pull Requests destinados à `main` e em pushes na `main`.

## Evidência e restrições

- CI verde isoladamente não autoriza elevar o estado do projeto.
- Nenhum status deve ser elevado além da evidência disponível.
- Credenciais, secrets, integrações e configurações de publicação não devem ser alteradas por uma mudança exclusivamente documental de status.

## Próxima ação de governança

Homologar o workflow `project-status-sync`. Somente após execução bem-sucedida e evidência do check ele deverá ser configurado como required status check da `main`.
