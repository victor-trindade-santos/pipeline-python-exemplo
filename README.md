
# 🚀 Pipeline com Python e GitHub Actions

Este repositório é um **exemplo didático** de como configurar uma pipeline simples 
usando **Python + pytest** no **GitHub Actions**.

A pipeline é executada sempre que alguém abre um **Pull Request** para a branch `develop`.  
Ela instala dependências, roda os testes e só permite o merge se todos os testes passarem ✅


## 📂 Estrutura do projeto

```

atividade-git-pipeline/
├── .github/
│   └── workflows/
│       └── ci.yml        # Arquivo que define a pipeline no GitHub Actions
├── tests/
│   └── test_main.py      # Teste de exemplo em Python
├── requirements.txt      # Dependências do projeto
└── README.md             # Documentação

````








## 📚 Referências

* [Documentação oficial do GitHub Actions](https://docs.github.com/actions)
* [Documentação do pytest](https://docs.pytest.org/)
* [Git - Livro Oficial](https://git-scm.com/book/pt-br/v2)


