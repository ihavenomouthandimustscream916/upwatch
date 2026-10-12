# UpWatch

Система моніторингу доступності мережевих сервісів для малих організацій. UpWatch періодично перевіряє сервери, сайти та мережеві пристрої (ICMP / TCP / HTTP), автоматично відкриває інцидент у разі збою та надсилає сповіщення черговому інженеру.

Навчальний проєкт з дисципліни «Інженерія програмного забезпечення».

## Структура репозиторію

```
upwatch/
├── docs/        # проєктна документація (.docx)
├── .gitignore
└── README.md
```

## Документація

| Документ | Файл |
|---|---|
| Бріф проєкту | [docs/01_Project_Brief.docx](docs/01_Project_Brief.docx) |
| Проєктне бачення | [docs/02_Vision_Document.docx](docs/02_Vision_Document.docx) |
| Специфікація v0.1 | [docs/03_Specification_v0.1.docx](docs/03_Specification_v0.1.docx) |
| Склад команди | [docs/04_Team.docx](docs/04_Team.docx) |

## Стек (попередній)

Python 3.12 · Flask · SQLite (SQLAlchemy) · APScheduler · pytest · GitHub Actions