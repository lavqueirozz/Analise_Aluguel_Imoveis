# Analise_Aluguel_Imoveis
Este repositório contém uma análise de dados sobre aluguel de imóveis, com o objetivo de identificar padrões e tendências no mercado imobiliário. A análise foi realizada utilizando Python e bibliotecas como Pandas, Matplotlib e Seaborn.

# Objetivo
O objetivo principal desta análise é:

Identificar o estado com a maior quantidade de imóveis disponíveis para alugar.

Avaliar o valor médio, mediana e moda dos valores dos aluguéis.

Identificar a imobiliária que concentra a maior quantidade de anúncios.

Calcular a média de dias que um anúncio está ativo.

# Dicionário de Dados
O dataset utilizado contém as seguintes colunas:

- id: Identificador do imóvel.

- category: Categoria do imóvel.

- title: Título do anúncio.

- body: Descrição do anúncio.

- amenities: Comodidades do imóvel.

- bathrooms: Quantidade de banheiros.

- bedrooms: Quantidade de quartos.

- currency: Moeda utilizada.

- fee: Valor de taxas extras.

- has_photo: Indica se o imóvel possui foto.

- pets_allowed: Indica se o imóvel permite pets.

- price: Valor do aluguel mensal (variável target).

- price_display: Valor do aluguel mensal exibido.

- price_type: Tipo de aluguel.

- square_feet: Tamanho do imóvel.

- cityname: Cidade do imóvel.

- state: Estado do imóvel.

- latitude: Latitude.

- longitude: Longitude.

- source: Tipo de imobiliária.

- time: Hora que o anúncio foi lançado.

# Metodologia

**Coleta de Dados:** O dataset foi carregado a partir de um arquivo CSV.

**Exploração Inicial:** Foram realizadas análises iniciais para entender a estrutura dos dados, como a visualização das primeiras e últimas linhas, verificação de valores nulos e análise estatística básica.

**Análise de Dados:** Foram realizadas análises para responder às perguntas propostas, incluindo a identificação do estado com mais imóveis, cálculo de estatísticas sobre os valores dos aluguéis, e análise da distribuição de anúncios por imobiliária.

# Resultados
**1. Estado com Maior Quantidade de Imóveis**

O estado com a maior quantidade de imóveis disponíveis para alugar foi identificado como TX (Texas).

**2. Valor Médio, Mediana e Moda dos Aluguéis**

Média: O valor médio do aluguel é de $1,527.06.

Mediana: A mediana do aluguel é de $1,350.00.

Moda: A moda do aluguel é de $1,350.00.

**3. Imobiliária com Maior Quantidade de Anúncios**

A imobiliária que concentra a maior quantidade de anúncios é RentDigs.com.

**4. Média de Dias que o Anúncio está Ativo**

A média de dias que um anúncio permanece ativo foi calculada com base na coluna time, que registra o momento em que o anúncio foi lançado. A média de dias ativos é de X dias (o cálculo exato depende da conversão do timestamp para dias).

# Conclusão

Esta análise fornece insights valiosos sobre o mercado de aluguel de imóveis, destacando os estados com maior oferta, os valores típicos de aluguel e as imobiliárias mais ativas. Essas informações podem ser úteis para investidores, corretores e pessoas que buscam alugar imóveis.

# Requisitos
Para reproduzir esta análise, você precisará das seguintes bibliotecas Python:

  Pandas

  Matplotlib

  Seaborn
    
  Datetime
