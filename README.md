## Como adicionar os Botões da SOHTEC em seu Site.

Veja abaixo os passos necessários para inserir os botões da SOHTEC em seu site, e utilizar todos os recursos da nossa plataforma.

### 1º - Adicionar Biblioteca

Inserir entre as tags **HEAD** do site a chamada para o script da biblioteca da SOHTEC

Exemplo:
```html {.line-numbers}
<script src="https://sohtec.com.br/services/Scripts/ClientProd.js" type="text/javascript"></script>
```

<!--### 2º - Adicionar Botão (Área do Cliente)-->

<!--Adicione o código abaixo no lugar onde você deseja que o texto seja mostrado.</br>-->
<!--Obs: O **ID_DA_SUA_EMPRESA** é fornecido pela SOHTEC no momento do contrato.-->

<!--Exemplo:-->
<!--```html {.line-numbers}-->
<!--<script type="text/javascript">-->
<!--    SOH.Exec({       -->
<!--        "clienteId": "ID_DA_SUA_EMPRESA"-->
<!--    });-->
<!--</script>-->

<!--```-->

### 2º - Adicionar Botão (Agende sua Visita e Alugue Online)

Adicione o código abaixo no lugar onde você deseja que o botão seja mostrado.</br>
No lugar das variáveis substitua com os dados do imóvel que desejar. 

Obs: O **ID_DA_SUA_EMPRESA** é fornecido pela SOHTEC no momento do contrato.

Exemplo:
```html {.line-numbers}
<script type="text/javascript">
    SOH.Exec({
        "customHTML": "", //Opcional (Informe aqui o seu html customizado para o botão)
        "buttonColorBg": "blue",
        "clienteId": "ID_DA_SUA_EMPRESA",
        "imovelId": "",
        "imovelUrl": "", //Informe a URL Absoluta da imagem (Ex: http://www.seudominio.com.br/imagem.jpg)
        "imovelEndereco": "",
        "imovelNumero": "",
        "imovelComplemento": "",
        "imovelBairro": "",
        "imovelCidade": "",
        "imovelEstado": "",
        "imovelDormitorios": "",
        "imovelVagas": "",
        "imovelCep": "00000-000",
        "imovelAluguel": "0,00", //Separador decimal (,) padrão PT-BR
        "imovelCondominio": "0,00", //Separador decimal (,) padrão PT-BR
        "imovelIptu": "0,00", //Separador decimal (,) padrão PT-BR
        "visitaAcompanhada": "false",
        //"ModalidadeCredPago": "true", //Opcional (valores aceitos 'true' ou 'false')
        //"ModalidadeFianca": "true", //Opcional (valores aceitos 'true' ou 'false')
        //"ModalidadeFiador": "true", //Opcional (valores aceitos 'true' ou 'false')
        //"ModalidadeTituloCap": "true", //Opcional (valores aceitos 'true' ou 'false')
    });
</script>
```

**As cores de botões disponíveis são:**</br>
green</br>
blue</br>
write</br>
