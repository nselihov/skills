# Skills

Мои skills для продуктового дизайна. Работают в Claude Code и других AI-агентах.

## Установка

```bash
npx skills@latest add nselihov/skills
```

Или вручную: скопируйте папку `skills/triz` в `~/.claude/skills/`.

## ТРИЗ — `triz`

ТРИЗ — теория решения изобретательских задач. Её придумал инженер Генрих Альтшуллер,
изучив тысячи изобретений.

Skill нужен для задач, где одно требование мешает другому. Например, в заявке не хватает
данных, а каждое новое поле снижает конверсию. Обычно такое решают компромиссом. ТРИЗ
ищет вариант, при котором выполняются оба требования.

Skill разбирает задачу по шагам ТРИЗ: формулирует противоречие, описывает идеальный
результат, ищет, что уже есть под рукой, и предлагает несколько решений. Ещё он умеет
оценить готовое решение по шкале от 0 до 10.

Примеры запросов:
- `/triz в заявке не хватает данных, но каждое новое поле снижает конверсию`
- как сделать уведомления заметными, но не раздражающими?
- клиенты звонят в поддержку узнать статус заявки, разбери по ТРИЗ

Skill написан на русском. Источники — в [references/sources.md](skills/triz/references/sources.md).

## English

Product design skills for Claude Code and other AI agents.

**triz** — TRIZ (Theory of Inventive Problem Solving, created by Genrich Altshuller)
for product and UX design. Use it when two requirements conflict and every obvious option
is a compromise. The skill states the contradiction, describes the ideal result, looks for
what is already available and suggests several solutions. Written in Russian, it answers
in the language of your request.

Install: `npx skills@latest add nselihov/skills`

## Лицензия

MIT
