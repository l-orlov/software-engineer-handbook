# software-engineer-handbook

Конспекты для подготовки к техническим собеседованиям Senior Backend (Go).

Формат карточки: **Вопрос → короткий ответ → что важно сказать на Senior-уровне → follow-up**.

## Контекст

Собес: Senior Backend (Go), Pasul LTD — реферальная программа, крипто-выплаты,
Postgres/YDB, Kafka/NATS. Готовимся спринтом на 4 дня, приоритет — темы,
реально релевантные этой вакансии, без деталей ради деталей.

## Roadmap / чеклист

- [x] День 1 (пт) — каркас репо + Go: concurrency
- [x] День 2 (сб) — PostgreSQL + Algorithms
- [x] День 3 (вс) — System Design (реферальная программа, идемпотентность, крипто-выплаты) + Kafka/NATS/Redis обзорно
- [ ] День 4 (пн) — Mock interview вслух + cheat-sheet + добивание пробелов
- [ ] Вт утром — только cheat-sheet

## Структура

```
docs/
  01-go/            concurrency.md, memory-and-types.md, questions.md
  02-postgresql/    indexes-and-planner.md, transactions-and-mvcc.md, questions.md
  03-algorithms/    data-structures.md, problems.md
  04-system-design/ referral-and-idempotency.md, payments-and-queues.md
  05-highload/      kafka-nats-redis.md
  mock-interview.md
  cheat-sheet.md
```

После собеса — при желании расширяем те же файлы вглубь, не переписывая структуру.
