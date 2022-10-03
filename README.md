# leitor_bar_code

Leitor para Códigos de Barras

Ler / Armazenar / Consultar / Alterar

- Listagem de funcionalidades (BackEnd)

  - Leitura de barcode
  - Criação de um objeto atrelado ao numero do barcode
    - **_Atributos_**
    - Qual objeto
    - Localização
    - Utilizador
    - Imagem do Objeto
    - Config em caso de Computadores
  - Adicionar atributos a um barcode
  - Salvamento do objeto criado em um BD
  - Leitura e Pesquisa de um barcode
  - Edição de atributos do objeto

- FrontEnd
  - Site simples com opções de ações
  - Editar
    - Editar um objeto ja existente (Solicita a leitura do Barcode)
  - Criar
    - Completar os atributos e ler o barcode para utilizar como ID
  - Deletar
    - Solicita a leitura de Barcode para rastrear item e logo após deleta-lo
