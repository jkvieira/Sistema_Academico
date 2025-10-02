## Caso de Teste – Visualizar Alunos Destaque
**ID:** CT-ST3-001  
**História de Usuário Relacionada:** ST3 – Como gestor, eu gostaria de visualizar os alunos considerados destaque acadêmico de todo o campus.  

**Pré-condições:**  
- O gestor deve estar autenticado no sistema.  
- O sistema deve ter alunos com média ≥ valor definido para destaque.  

**Passos do Teste:**  
1. Acessar o sistema acadêmico.  
2. Acessar a guia **Relatórios**.  
3. Preencher campo de busca com média ≥ valor definido.  

**Resultado Esperado:**  
- O sistema exibe os dados dos alunos com média ≥ valor definido.  
- O sistema oferece a opção de imprimir relatório.  

**Cenários Alternativos:**  
- ❌ Gestor sem permissão → sistema bloqueia acesso.  
- ❌ Relatório vazio (nenhum aluno com destaque) → sistema exibe mensagem adequada.  
- ✅ Relatório possui filtros adicionais (curso/período) → gestor consegue refinar dados.  
