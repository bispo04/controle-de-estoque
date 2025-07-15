# 💊 Sistema de Gerenciamento de Remédios

Este projeto é um sistema simples em Python para cadastro, consulta, compra e exclusão de remédios. Ele simula o controle de estoque de uma farmácia ou drogaria, possibilitando manter informações sobre produtos armazenados.

## 🚀 Funcionalidades

✅ **Adicionar Remédio**

* Cadastra um novo remédio informando:

  * Nome
  * Princípio ativo
  * Código do produto
  * Quantidade em estoque
  * Setor onde está armazenado
  * Preço unitário

✅ **Listar Remédios**

* Exibe a lista de todos os remédios cadastrados com suas informações.

✅ **Buscar Remédio**

* Permite buscar detalhes de um remédio pelo código do produto.

✅ **Comprar Remédio**

* Realiza a compra de uma quantidade desejada de um remédio, descontando do estoque e mostrando o valor total da compra.

✅ **Excluir Remédio**

* Remove um remédio do sistema pelo código informado.

✅ **Menu Interativo**

* Sistema de menu para facilitar a navegação entre as opções.

---

## 🛠️ Como usar

1. Certifique-se de ter Python instalado (versão 3.x).
2. Baixe ou clone este repositório.
3. Execute o arquivo Python:

```bash
python nome_do_arquivo.py
```

4. Siga as instruções exibidas no terminal.

---

## 💻 Exemplo de uso

### Cadastro de Remédio

```
Digite o nome do remédio: Paracetamol
Digite o Pincipio ativo: Paracetamol
Digite o codigó do produto: 123
Digite a quantidade: 50
Digite o setor aonde fica armazenado o remédio: Prateleira A
Digite o preço: R$5.50
Remédio cadastrado com sucesso!
```

### Compra de Remédio

```
Digite o codigó do remédio: 123
Digite a quantidade que deseja comprar: 2
Total a pagar: R$ 11.00
Compra realizada com sucesso!

Quantidade restante de Paracetamol: 48
```

---

## 📂 Organização do Código

* **adicionar\_remedios()** → adiciona um novo remédio ao estoque.
* **listar\_remedios()** → lista todos os remédios cadastrados.
* **buscas\_remedios()** → busca informações detalhadas de um remédio pelo código.
* **comprar\_remedios()** → realiza a compra de remédios.
* **excluir\_remedios()** → exclui um remédio do cadastro.
* **menu()** → exibe o menu de opções e executa as funções correspondentes.

---

## 📌 Melhorias Futuras

* Persistência de dados em arquivo (CSV, JSON ou banco de dados).
* Validação de entradas do usuário.
* Interface gráfica (GUI).
* Relatórios de estoque.
* Implementação de permissões de acesso para diferentes tipos de usuários.

---

## 🤝 Contribuição

Sinta-se à vontade para contribuir enviando pull requests ou relatando problemas via Issues!

---

## 📝 Licença

Este projeto está sob licença MIT. Veja o arquivo LICENSE para mais detalhes.

---

Quer que eu ajuste para outro estilo (mais resumido ou detalhado)? Ou colocar seu nome ou dados no autor?
