## Para que serve
Se trata de uma forma de compartilhar código entre produtos sem a necessidade de estar no Asteroid ou ficar replicando em vários projetos um componente ou recurso. Assim mantendo sempre um padrão de código.

Será utilizado apenas em casos que temos no máximo 2 projetos usando algum componente igual. Caso mais produtos necessitem, será necessário jogar para o Asteroid.

<br>

## Como usar
No seu repositório que deseja adicionar:
```shell
git submodule add <URL-DO-GIT>
```

OBS: Quando você clona algum repositório que está usando o submodule, após o clone, basta rodar:
```shell
git submodule update --init --recursive
```
<br>

## Componentes e Módulos utilizando
Caso algum produto use algum módulo, atualizar aqui para sabermos quando necessário transferir para o Asteroid.

### Componente 1
- [ ] Vendas
- [x] CRM
- [ ] Relacionamento
- [ ] Cadastro
- [ ] Assitência Técnica
- [ ] Manutenção Preventiva
- [ ] Hub
- [ ] Contratos
