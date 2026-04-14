# Estratégia Inicial de Testes – LocalEats

## 1. Funcionalidades
- Login
- Busca de restaurantes (filtro por tipo, localização e preço)
- Visualização de cardápio, fotos e avaliações
- Sistema de favoritos
- Recomendações personalizadas
- Avaliações e feedback

---

## 2. Níveis de Teste

### Funcionalidade: Login
- Unitário: validar senha e campos obrigatórios
- Integração: verificar comunicação com banco
- Sistema: usuário faz login completo
- Aceitação: usuário entra no sistema sem erro

### Funcionalidade: Busca de restaurantes
- Unitário: lógica dos filtros (tipo, preço, localização)
- Integração: conexão entre front-end + API + banco de dados
- Sistema: usuário busca e recebe resultados corretos
- Aceitação: usuário consegue encontrar restaurantes facilmente

### Funcionalidade: Visualização de cardápio e avaliações
- Unitário: carregamento de dados (cardápio, imagens, avaliações)
- Integração: API + banco + interface
- Sistema: usuário entra no restaurante e vê todas infos
- Aceitação: usuário entende as informações sem dificuldade

### Funcionalidade: Favoritos
- Unitário: salvar/remover favorito
- Integração: usuário + banco de dados
- Sistema: salvar e acessar lista de favoritos
- Aceitação: usuário consegue favoritar e acessar depois

### Funcionalidade: Recomendações
- Unitário: lógica de recomendação
- Integração: dados do usuário + sistema de recomendação
- Sistema: exibir recomendações personalizadas
- Aceitação: usuário recebe sugestões relevantes

---

## 3. Prioridades e Riscos

Alta prioridade:
- Login → sem login o usuário não usa o sistema
- Busca de restaurantes
- Visualização de informações
- Avaliações

Justificativa:
Se a busca falhar ou mostrar resultado errado, o sistema perde totalmente o sentido.
Se informações (cardápio, fotos) estiverem erradas ou lentas, prejudica a decisão do usuário.
Se avaliações sumirem, gera perda de confiança na plataforma.

Média prioridade: 
- Problemas de performance (lentidão em horários de pico)
- Falhas em mobile (impacta muitos usuários)


---

## 4. Pirâmide de Testes

- Maior foco: Maior foco em testes unitários, mais rápidos e baratos, ajudam a evitar bugs desde o início
- Médio foco: Quantidade média de testes de integração. Garantir que sistemas conversem corretamente
- Menor foco: Menos testes de sistema/E2E, mais caros e lentos

Justificativa:
Testes unitários pegam a maioria dos erros cedo.
Integração garante que API e banco funcionem juntos.
Testes completos são importantes, mas devem ser usados com mais cuidado por causa do custo.

---

## 5. Testes em Produção

- Uso de testes A/B e monitoramento de erros.
- AAplicar em novas funcionalidades, mudanças de interface e correções críticas

Justificativa:
Nem todos os problemas aparecem antes do lançamento, principalmente em diferentes dispositivos e com muitos usuários ao mesmo tempo. Os testes em produção ajudam a identificar erros reais mais rápido e corrigir antes de impactar todo mundo.