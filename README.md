caracter produto[30] 
real preco
inteiro estoque
real venda

escreva("Sistema de Vendas")
escreva("1 - Cadastrar Produto")
escreva("2 - Reajustar Preço")
escreva("3 - Cadastrar Venda")
escreva("0 - Sair")

inteiro opcao
leia(opcao)

enquanto(opcao != 0) faca
    se(opcao == 1){
        escreva("Digite o nome do Produto:")
        leia(produto[30])
        escreva("Digite o preço do Produto:")
        leia(preco)
        escreva("Digite a quantidade em estoque:")
        leia(estoque)
    } 
    senao{ 
    		se(opcao == 2){
    			escreva("Digite o nome do Produto:")
        		leia(produto[30])
       	 	escreva("Digite o novo preço:")
        		leia(preco)
    		}
    }
    se(opcao == 3){
        	escreva("Digite o valor da venda:")
        	leia(venda)
	}

	senao{
        escreva("Opção inválida. Tente novamente.")
    }

    escreva("Sistema de Vendas")
    escreva("1 - Cadastrar Produto")
    escreva("2 - Reajustar Preço")
    escreva("3 - Cadastrar Venda")
    escreva("0 - Sair")

    leia(opcao)
}

escreva("Programa encerrado.")


produto
real preco
inteiro estoque
real venda

escreva("Sistema de Vendas")
escreva("1 - Cadastrar Produto")
escreva("2 - Reajustar Preço")
escreva("3 - Cadastrar Venda")
escreva("0 - Sair")

inteiro opcao
leia(opcao)

enquanto(opcao != 0) faca{
    		se(opcao == 1) entao{
         		escreva("Digite o nome do Produto:")
       	 	leia(produto)
        		escreva("Digite o preço do Produto:")
        		leia(preco)
        		escreva("Digite a quantidade em estoque:")
        		leia(estoque)
    		}
}
    senao{
    		se(opcao == 2) entao{
        		escreva("Digite o nome do Produto:")
        		leia(produto)
        		escreva("Digite o novo preço:")
        		leia(preco)
    	}
  }
        
    senao{
    		se(opcao == 3) entao{
        		escreva("Digite o valor da venda:")
        		leia(venda)
    		}
    }
        
    senao{
        escreva("Opção inválida. Tente novamente.")
    }

    escreva("Sistema de Vendas")
    escreva("1 - Cadastrar Produto")
    escreva("2 - Reajustar Preço")
    escreva("3 - Cadastrar Venda")
    escreva("0 - Sair")

    leia(opcao)
}

escreva("Programa encerrado.")


	}
}
}

