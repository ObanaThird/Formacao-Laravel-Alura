# Controle de Séries

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

Sistema web para gerenciamento de séries de TV, permitindo que o usuário organize e acompanhe o progresso dos episódios assistidos.

Este projeto foi desenvolvido com o framework PHP **Laravel**, com base nos cursos da **Formação Laravel da Alura**.

---

## 📖 Índice

*   [✨ Funcionalidades](#-funcionalidades)
*   [🛠️ Tecnologias Utilizadas](#-tecnologias-utilizadas)
*   [🚀 Começando](#-começando)
    *   [Pré-requisitos](#pré-requisitos)
    *   [Instalação](#instalação)
*   [🧪 Rodando os Testes](#-rodando-os-testes)
*   [🤝 Contribuindo](#-contribuindo)
*   [📝 Licença](#-licença)

---

## ✨ Funcionalidades

*   **Autenticação de Usuários:** Sistema completo de login e registro.
*   **Gerenciamento de Séries (CRUD):**
    *   Adicionar novas séries à sua lista.
    *   Visualizar todas as séries cadastradas.
    *   Editar informações de uma série.
    *   Remover séries da lista.
*   **Controle de Temporadas e Episódios:**
    *   Adicionar temporadas e o número de episódios correspondente para cada série.
    *   Marcar episódios individualmente como assistidos.
    *   Visualizar o progresso de episódios assistidos por temporada.
*   **Interface Intuitiva:** Design simples e funcional para uma fácil navegação.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

-   **[Laravel](https://laravel.com/)**: Framework PHP para o desenvolvimento da aplicação.
-   **[PHP](https://www.php.net/)**: Linguagem de programação principal.
-   **[SQLite](https://www.sqlite.org/index.html)**: Banco de dados relacional embarcado.
-   **[Blade](https://laravel.com/docs/blade)**: Template engine do Laravel.
-   **[Bootstrap](https://getbootstrap.com/)**: Framework CSS para estilização da interface.
-   **[Composer](https://getcomposer.org/)**: Gerenciador de dependências para o PHP.

---

## 🚀 Começando

Siga estas instruções para obter uma cópia do projeto em funcionamento na sua máquina local para desenvolvimento e testes.

### Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em seu ambiente:

-   [PHP](https://www.php.net/downloads.php) (versão ^8.2 ou superior)
-   [Composer](https://getcomposer.org/download/)
-   A extensão PHP para SQLite (`php-sqlite3`)

### Instalação

1.  Clone o repositório para sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/controle-series.git
    cd controle-series
    ```

2.  Instale as dependências do PHP com o Composer:
    ```bash
    composer install
    ```

3.  Crie uma cópia do arquivo de ambiente e configure suas variáveis:
    ```bash
    cp .env.example .env
    ```

4.  Gere a chave de encriptação da aplicação:
    ```bash
    php artisan key:generate
    ```

5.  Crie o arquivo para o banco de dados SQLite:
    ```bash
    touch database/database.sqlite
    ```

6.  Execute as migrações para criar as tabelas do banco de dados:
    ```bash
    php artisan migrate
    ```

7.  Inicie o servidor de desenvolvimento local:
    ```bash
    php artisan serve
    ```

8.  Abra seu navegador e acesse `http://127.0.0.1:8000`.

---

## 🧪 Rodando os Testes

O Laravel fornece uma suíte de testes robusta. Para executar os testes automatizados deste projeto, utilize o seguinte comando:

```bash
php artisan test
```

---

## 🤝 Contribuindo

Contribuições são o que tornam a comunidade de código aberto um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1.  Faça um *Fork* do projeto.
2.  Crie uma *Branch* para sua modificação (`git checkout -b feature/FuncionalidadeIncrivel`).
3.  Faça o *Commit* de suas mudanças (`git commit -m 'Adiciona FuncionalidadeIncrivel'`).
4.  Faça o *Push* da *Branch* (`git push origin feature/FuncionalidadeIncrivel`).
5.  Abra um *Pull Request*.