# Casos de Teste – Sistema Acadêmico

## Caso de Teste – Matricular em Disciplina
**ID:** CT-ST1-001  
**História de Usuário Relacionada:** ST1 – Como aluno, eu gostaria de me matricular em uma determinada disciplina.  

**Pré-condições:**  
- O aluno deve estar autenticado no sistema.  
- A disciplina deve estar disponível para matrícula (com vagas abertas).  

**Passos do Teste:**  
1. Acessar o sistema acadêmico com login válido.  
2. Navegar até a seção **Matrícula**.  
3. Selecionar a disciplina disponível na lista.  
4. Confirmar a matrícula.  

**Resultado Esperado:**  
- O sistema confirma a matrícula e exibe mensagem de sucesso.  
- A disciplina passa a constar na grade do aluno.  
- O sistema impede duplicidade de matrícula na mesma disciplina.  

**Cenários Alternativos:**  
- ❌ Tentativa de matrícula em disciplina sem vagas → exibe mensagem “Disciplina lotada”.  
- ❌ Aluno não autenticado → bloqueia acesso e solicita login.  
- ✅ Cancelar matrícula → a disciplina é removida da grade.  
