ESTRUTURA DO BOT PATITO

src/
├── index.ts
├── config.ts
├── types/
│   ├── command.ts
│   ├── button.ts
│   ├── modal.ts
│   ├── selectMenu.ts
│   ├── ticket.ts
│   ├── warning.ts
│   ├── case.ts
│   ├── giveaway.ts
│   ├── reminder.ts
│   └── serverSettings.ts
├── commands/ (289 comandos em 16 categorias)
├── events/ (29 arquivos)
├── handlers/ (8 arquivos)
├── services/ (21 arquivos)
├── interactions/
│   ├── buttons/ (5 arquivos)
│   ├── modals/ (4 arquivos)
│   └── selectMenus/ (5 arquivos)
├── database/
│   ├── database.ts
│   ├── jsonDatabase.ts
│   ├── dataValidator.ts
│   ├── migration.ts
│   ├── backup.ts
│   └── repositories/ (9 arquivos)
├── utils/ (16 arquivos)
├── config/ (9 arquivos)
├── jobs/ (6 arquivos)
└── middlewares/ (6 arquivos)

data/
├── warnings.json
├── mutes.json
├── bans.json
├── kicks.json
├── cases.json
├── tickets.json
├── settings.json
├── autoroles.json
├── automod.json
├── giveaways.json
└── reminders.json

logs/
├── moderation.log
├── messages.log
├── members.log
├── voice.log
└── errors.log

backups/
└── (arquivos de backup)

Root:
├── README.md
├── package.json
├── package-lock.json
├── tsconfig.json
├── config.example.env
└── deploy-commands.ts