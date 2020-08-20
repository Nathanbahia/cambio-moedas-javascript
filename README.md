# Dinheiro Agora

### Projeto desenvolvido usando apenas HTML, CSS, JS Vanilla.

Através do acesso a uma API pública do governo ([acesse aqui](https://economia.awesomeapi.com.br)), é possível obter os valores de variação de diversas moedas internacionais em relação ao real para períodos de no máximo 1 ano.

A requisição das informações é feita utilizando Axios:

```
axios.get(`https://economia.awesomeapi.com.br/json/daily/${moeda}-BRL/${dias}`)
```
 
Usando a API de geração de gráficos do Google, é exibido um gráfico demonstrando a variação da moeda dentro do período selecionado.

O projeto foi colocado em produção usando o serviços de deploy gratuito da Netlify e pode ser visto [aqui](https://005-portfolio-nathanbahia.netlify.app/).
