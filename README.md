# Мое Здравство Main

Главното Git repo на Мое Здравство.

Бидејќи немаме build system за компилација на Tailwind, користиме tailwind cli за мануелно да компајлираме views.

Моментално не користиме никаков framework додека да не се најде потреба, т.е. ако испадне пре комплексен кодот.

За templating исто така користиме std библиотека.

Stack:
- Go v1.20
- Tailwind (Compiled)
- HTMX
- AlpineJS

- Todo
- [ ] Додади GoFiber, templates се малку досадни за работа со stdlib net/templates, засреди FE, тргни се' живо од index.html
- [ ] Има ко 0 security features, пред golive детално да се провери се'
