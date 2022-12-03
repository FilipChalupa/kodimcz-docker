# Kódím.cz docker

Docker pro spuštění vlastního vývojového serveru pro materiály na [Kódím.cz](https://kodim.cz/).

## Použití

Spusťte `docker run -it onset/kodimcz` uvnitř repozitáře s kurzem.

## Vývoj tohoto docker image

### Přichystání nové verze

1. Udělejte změny v kódu tohoto repozitáře.
1. Spusťte `npm version patch` (nebo místo `patch` například `minor`, `major`).
1. Spusťte `npm run release`.
