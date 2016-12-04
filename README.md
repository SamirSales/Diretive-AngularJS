# Diretive
"São uma maneira poderosa de criar componentes auto-contidos e interativos. Ao contrário do jQuery que adiciona a interatividade como uma camada em cima do HTML, AngularJS trata a interatividade como um componente nativo do HTML."

## Diretive (appInfo.js)
Ensinamos um novo elemento ao browser (app-info) para usá-lo no ***index.html***.

código        |  finalidade
------------- | -------------
restrict: 'E' |  cria novo elemento para html
info: '='     |  a diretriz se atentará para o atributo ***info***
templateUrl   |  HTML bucará dados no ***scope.info*** no arquivo apontado pela URL.

## installApp.js
código        |  finalidade
------------- | -------------
app.directive | cria uma nova diretriz chamada ***installApp***
restrict: 'E' | cria novo elemento para html
scope: {}     | cria um escopo vazio
link          | cria função e variáveis que poderão ser linkados por outros arquivos.

## installApp.html
O arquivo segue os ***link***s criados pelo ***installApp.js***. No ***ng-click***, a função ***download()*** é utilizada, por exemplo.
