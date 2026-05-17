# Tomaz Cantarelli Xavier — Currículo Online

## Produção

[https://tomazcx.github.io/ds881-curriculo-GRR20235618/](https://tomazcx.github.io/ds881-curriculo-GRR20235618/)

---

## Execução Local com Docker

### Pré-requisitos

- Docker e Docker Compose instalados

### Passo a passo

1. Clone o repositório:

   ```bash
   git clone https://github.com/tomazcx/ds881-curriculo-GRR20235618.git
   cd ds881-curriculo-GRR20235618
   ```

2. Suba o container:

   ```bash
   docker compose up --build
   ```

3. Acesse em [http://localhost:8080](http://localhost:8080)

4. Pare o container:

   ```bash
   docker compose down
   ```

---

## Proteção de Branch

A branch `main` está configurada com as seguintes regras:

| Regra | Descrição |
|---|---|
| **Require a pull request before merging** | Proíbe push direto na `main` |
| **Require status checks to pass before merging** | Exige CI verde para permitir merge |
| **Require branches to be up to date before merging** | Garante branch sincronizada com `main` |

### Evidência

> Adicione aqui o print de `Settings → Branches → Branch protection rules` comprovando a configuração.
