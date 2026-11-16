# Entrega 04 — Itens 3 e 4: qualidade, testes e colaboração

> Evidências da Sprint 02. Atualizado em 16/11/2026. Este documento registra os testes executados, as validações funcionais e os pontos que ainda dependem de comprovação pela equipe.

## 3. Qualidade e testes

### Testes automatizados

O projeto contém 17 testes Django em `src/backend/demandas/tests.py`.

**Execução de 04/11/2026**

A execução local terminou com **17 testes aprovados**, sem falhas ou erros.

**Nova execução de 16/11/2026**

Os testes foram executados novamente após uma correção na configuração de armazenamento dos arquivos estáticos durante os testes automatizados.

Resultado:

- Verificação do Django: nenhum problema identificado.
- Testes encontrados: 17.
- Testes aprovados: 17.
- Falhas: 0.
- Erros: 0.
- Resultado final: `OK`.

Comandos utilizados, na pasta `src/backend`:

```powershell
python manage.py check
python manage.py test demandas --verbosity 2
```

As execuções ocorreram localmente, utilizando banco de dados temporário em memória. Esses resultados não representam uma execução de CI no GitHub.

### Cobertura relacionada à Sprint 02

Foram identificados testes relacionados a:

- Conclusão da fiscalização e bloqueio de alterações após a conclusão.
- Restrições de acesso e ações de homologação.
- Aprovação da fiscalização pela gerência.
- Acesso à geração do relatório técnico após a homologação.

**Observação:** os 17 testes abrangem funcionalidades anteriores e atuais do sistema. Não são 17 testes exclusivos da Entrega 04. A validação completa do conteúdo do relatório e do vínculo conceitual com o SEI foi realizada manualmente, não por testes automatizados específicos.

### Validações funcionais no navegador

As validações manuais da Sprint 02 foram registradas nos cartões do Trello.

| História | Validação registrada |
|---|---|
| US13 — Acompanhar o andamento da fiscalização | Início, andamento, checklist, evidências, conclusão e visualização pela gerência. |
| US14 — Gerar relatório técnico sanitário | Geração do relatório, conteúdo, confirmação e opção de impressão ou salvamento em PDF. |
| US15 — Visualizar gráficos e indicadores | Conferência funcional registrada pela equipe. |
| US16 — Homologar fiscalização | Homologação pela gerência, também observada durante a validação da US13. |
| US17 — Vincular relatório ao processo SEI | Registro do vínculo conceitual, confirmação com número do processo e alteração do status para Registrado. |

**Cartões de evidências:**

- [Testes automatizados e validação funcional — Entrega 04](https://trello.com/c/GwPY7Ugb/63/testes-automatizados-e-valida%C3%A7%C3%A3o-funcional-entrega-04)
- [US13 — Acompanhar o andamento da fiscalização](https://trello.com/c/31TqcHkJ/40-us13-acompanhar-o-andamento-da-fiscaliza%C3%A7%C3%A3o)
- [US14 — Gerar relatório técnico sanitário](https://trello.com/c/N4yFl8px/39-us14-gerar-relat%C3%B3rio-t%C3%A9cnico-sanit%C3%A1rio)
- [US15 — Visualizar gráficos e indicadores](https://trello.com/c/1euG3jZO/34-us15-visualizar-gr%C3%A1ficos-e-indicadores)
- [US16 — Homologar fiscalização](https://trello.com/c/1lt7Jh7a/43-us16-homologar-fiscaliza%C3%A7%C3%A3o)
- [US17 — Vincular relatório ao processo SEI](https://trello.com/c/nPArztwF/54/us17-vincular-relatorio-ao-processo-sei)

### Limitações conhecidas

- A geração do relatório é funcional no sistema, mas não envolve geração por inteligência artificial nem assinatura digital.
- O vínculo com o processo SEI é conceitual. Não existe integração real ou envio automático ao SEI.
- As evidências registradas no MVP não representam necessariamente o envio de arquivos fotográficos reais.
- Os testes automatizados não cobrem integralmente o conteúdo do relatório nem o fluxo de integração com o SEI.

### Issue / bug tracker

O projeto possui modelo de issue para registro de bugs em `.github/ISSUE_TEMPLATE/bug_report.md`.

Defeitos devem ser registrados somente quando reproduzidos, com passos, comportamento esperado e obtido, ambiente e evidências. Não registrar bugs fictícios.

## 4. Colaboração e evidências

### Programação em pares

As sessões de programação em pares e as contribuições individuais devem ser registradas somente após confirmação dos participantes.

| Par (nomes) | Data | História/tarefa | O que foi realizado | Evidência |
|---|---|---|---|---|
| A confirmar | A confirmar | A confirmar | A confirmar | A confirmar |

Não atribuir autoria ou participação sem comprovação.

### Evidências da Sprint 02

- [Quadro VISAT no Trello](https://trello.com/b/er7tMowp/visat)
- [Cartão de planejamento da Sprint 02](https://trello.com/c/eEpHPicB/61/sprint-02-planejamento-e-resultados)
- [Cartão de testes automatizados e validação funcional](https://trello.com/c/GwPY7Ugb/63/testes-automatizados-e-valida%C3%A7%C3%A3o-funcional-entrega-04)

O quadro Trello é privado. É necessário garantir que o professor tenha permissão para acessar os cartões e seus anexos.

### Revisão final

- [x] Executar `manage.py check`.
- [x] Executar os testes automatizados.
- [x] Registrar o resultado de 17 testes aprovados.
- [x] Anexar evidência da execução no Trello.
- [x] Registrar as validações funcionais realizadas.
- [x] Documentar as limitações conhecidas do MVP.
- [ ] Confirmar e documentar as sessões reais de programação em pares.
- [x] Revisar as evidências com a equipe.