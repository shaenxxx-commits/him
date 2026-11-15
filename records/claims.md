# records/claims.md

Реестр утверждений с claim_id. Append-only.
Используется для ссылок из `meta/transitions.md` и `PROVENANCE.md`.

Формат:

    C-NNN
    УТВЕРЖДЕНИЕ: <формулировка>
    ТИП: OBSERVATION | RESULT | INTERPRETATION
    СТАТУС: UNKNOWN | HYPOTHESIS | SUPPORTED | VERIFIED
    ИСТОЧНИК: <URL / документ / SHA>
    ПОДТВЕРЖДЕНИЯ: <список источников>
    ОПРОВЕРЖЕНИЯ: <список источников>
    СВЯЗАННЫЕ: <F-NNN, L-NNN, H-NNN>
    ДАТА: YYYY-MM-DD

---
