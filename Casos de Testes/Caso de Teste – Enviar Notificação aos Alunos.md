# Caso de Teste – Enviar Notificação aos Alunos
**ID:** CT-ST4-001  
**História de Usuário Relacionada:** ST4 – Como gestor, eu gostaria que o sistema enviasse notificações aos alunos sobre eventos acadêmicos.  

**Pré-condições:**  
- O gestor deve estar autenticado no sistema.  
- O sistema deve possuir lista de alunos cadastrados com e-mail válido.  

**Passos do Teste:**  
1. Acessar o sistema acadêmico com login de gestor.  
2. Navegar até a seção **Notificações**.  
3. Criar uma nova notificação informando título, descrição e data do evento.  
4. Enviar a notificação para a lista de alunos.  

**Resultado Esperado:**  
- O sistema envia a notificação para todos os alunos cadastrados.  
- Cada aluno recebe a mensagem no canal configurado (e-mail ou app).  

**Cenários Alternativos:**  
- ❌ Lista de alunos com e-mails inválidos → sistema informa falha parcial no envio.  
- ❌ Gestor não preenche campos obrigatórios → sistema exibe alerta e bloqueia envio.  
- ✅ Notificação segmentada (curso/turma) → alunos corretos recebem a mensagem.  


