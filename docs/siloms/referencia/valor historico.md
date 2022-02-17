!!! note ""
    SILOMS 11G: Gerenciar Plano de Requisição (PLJ0461P)


Requisições que atingiram o status de _mapa gerado_ e demais status posteriores podem ser utilizadas como referência na estimativa do preço de referência em requisições atuais.

Para pesquisar por tais requisições na tela *PLJ0461P*, deve-se:
* clicar em **Cancelar Filtro**
* clicar em **Definir Filtro**
* clicar em **Temporário** para abrir a tela de *Filtros Temporários*

Na aba *Status do Plano* escolher:
* *Autorizado*
* *Concluído Parcialmente*
* *Concluído*

Na aba *Status da Requisição" escolher:
* *Mapa Gerado*
* *Mapa Aprovado*
* *Empenho Gerado*
* *Empenho Aprovado*
* *Expedido na Unidade*
* *Recebida na Comissão*
* *Controle de Qualidade*
* *Expedida*
* *Embacado*
* **Volume no Solicitante*
* **Recebida Parcialmente no Solicitante*
* **Recebida no Solicitante*

Na aba *Órgão Provedor" escolher:
* *CELOG*
* *Outros*

Clicar em **Ocultar Filtros** ou **Salvar Filtros**. 

!!! note ""
    Ao se optar por **Salvar Filtros**, serão utilizados os parâmetros salvos sempre que a tela *PLJ0461P* for acessada.

Na aba *Planos de Requisição* atualizar os campos:
* *PN* com o *part number* de interesse iniciado por **DCN**
* *Extra?* para **Não**
* clicar em *Executar Consulta*

!!! note ""
    É possível realizar uma pesquisa para um conjunto de *DCNs* de interesse.

A delimitação do conjunto de *DCNs* de interesse é feita clicando-se sobre o campo *PN* e em seguida na tecla *F9*.
Os *DCNs* devem ser inseridos com uma separação de vírgula entre eles.
Uma vez que as requisições sejam listadas, clicar em *Todos*, para marcar as requisições, e no ícone da impressora (Listagem de Materiais).
Na aba *Opções* escolher *Arquivo Texto* e na aba *Tipos de Arquivo*, *CSV*.
O arquivo gerado pode ser aberto em planilhas eletrônicas, valendo observar que o separador de campos corresponde à vírgula.

Dois campos devem ser observados:
* data do plano da requisição (coluna P)
* valor unitário (coluna AC)

Uma alternativa para a correção desse valor histórico é aplicando-se o índice IGP-M, conforme:
* acessar o site *https://extra-ibre.fgv.br/autenticacao_produtos_licenciados/*
* clicar em *SÉRIES INSTITUCIONAIS*

Atualizar a aba *Atualização monetária de valor*, conforme:
* *Valor a ser corrigido*: valor unitário da requisição
* *Data inicial*: data do plano da requisição
* *Data final*: data atual
* *Índice para atualização*: IGP-M