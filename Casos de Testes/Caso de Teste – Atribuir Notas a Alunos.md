## Caso de Teste – Atribuir Notas a Alunos
**ID:** CT-ST2-001  
**História de Usuário Relacionada:** ST2 – Como professor, eu gostaria de atribuir notas aos alunos das minhas disciplinas.  

**Pré-condições:**  
- O professor deve estar autenticado no sistema.  
- O professor deve ter turmas/disciplina vinculada no sistema.  

**Passos do Teste:**  
1. Acessar o sistema acadêmico com login válido.  
2. Selecionar a disciplina/turma cadastrada.  
3. Inserir notas válidas para os alunos.  
4. Salvar os registros.  

**Resultado Esperado:**  
- O sistema salva corretamente as notas atribuídas.  
- Os alunos visualizam suas notas no portal acadêmico.  

**Cenários Alternativos:**  
- ❌ Inserção de nota fora do intervalo permitido (ex.: maior que 10) → o sistema bloqueia e exibe alerta.  
- ❌ Professor sem vínculo em disciplina → sistema não exibe lista de alunos.  
- ✅ Possibilidade de editar notas dentro do prazo → sistema registra alteração e histórico.  
