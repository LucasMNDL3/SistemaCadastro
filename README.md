1. Qual a finalidade de uma branch?
O Branch permite desenvolver funcionalidades sem afetar a versão principal do projeto. No caso, a main continua estável e os desenvolvimentos podem ser realizados de forma paralela sem afetar a versão principal.

2. Qual a diferença entre commit e merge?
O commit registra as alterações no histórico, dentro de uma branch. Já o merge, integra as alterações de uma branch a outra. Commit é registro e merge é integração. 

3. Por que é importante utilizar mensagens claras nos commits?
Porque garantem rastreabilidade: permitem entender o que foi feito, por quê e por quem, sem precisar ler o código. Facilitam localizar quando um problema foi introduzido e reverter a alteração certa.

4. Por que o controle de versão é importante em equipes?
Permite trabalho simultâneo sem sobrescrita, mantém histórico completo, viabiliza rollback e dá rastreabilidade das mudanças.

5. O que representa a versão 1.1.0?
Pelo versionamento semântico, o incremento do MINOR (de 1.0.0 para 1.1.0) indica uma nova funcionalidade compatível com a versão anterior — a opção de exclusão de usuário. Não houve quebra de compatibilidade, o que exigiria MAJOR.