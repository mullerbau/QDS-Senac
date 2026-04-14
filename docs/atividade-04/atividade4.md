# 🧪 Aula 5 – Testes Funcionais vs Estruturais  
## LocalEats

---

## 👥 Integrantes do Grupo
- Eric Bauer 
- Derek Bezerra 
- Felipe Noguez  
- João Pedro da Silva Silva  

---

## 🎯 1. Funcionalidade escolhida

**Funcionalidade selecionada:**  
### Busca de restaurantes

**Descrição da funcionalidade:**  
Permite que o usuário busque restaurantes usando filtros como tipo de comida, localização e preço.

**O que o usuário espera:**  
Receber resultados corretos, rápidos e que correspondam com o que ele pesquisou.

---

## 🔍 2. Testes Caixa-Preta (Visão do Usuário)

**Quais testes vocês fariam sem conhecer o código?**

### 🔹 Cenários de teste

- Cenário 1:
Buscar por tipo de comida (ex: pizza) e receber restaurantes relacionados

- Cenário 2:
Buscar por localização e ver apenas restaurantes próximos
- Cenário 3:
Aplicar mais de um filtro (tipo + preço) e receber resultados corretos
- Cenário 4:
Buscar sem digitar nada e verificar comportamento do sistema

---

### 🔹 Possíveis erros identificados

-  Resultados incorretos
-  Filtros não funcionando
-  Lentidão ou travamento
-  Nenhum resultado quando deveria ter

---

## 🔧 3. Testes Caixa-Branca (Visão do Sistema)

**Como essa funcionalidade poderia estar implementada internamente?**

### 🔹 Lógica hipotética (pseudo-código ou descrição)

```pseudo
se tipo_comida != vazio:
    aplicar filtro por tipo

se localizacao != vazio:
    aplicar filtro por localização

se preco != vazio:
    aplicar filtro por preço

resultado = buscar no banco com filtros aplicados

se resultado vazio:
    retornar mensagem "nenhum resultado encontrado"

retornar resultado
```

### 🔹 Situações a serem testadas

- Situação 1: filtros aplicados individualmente
- Situação 2: combinação de filtros
- Situação 3: busca sem resultado

### 🔹 Possíveis erros identificados

-  Lógica de filtro incorreta
-  Erro na consulta ao banco
-  Falha ao tratar resultado vazio

## ⚖️ 4. Comparação entre as abordagens

Qual a principal diferença entre testar sem ver o código e com acesso ao código?

Sem ver o código, testamos como usuário. Com acesso ao código, testamos a lógica interna do sistema.

Que tipo de problema cada abordagem ajuda a encontrar?

Caixa-preta:
Erros visíveis para o usuário (resultado errado, lentidão, falhas na tela)
Caixa-branca:
Erros na lógica do sistema (condições erradas, validações incorretas, falhas internas)

## 💡 5. Reflexão no contexto do LocalEats

Qual abordagem parece mais importante neste momento do projeto?

Caixa-preta, pois os problemas atuais estão diretamente ligados ao uso do sistema (busca errada, telas confusas, etc).

Apenas uma abordagem seria suficiente? Por quê?

Não. A caixa-preta ajuda a identificar o problema, mas a caixa-branca é necessária para corrigir a causa no código.

## 🚀 Conclusão

