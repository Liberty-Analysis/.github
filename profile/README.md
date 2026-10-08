![Liberty Market Analytics](https://raw.githubusercontent.com/Liberty-Analysis/.github/main/profile/banner.png)

## Liberty Market Analytics

Mercados de previsão para o Brasil. Uma pergunta com prazo e fonte oficial; você compra cotas de
**Sim** ou **Não**. O preço de cada cota é a chance que o mercado dá ao resultado — e é também o
que você paga por ela. Entrada e saída por Pix, USDT e USDC.

[libertyanalysis.com](https://libertyanalysis.com)

### Os repositórios

| | |
|---|---|
| [**liberty-api**](https://github.com/Liberty-Analysis/liberty-api) | API em Go: domínio, ledger, workers, OpenAPI e cliente TypeScript gerado |
| [**liberty-mobile**](https://github.com/Liberty-Analysis/liberty-mobile) | App em Expo e React Native |
| [**liberty-web**](https://github.com/Liberty-Analysis/liberty-web) | A landing, em React e Vite |
| [**liberty-docs**](https://github.com/Liberty-Analysis/liberty-docs) | Arquitetura, decisões e o que elas custaram |

Repositórios independentes: cada um com seu git, seu CI e seu deploy. A única coisa que atravessa a
fronteira é o contrato HTTP da API e o cliente gerado a partir dele.

### Como isso funciona por baixo

Pix entra e sai por uma **instituição autorizada (PSAV)**, em relação direta com o usuário. A
unidade de conta é **USDC**, o dólar digital em que esses mercados são cotados no mundo. O registro
das transferências fica na **Polygon**. Preço e resolução vêm da **Polymarket**, pelo SDK público
da plataforma.

A Liberty Market Analytics é **prestadora de serviço de tecnologia**. Não é afiliada, parceira,
revendedora nem autorizada por Polymarket, Polygon Labs, Tether ou Circle, e não representa nenhuma
delas. Pagamentos, custódia, conversão e verificação de identidade são executados pela instituição
autorizada, em relação direta com o usuário. Marcas, nomes e logotipos citados pertencem a seus
respectivos titulares.

### Estado

Pré-lançamento. **Sem dinheiro real** até o licenciamento estar definido.
