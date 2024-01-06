# MyMenu Back-End

## Executar localmente

Clone o repositório

```bash
  git clone https://github.com/team-codebits/my-menu-back-end.git
```

Instale as dependências

```bash
  composer install
```

Copie o arquivo .env.example
```bash
  cp .env.example .env
```

Gere a chave da aplicação
```bash
  php artisan key:generate
```

Execute o servidor

```bash
  php artisan serve
```

## Comandos GIT

Liste as branches
```bash
  git branch
```

Crie uma nova branch
```bash
  git branch <nome-da-branch>
```

Navegue para a outra branch
```bash
  git checkout <nome-da-branch>
```