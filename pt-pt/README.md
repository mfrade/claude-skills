# 🇵🇹 pt-pt — Skill de Português Europeu para Claude

Um *skill* para o Claude que garante que **todas as respostas em português seguem a norma europeia (PT-PT)**, evitando completamente construções e vocabulário do português do Brasil (PT-BR).

---

## O que é um *skill* do Claude?

Os *skills* são ficheiros de instruções que o Claude carrega automaticamente quando são colocados na directoria `/mnt/skills/`. Funcionam como uma camada de contexto persistente que molda o comportamento do modelo em domínios específicos.

---

## O que faz este *skill*?

- ✅ Usa vocabulário PT-PT (`utilizador`, `ficheiro`, `telemóvel`, `autocarro`…)
- ✅ Usa a construção progressiva correcta (`estou a fazer`, nunca `estou fazendo`)
- ✅ Coloca pronomes clíticos na posição correcta (`disse-me`, nunca `me disse`)
- ✅ Usa `tu` como pronome informal (em vez de `você`)
- ✅ Aplica-se a texto corrido, listas, código comentado, e-mails, documentos e apresentações
- ✅ Responde sempre em PT-PT mesmo que o utilizador escreva em PT-BR

---

## Instalação

1. Copia o ficheiro `SKILL.md` para a directoria de *skills* do teu ambiente Claude:

```
/mnt/skills/user/pt-pt/SKILL.md
```

2. O Claude detecta e carrega o *skill* automaticamente sempre que comunicares em português.

Não é necessária qualquer configuração adicional.

---

## Exemplos

| Sem o skill (PT-BR) | Com o skill (PT-PT) |
|---|---|
| Estou fazendo o relatório | Estou a fazer o relatório |
| Me diz uma coisa | Diz-me uma coisa |
| Você pode me ajudar? | Podes ajudar-me? |
| Baixar o arquivo | Descarregar o ficheiro |
| Deletar o usuário | Apagar o utilizador |
| Aplicativo móvel | Aplicação móvel |

---

## Conteúdo do skill

O `SKILL.md` cobre:

- **Ortografia** — Acordo Ortográfico de 1990 aplicado à norma PT-PT
- **Vocabulário** — Tabela completa PT-PT vs PT-BR com ~40 entradas
- **Gerúndio progressivo** — Substituição sistemática por `estar a + infinitivo`
- **Colocação pronominal** — Ênclise por defeito, próclise com palavras atrativas
- **Pronomes e tratamento** — Uso de `tu` vs `você`, formas verbais com mesóclise
- **Preposições e contrações** — Regras de crase e contração em PT-PT
- **Números e datas** — Formatos PT-PT para datas, moeda e separadores
- **Registo e tom** — Adaptação contextual mantendo sempre a norma europeia
- **Lista de erros comuns** — Tabela de construções erradas e correctas

---

## Compatibilidade

Testado com **Claude Sonnet** e **Claude Opus** via:
- [Claude.ai](https://claude.ai) (interface web e móvel)
- API Anthropic com suporte a *skills* via sistema de ficheiros

---

## Contribuições

Contribuições são bem-vindas! Se encontrares um caso não coberto — vocabulário regional, termos técnicos, expressões idiomáticas — abre um *issue* ou submete um *pull request*.

Por favor, mantém todas as contribuições em PT-PT. 😄

---

## Licença

MIT — podes usar, modificar e redistribuir livremente.

---

*Feito com 🇵🇹 para todos os que querem um Claude que fale mesmo português.*
