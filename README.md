# 📦 Sistema de Estoque

Sistema de controle de estoque desenvolvido em **Python**, com interface de menu no terminal. Permite cadastrar produtos, controlar entradas e saídas, buscar itens e acompanhar o valor total do estoque, tudo com os dados salvos automaticamente em arquivo JSON.

## ✨ Funcionalidades

- ➕ **Adicionar produtos**: se o produto já existir, a quantidade é somada
- 📋 **Listar estoque** completo com preço unitário e subtotal
- 🗑️ **Remover produtos**
- 🔄 **Entrada e saída** de quantidade, com bloqueio de valores negativos
- 🔍 **Busca** por nome ou parte do nome
- 💰 **Relatório** com valor total do estoque
- ⚠️ **Alerta de estoque baixo** (5 unidades ou menos)
- 💾 **Persistência de dados** em `estoque.json`, sem perder nada ao fechar o programa
- ✅ **Validação de entradas**: aceita vírgula ou ponto nos preços e evita erros ao digitar letras onde se espera número

## 🛠️ Tecnologias

- Python 3.8+
- Bibliotecas padrão: `json`, `os`, `datetime` (nenhuma instalação extra)

## 🚀 Como executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/sistema-de-estoque.git

# Entre na pasta
cd sistema-de-estoque

# Execute o programa
python estoque.py
```

## 📖 Como usar

Ao iniciar, o menu principal é exibido:

```
===================================
      SISTEMA DE ESTOQUE PRO
===================================
1 - Adicionar produto
2 - Ver estoque completo
3 - Remover produto
4 - Entrada/saída de quantidade
5 - Buscar produto
6 - Relatório (valor total e estoque baixo)
7 - Sair
===================================
```

Exemplo de listagem:

```
PRODUTO             QTD       PREÇO UNIT.    SUBTOTAL
---------------------------------------------------------
Arroz               20        R$ 5.50        R$ 110.00
Feijão              3         R$ 8.90        R$ 26.70
---------------------------------------------------------
```

## 🗂️ Estrutura do projeto

```
sistema-de-estoque/
├── estoque.py      # Código principal
├── estoque.json    # Gerado automaticamente ao salvar dados
└── README.md
```

## 🧠 Conceitos aplicados

- Programação Orientada a Objetos (classe `Estoque`)
- Manipulação de arquivos JSON
- Tratamento de exceções e validação de entradas
- Organização do código em funções reutilizáveis

## 🔮 Melhorias futuras

- [ ] Exportar relatório para CSV/PDF
- [ ] Histórico de movimentações
- [ ] Categorias de produtos
- [ ] Interface gráfica (Tkinter) ou versão web
- [ ] Testes automatizados

## 📄 Licença

Distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais informações.

## 👤 Autor

Feito por Christopher Coly
GitHub: https://github.com/ChrisColy • LinkedIn: https://www.linkedin.com/in/christopher-coly-655413248


