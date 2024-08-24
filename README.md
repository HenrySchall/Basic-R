## Introdução
- Download R: https://cran.r-project.org/bin/windows/base/
- Comunidade: https://rpubs.com/
- Leitura: https://medium.com/@henrique.schall

> R é uma linguagem de programação de código aberto direcionada para a computação estatística, sendo amplamente utilizado em análise de dados. A linguagem foi criada por Ross Ihaka e Robert Gentleman na Universidade de Auckland, Nova Zelândia, no início dos anos 1990. Eles tinha como motivação o desejo de desenvolver uma linguagem de programação que fosse poderosa para análise estatística e ao mesmo tempo acessível e flexível, como uma alternativa gratuita à linguagem S

### Configuração R para uso no Visual Studio Code 

```r
#Rodar no terminal do R
install.packages("languageserver")
install.packages("httpgd")
```
```r
#Preferences (Open User Settings (JSON)
"editor.quickSuggestions.other": false
r.lsp.diagnostics": false
"r.plot.useHttpgd": true
```
#### Tipos de Dados

Qualitativos (atributos não numéricos).
- Nominais: Denominações (cores, gênero, raça, títulos…)
- Ordinais: atributos que podem ser classificados (Ex: classificação de filmes mais assistidos, grau de escolaridade, nível de satisfação…).

Quantitativos (atributos numéricas).
- Discreto: valores finitos ou enumeráveis (quantidade de pessoas numa sala, número de carros em um estacionamento…)
- Contínuo: infinitos valores possíveis num intervalo (renda, tempo, altura…).
