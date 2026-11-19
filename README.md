# A fÃ¡brica de vÃ­deo com agentes

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso 4 de 6 da **FormaÃ§Ã£o Cinema com IA** do INEMA.CLUB (conteÃºdo aberto e gratuito, formato INEMA Learning v7.2), em portuguÃªs, inglÃªs e espanhol.

- Curso: https://inematds.github.io/formacao-cinema-ia-fabrica-v72/ (EN: `/en/`, ES: `/es/`)
- PÃºblico: quem jÃ¡ usa Claude Code ou Codex no terminal.
- Oito aulas: o mapa da fÃ¡brica, explicavideos, demonstraÃ§Ã£o de app, docflow e refazvideo, shorts com portÃ£o de qualidade, editor de reels por agente, avatar e consentimento, publicaÃ§Ã£o no YouTube em ensaio.

## Kit

`kit/` traz os blocos testados das aulas (`kit/blocos/*.sh`), as saÃ­das capturadas em 19/10/2026 (`kit/saidas/`), os exemplos e quatro ferramentas: `qual-motor.py`, `conferir.py`, `conferir-consentimento.py` e `portao-avatar.sh`.

```bash
mkdir -p ~/projetos && cd ~/projetos
git clone https://github.com/inematds/formacao-cinema-ia-fabrica-v72.git
bash formacao-cinema-ia-fabrica-v72/kit/blocos/a1a-ambiente.sh
```

Cada bloco clona um motor pÃºblico do INEMA num commit fixo e para antes de qualquer passo que gaste crÃ©dito ou publique: nenhum avatar, nenhum vÃ­deo gerado por IA, nenhum envio.

## Gerar as pÃ¡ginas

ConteÃºdo em `conteudo/<lang>/`; `python3 gerar.py && python3 validar.py` (e `--lang en`, `--lang es`).

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>