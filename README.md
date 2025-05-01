# Projeto_CadastroEndereco
O projeto de formulário de cadastro de endereço consiste em demonstrar a utilização da linguagem JavaScript para consumo de API de endereço que está disponível no site ViaCEP. Todas as instruções, incluíndo o código Javascript necessário para o funcionamento desse recurso está disponível no mesmo site.



# Funcionalidades

Campos de cadastro: Os campos de cadastro são relacionados aos dados de endereço somente. No entanto, são os mesmos campos solicitados em qualquer website de e-commerce, por exemplo.
Consumo de API ViaCEP: Essa funcionalidade utiliza Javacript para consultar dados de endereço a partir do número de CEP informado.
Auto preenchimento: A partir do CEP digitado no formulário, os campos RUA, BAIRRO, CIDADE e ESTADO são preenchidos automaticamente. Caso o CEP Informado está incorreto, o formulário apresenta uma mensagem de erro.

## Como funciona
Consultando o CEP: A aplicação é simples. Consiste em o usuário digitar o CEP desejado. Ao mudar de campo, seja com o mouse, clicando em outro campo, seja pressionando a tecla TAB (utilizada para trocar de campo), o código Javascript é executado.


![site (1)](https://github.com/user-attachments/assets/ccc3f834-c1ca-444b-9fb3-6abbc43ec63a)




CEP inexistente: Ao digitar um CEP errado, o código irá disparar um método alert que irá mostrar uma caixa de diálogo com a mensagem de erro.

![erro](https://github.com/user-attachments/assets/8d6aec73-058c-4438-9e8e-2239b515e57e)

