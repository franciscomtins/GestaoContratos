## Gestão de Contratos


### Objetivo:

Este projeto tem o objetivo de exercitar a identificação e criação de cenários de testes. O sistema simulará a gestão de contratos, possibilitando informar os contratantes e quais serviços foram contratados, realizar controle da data de execução do contrato e a situação financeira deste.  


### Escopo Previsto:

1. **Cadastro da Empresa:** Cadastro da empresa prestadora de serviços.
2. **Serviços:** Cadastro dos serviços prestados. 
3. **Cadastro de Clientes:** Cadastro dos clientes que contrataram os serviços
4. **Contrato de Serviços:** Registro dos contratos efetivados. 


### Features:

#### 1 - Cadastro da Empresa:
1. O sistema fará a gestão de apenas uma empresa prestadora de serviços.
2. A empresa terá em seu cadastro nome, celular, endereço e e-mail.
3. O telefone deverá conter máscara para informação do código de área e nove dígitos. 
4. No campo endereço serão informados o logradouro, número e cidade. 

#### 2 - Serviços:
1. Cada serviço terá um identificador único, descrição e status
2. O status dos serviços irá variar entre ativo e inativo.

#### 3 - Cadastro de Clientes:
1. Cada cliente terá um identificador único, nome, celular, endereço e e-mail.
2. O telefone deverá conter máscara para informação do código de área e nove dígitos. 
3. No campo endereço serão informados o logradouro, número e cidade. 
4. O cliente poderá realizar a contratação de mais de um contrato simultaneamente.
5. No cadastro do cliente, deve ser possível ver todos os contratos realiazados pelo mesmo. 

#### 4 - Contrato de Serviços:
1. Cada contrato terá um identificador único, data de contratação e de execução, observação e status.
2. A data de execução não poderá ser menor que a data de contratação.
3. O status do contrato varia entre Pendente e Realizado. 
4. Ao cadastrar um contrato, se a data de execução não for informada, o contrato deverá ter o status Pendente.
5. Ao informar a data de execução, no ato do cadastro ou em uma edição futura, o status do contrato deverá ter seu valor atribuído para Realizado. 




