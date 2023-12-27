# processos-seletivos-01: Meu template de back-end Driven

- Nesta atividade, vocês devem criar um projeto template de back-end com todas as configurações descritas no compilado da aula. Posteriormente complementaremos com as configurações de testes, lint, etc.
- Este projeto base deve conter: Prisma, TypeScript



- Da mesma forma como validamos os cenários onde tudo acontece como previsto, devemos validar os cenários onde as coisas não andam exatamente como gostaríamos.
- No código abaixo existe um cenário onde a service lança um 404 quando o usuário não é encontrado com a propriedade `licenseId`.
- ➡️ Implemente os testes do arquivo `unit/infractions.test.ts` usando o `spyOn` para mockar os respectivos comportamentos dos repositórios.
    - A implementação já possui alguns testes de integração para que você possa entender a regra de negócio básica.