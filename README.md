# Respostas Magazord

# Cenário 1

**documentação e materiais de apoio**

- Identificação da documentação: Requisitos e especificações técnicas de cada integração.

- Analise da documentação: analise detalhada das funções especificadas nos requisitos de cada integração e as especificações técnicas de cada uma das funções do sistema.

- Mapeamento de requisitos: com base na analise dos requisitos e nas especificações técnicas de cada função é possível avaliar quais os pontos de testes de cada rotina e cada integração.

- Utilização de ferramentas: Ferramentas disponibilizadas de acesso aos requisitos, de especificações técnicas e gerenciamento de testes.

**Abrangência dos testes**

- Funcionalidades: Todas as funcionalidades disponibilizadas ou as mais usadas e essenciais em caso de limite de tempo.

- Casos de uso: casos de sucesso em funções que tenham resultados bastante específicos, casos de falha em rotinas com grande abrangência e cenários de carga em testes de performance.

- Priorização dos testes: Essencialidade da função, quanto usado é a função e potencial de risco.

**Execução dos testes**

- Ambiente de teste: Ambiente de Qualidade.

- Dados de teste: dados aleatórios ou dados utilizados em problemas identificados anteriormente.

- Ferramentas de automação: Nenhuma

- Registro de resultados: planilhas com os testes realizados, seus dados principais e seus resultados organizados por integração.

# Cenário 2

**documentação e materiais de apoio**

- Identificação da documentação: Requisitos e especificações técnicas.

- Mapeamento de requisitos: é possível através analise dos requisitos de cada função da integração vai apontar quais os pontos de testes de cada função e rotina.

- Utilização de ferramentas: Ferramentas disponibilizadas de acesso aos requisitos, de especificações técnicas e gerenciamento de testes.

**Abrangência dos testes**

- Funcionalidades: Todas as funcionalidades disponibilizadas e entregues na integração.

- Priorização dos testes: Essencialidade da função e potencial de risco.

**Execução dos testes**

- Dados de teste: dados aleatórios ou dados utilizados em problemas identificados anteriormente.

- Ferramentas de automação: Nenhuma

- Registro de resultados: planilhas com os testes realizados, seus dados principais e seus resultados.

# Cenário 3

- **1º Hipotese** - O comando de alteração da situação do anuncio não esta sendo feito quando ocorre o esgotamento do estoque e o teste seria zerar o estoque de um anuncio da forma que ocorreria no caso de uma venda normal e verificar se gravou o log de envio da informação de estoque zerado.

- **2º Hipotese** - Ao zerar o estoque esta ocorrendo o comando para alterar a situação do anuncio mas o comando esta alterando para a situação errada e não esta gravando log e o teste seria zerar o estoque de um anuncio da forma que ocorreria no caso de uma venda normal e verificar a situação do anuncio.

# Cenario 4
**Campo Nome**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam letras.

- Validar obrigatoriedade do campo: na tela de inclusão/alteração, deixar e campo vazio e gravar, verificar se ocorreu bloqueio.

- Testar validação de campo em duplicidade (Caso seja feita feita essa validação, é mais provavel que seja feita pelo campo CPF): informar na tela de inclusão/alteração um mesmo nome que ja esta informado em outro registro, gravar e verificar se ocorreu bloqueio.

**Campo Email**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar validação de campo em duplicidade (Caso seja feita feita essa validação): informar na tela de inclusão/alteração um mesmo email que ja esta informado em outro registro, gravar e verificar se ocorreu bloqueio.

**Numero de telefone**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam numeros.

**Data de nascimento**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam numeros.

**Endereço - Rua**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam letras ou numeros.

**Endereço - Cidade**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam letras.

**Endereço - Estado**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam letras.

**Endereço - CEP**

- Testar se o campo esta sendo gravado: preencher o campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar se o campo pode ser alterado depois de gravado e se a alteração esta sendo gravada: selecionar um registro ja incluido e alterar, na tela de alteração mudar a informação do campo e gravar, depois visualizar se a informação foi gravada conforme informado.

- Testar limite de quantidade de caracteres: na tela de inclusão/alteração informar mais caracteres do que o especificado no requisito para o campo.

- Testar limite de tipo de caracteres: na tela de inclusão/alteração tentar informar caracteres que não sejam numeros.
