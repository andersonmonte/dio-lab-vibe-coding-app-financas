# 💸 App de Finanças Pessoais do Anderson com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando o Lovable e o Copilot Web. A proposta é criar um aplicativo de organização financeira pessoal baseado em interações em linguagem natural.

---

## 📝 PRD Refinado no Copilot Web

```markdown
# PRD – App de Organização de Finanças Pessoais

## Contexto
Criar um aplicativo de organização financeira pessoal que funcione por meio de conversas em linguagem natural.
O objetivo é simplificar o controle de gastos, evitando formulários complexos e planilhas manuais.

## Problema
Usuários desistem de controlar suas finanças porque os apps atuais exigem muita entrada manual e oferecem pouca personalização.
A solução proposta é uma experiência conversacional com recomendações automáticas de economia.

## Público-Alvo
Pessoas que desejam começar a organizar suas finanças de forma prática e acessível, especialmente iniciantes sem experiência prévia em controle financeiro.

## Funcionalidades-Chave
1. Registro via chat: Inserir gastos em linguagem natural.
2. Classificação automática: Categorizar transações sem esforço manual.
3. Metas financeiras: Criar e acompanhar objetivos de economia.
4. Agente Financeiro: Receber dicas personalizadas de economia.
5. Relatórios simples: Visualizar insights claros e adaptados ao perfil do usuário.
6. Design universal: Garantir que o app seja acessível e ofereça boa experiência para o maior número possível de pessoas.
7. Acessibilidade digital: Implementar práticas específicas para apps conversacionais, incluindo:
   - Compatibilidade com leitores de tela.
   - Contraste adequado de cores.
   - Suporte multimodal (voz e texto).
   - Linguagem clara e inclusiva.
   - Feedback acessível (visual e sonoro).
   - Navegação por teclado.
   - Opções de personalização (tamanho de fonte, velocidade de leitura).

## Entregável da IA
Plano de MVP contendo:
- Principais telas (chat, metas, relatórios).
- Recursos necessários (NLP para linguagem natural, categorização automática, motor de recomendações).
- Esboço de validação inicial (testes com grupo piloto de usuários iniciantes).
- Linguagem acessível e tom educativo.
- Avaliação de usabilidade com foco em design universal e acessibilidade digital.
- Métricas de validação de acessibilidade.

## Métricas de Validação de Acessibilidade
- Taxa de sucesso com leitores de tela: Percentual de tarefas concluídas corretamente por usuários que dependem de leitores de tela.
- Teste de contraste: Verificação automática de cores segundo padrões WCAG (mínimo AA).
- Tempo médio de interação: Comparar tempo de execução de tarefas entre usuários com e sem deficiência.
- Erro de navegação: Quantidade de cliques ou comandos incorretos durante o uso por teclado ou voz.
- Feedback dos usuários: Coleta de percepções qualitativas sobre clareza da linguagem e facilidade de uso.
- Taxa de personalização: Percentual de usuários que ajustam configurações de acessibilidade (fonte, contraste, velocidade).
- Inclusão em testes: Garantir que pelo menos 20% dos participantes dos testes de usabilidade sejam pessoas com deficiência.
```

---

## 🗨️ Interações com o Lovable

Prompts utilizados:
- Crie um App de Finanças Pessoais com base no seguinte PRD (Product Requirements Document): {PRD}
- O menu lateral está disponível apenas na tela "Conversas". Por favor, disponibilize o menu lateral também para as telas "Metas", "Relatórios" e "Acessibilidade".
- A aplicação está criando uma nova conversa toda vez que a tela "Conversas" é carregada. Por favor, conserte esse bug, pois uma nova conversa só deve ser criada quando não existir nenhuma ainda para o usuário. Além disso, adicione a opção de editar o título da conversa, ao lado da opção de excluir, que já existe.
- Por favor, salve o título da conversa após a edição, de modo que o título não seja substituído pelo texto dos prompts posteriores.
- Após salvar o novo título da conversa, e navegar para outra tela qualquer, ao voltar para a tela "Conversas", o título da conversa recém-editada volta a ser "Sem Título". Por favor, conserte esse bug.

---

## 🎯 Resultado final no Lovable:  
[https://bento-assistente-financas.lovable.app/](https://bento-assistente-financas.lovable.app/)

<img width="1916" height="916" alt="image" src="https://github.com/user-attachments/assets/2c80f9fd-a88f-4041-ac26-ff9c3554ce53" />

---

## 🔍 Funcionalidades do App de Finanças Pessoais

### Chat de registro
Permite inserir gastos, receitas ou metas diretamente em linguagem natural.  
Exemplo: "Gastei 45 no mercado ontem".

### Classificação automática
As transações são categorizadas automaticamente (ex.: mercado, transporte, lazer).

### Metas financeiras
O usuário pode definir objetivos como "Quero juntar 500 reais até o fim do mês" e acompanhar o progresso.

### Relatórios personalizados
Geração de resumos simples e visuais dos gastos e ganhos, adaptados ao perfil do usuário.

### Agente Financeiro
Assistente integrado que oferece dicas de economia e recomendações práticas.

### Design universal
Interface pensada para ser intuitiva e inclusiva, garantindo boa experiência para diferentes perfis de usuários.

### Acessibilidade digital
Práticas específicas para apps conversacionais:
- Compatibilidade com leitores de tela
- Contraste adequado de cores
- Suporte multimodal (voz e texto)
- Linguagem clara e inclusiva
- Feedback acessível (visual e sonoro)
- Navegação por teclado
- Opções de personalização (tamanho de fonte, contraste, velocidade)

---

## 🧠 Reflexão

### O que funcionou bem?
O refinamento do PRD, feito previamente no Copilot, ajudou a criar, no Lovable, um MVP bastante organizado e funcional. Isso permitiu concentrar esforços no ajuste e refinamento das funcionalidades básicas implementadas, através dos prompts subsequentes.

### O que não funcionou como o esperado?
Esperava poder interagir mais vezes gratuitamente com o Lovable, dado que ainda existem alguns bugs de navegação a serem consertados. Entretanto, a experiência foi muito útil para aprender mais sobre Vibe Coding. Além disso, posso aguardar a recarga diária dos créditos grátis do Lovable e tentar novas interações para consertar os bugs pendentes.

### O que aprendeu sobre conversar com IAs?
Aprendi que é semelhante a conversar com uma pessoa, ou no caso do Lovable, com um desenvolvedor. Quanto mais detalhes e clareza você der, melhor será a interação, e melhores serão os produtos desenvolvidos.
