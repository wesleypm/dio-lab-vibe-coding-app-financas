# 💸 app PWA de finanças pessoais


```markdown

Título: PRD - App PWA Finanças Pessoais (FinanFlix) 

1. Contexto
Criar um aplicativo de organização de finanças pessoais que funcione por meio de conversas em linguagem natural, permitindo que o usuário controle gastos sem formulários complexos ou planilhas.

2. Objetivo
Facilitar o controle financeiro de forma simples, natural e inclusiva, reduzindo a fricção de entrada de dados e aumentando a adesão de usuários iniciantes.

3. Problema
Muitos usuários desistem de controlar seus gastos porque os apps atuais exigem entrada manual excessiva e oferecem pouca personalização. Falta uma experiência conversacional que recomende ações práticas de economia.

4. Público-alvo
Pessoas que querem começar a organizar suas finanças de forma prática, principalmente iniciantes. O produto deve seguir princípios de Design Universal para oferecer boa experiência ao maior número possível de usuários, incluindo diferentes idades, níveis de letramento digital e necessidades de acessibilidade.

5. Funcionalidades-chave
- Registrar gastos via chat em linguagem natural.
- Classificação automática das transações por categoria.
- Definir e acompanhar metas financeiras (ex.: metas mensais, metas por categoria).
- Agente Financeiro que envia dicas personalizadas de economia.
- Visualizar relatórios simples e personalizados (resumo, tendências, gráficos).
- Exportar relatórios em PDF.
- Interface inclusiva e acessível (contraste adequado, navegação simples, suporte a leitores de tela, textos legíveis).

6. Requisitos não funcionais
- Design Universal e acessibilidade como requisitos primários.
- Privacidade e segurança de dados (armazenamento criptografado, consentimento explícito).
- Latência de resposta do chat aceitável (< 2s para respostas locais; tolerância maior se depender de APIs externas).
- Suporte offline parcial para visualização de dados já sincronizados.

7. Entregável da IA (MVP)
- Plano de MVP com:
  - Principais telas: Chat conversacional; Dashboard resumido; Tela de metas; Tela de relatórios; Configurações de acessibilidade.
  - Recursos técnicos: Motor de NLP para entendimento de linguagem natural; Módulo de categorização automática; Motor de regras para metas e recomendações; Gerador de PDF.
  - Integrações: Serviços de autenticação; armazenamento seguro; APIs de pagamento/opcional para importação de transações.
  - Métricas de sucesso iniciais: taxa de registro de transações por usuário ativo; retenção 7/30 dias; taxa de correção manual de categorias.
  - Plano de validação inicial: teste com grupo de 20–50 usuários iniciantes e com perfis diversos; coleta de feedback qualitativo sobre usabilidade e acessibilidade.

8. Critérios de aceitação do MVP
- Usuário consegue registrar uma transação via chat em linguagem natural sem instruções adicionais.
- Sistema classifica automaticamente ≥ 80% das transações corretamente (ou oferece sugestão fácil de corrigir).
- Usuário consegue criar e visualizar uma meta e ver progresso.
- Relatório PDF gerado com resumo e gráficos básicos.
- Avaliação de acessibilidade: checklist de Design Universal atendido em itens críticos (contraste, navegação, suporte a leitores de tela).

9. Riscos e mitigação
- Classificação incorreta de transações: mitigação com correção manual simples e aprendizado incremental.
- Barreiras de adoção por baixa alfabetização digital: mitigação com linguagem simples, exemplos e onboarding guiado por conversa.
- Questões de privacidade: mitigação com transparência, consentimento e opções de exportação/exclusão de dados.

10. Próximos passos
- Prototipar fluxo de chat e dashboard com foco em Design Universal.
- Validar protótipo com usuários reais de perfis variados.
- Iterar com base em métricas e feedback.
```

## INTERAÇÕES COM LOVABLE (prompt PRD)

> 1 - Crie um app PWA de Finanças Pessoais com sabe no seguinte PRD: {PRD} 
> 2 - Poderia reorganizar a visualização, quero que o chat fique mais no canto e o dashboard fique como principal, faltou a opção gerar pdf, corrija utilize as cores do ITAU.


## PRINTS
Resultado final: Link do app teste criado: https://app-pwa-financas-pessoais.lovable.app

<img width="396" height="676" alt="image" src="https://github.com/user-attachments/assets/0ade1a07-2304-4c48-89a0-2a3c3efa9464" />
<img width="358" height="679" alt="image" src="https://github.com/user-attachments/assets/6346aeae-9d49-439f-afe8-3bb34deac8a7" />
<img width="364" height="664" alt="image" src="https://github.com/user-attachments/assets/daa07545-42a1-47d4-985f-b0b24cfff2d2" />


## RESUMO DO APP

Resumo do App de Finanças Pessoais em PWA
O aplicativo é uma solução de organização de finanças pessoais que funciona por meio de interações conversacionais. Ele permite que o usuário registre e acompanhe seus gastos de forma prática e acessível.

Principais funcionalidades
Dashboard: mostra o resumo do mês atual, incluindo saldo, receitas e despesas.

Chat: permite registrar transações em linguagem natural, sem formulários complexos.

Metas: possibilita definir e acompanhar objetivos financeiros.

Relatórios: gera relatórios simples e personalizados, com gráficos e resumos.

Diferenciais
Experiência baseada em conversa natural, tornando o controle financeiro mais intuitivo.

Classificação automática das transações por categoria.

Agente Financeiro que fornece dicas de economia personalizadas.

Exportação de relatórios em PDF.

Interface pensada com Design Universal, garantindo acessibilidade e boa experiência para o maior número possível de usuários.



## REFLEXÃO
  - O que funcionou bem?  
  O Refinamento até que funcionou bem, consegui finalizar praticamente o APP inteiro em 2 interações, porém o não foi realizado o back end, ficou sem login e B.D
  - O que não funcionou como o esperado?  
  As limitações do Lovable, no plano free limitam as interações, mas mesmo assim, são perfeitas para aprender mesmo assim.
  - O que aprendeu sobre conversar com IAs?
  Aprendi que é primordial saber estruturar um prompt para se ter um resultado bem próximo do que se espera já de cara, sem precisar ficar ajustanto no start com Vibe Coding.



## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
