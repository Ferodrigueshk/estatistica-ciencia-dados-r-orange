# 📊 Métodos de Amostragem - Parte 1

## 🎯 Amostragem

A amostragem é uma técnica essencial em estatística. De modo geral, ao coletar uma amostra, é fundamental garantir que ela seja **selecionada de maneira aleatória**.

> ❓ **Por quê?**
> Para assegurar que **cada membro da população tenha a mesma chance de ser escolhido**, reduzindo o viés e aumentando a confiabilidade das conclusões.

Existem dois tipos principais de amostragem:

- **Probabilísticas**: todos têm chance conhecida de serem escolhidos.
- **Não probabilísticas**: nem todos os elementos têm a mesma chance, o que pode gerar viés.

---

## 🔄 Amostragem Probabilística

Nesse tipo de amostragem, **cada indivíduo da população possui a mesma probabilidade de ser selecionado**. Isso garante **aleatoriedade** e permite realizar inferências mais justas e representativas sobre a população.

Principais métodos:

- Amostragem **aleatória simples**
- Amostragem **aleatória sistemática**
- Amostragem **estratificada (proporcional)**

---

## 📌 Amostragem Aleatória Simples

É quando cada elemento da população tem a **mesma probabilidade matemática** de ser incluído na amostra.

> 📐 **Exemplo:**
> Em uma população de 200 pessoas:
> `P = 1/200`
>
> Se quisermos selecionar 3 pessoas, precisamos garantir que **todas as combinações possíveis de 3 pessoas tenham a mesma chance** de serem escolhidas.

Esse método é geralmente realizado por sorteio ou software (como Excel, R ou Python).

---

## 🧭 Amostragem Aleatória Sistemática

Neste método, os elementos são escolhidos a partir de **intervalos fixos**, após a escolha aleatória do primeiro item.

> 🏢 **Exemplo:**
> Uma empresa quer saber se seus clientes aprovam a nova embalagem de um produto. Ela decide selecionar uma amostra de **10%** dos clientes usando a **metodologia sistemática**.

> ℹ️ **Cálculo e processo:**
>
> - `10% = 10/100 = 1/10`, ou seja, **1 a cada 10 clientes será selecionado**.
> - No Excel, você pode usar a fórmula: `=ALEATÓRIOENTRE(1;10)` para definir o primeiro cliente.
> - Depois, continue com:
>   `n`, `n+10`, `n+20`, `n+30`, ...

Esse método é prático e bastante utilizado em inspeções, controle de qualidade e auditorias.

---

## 🧩 Amostragem Aleatória Estratificada

É aplicada quando a população pode ser dividida em **subgrupos (estratos)** com características semelhantes, e deseja-se que **todos os grupos estejam proporcionalmente representados** na amostra.

> 🧮 A seleção de indivíduos deve seguir uma **proporção equivalente ao tamanho de cada estrato** em relação à população total.

> 📐 **Exemplo:**
> Em um condomínio, existem:
>
> - 15 famílias com **1 pessoa**
> - 50 famílias com **2 pessoas**
> - 20 famílias com **3 pessoas**
> - 55 famílias com **4 ou mais pessoas**

A amostra será de 30 famílias. Quantas de cada tipo devem ser selecionadas?

> ℹ️ **Cálculo proporcional:**
>
> - Total de famílias = 15 + 50 + 20 + 55 = **140**
> - 1 pessoa: `15/140 * 30 = 3`
> - 2 pessoas: `50/140 * 30 = 11`
> - 3 pessoas: `20/140 * 30 = 4`
> - 4 ou mais pessoas: `55/140 * 30 = 12`

**✅ Resultado final da amostra:**

- 3 famílias com 1 pessoa
- 11 famílias com 2 pessoas
