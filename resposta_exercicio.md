1. `git init`:
   - Descrição: Inicializa um novo repositório Git na pasta atual.
   - Exemplo:
     ```
     $ git init
     ```

2. `git config`:
   - Descrição: Configura opções do Git, como nome de usuário e email.
   - Exemplo:
     ```
     $ git config --global user.name "Seu Nome"
     $ git config --global user.email "seu-email@example.com"
     ```

3. `git status`:
   - Descrição: Mostra o estado atual do repositório Git, exibindo os arquivos modificados, adicionados ou removidos.
   - Exemplo:
     ```
     $ git status
     ```

4. `git add`:
   - Descrição: Adiciona arquivos ao índice do Git para serem incluídos no próximo commit.
   - Exemplo:
     ```
     $ git add arquivo.txt       # Adiciona um arquivo específico
     $ git add pasta/            # Adiciona uma pasta inteira
     $ git add .                 # Adiciona todos os arquivos e pastas modificados
     ```

5. `git commit`:
   - Descrição: Registra as mudanças feitas no repositório como uma nova revisão.
   - Exemplo:
     ```
     $ git commit -m "Mensagem de commit"
     ```

6. `git branch`:
   - Descrição: Lista, cria ou exclui branches (ramificações) no repositório.
   - Exemplo:
     ```
     $ git branch                    # Lista os branches existentes
     $ git branch novo-branch        # Cria um novo branch
     $ git branch -d nome-branch     # Exclui um branch
     ```

7. `git checkout`:
   - Descrição: Altera o branch atual ou restaura arquivos para um estado anterior.
   - Exemplo:
     ```
     $ git checkout nome-branch         # Altera para o branch especificado
     $ git checkout -b novo-branch      # Cria um novo branch e altera para ele
     $ git checkout HEAD~1 arquivo.txt  # Restaura um arquivo para o estado anterior
     ```

8. `git merge`:
   - Descrição: Combina as alterações de duas branches diferentes.
   - Exemplo:
     ```
     $ git checkout branch-destino      # Altera para o branch de destino
     $ git merge branch-fonte           # Combina as alterações do branch-fonte
     ```

9. `git remote`:
   - Descrição: Gerencia conexões remotas do repositório.
   - Exemplo:
     ```
     $ git remote add origin https://github.com/seu-usuario/seu-repositorio.git    # Adiciona um repositório remoto
     $ git remote -v                                                              # Lista os repositórios remotos configurados
     ```

10. `git push`:
    - Descrição: Envia as alterações locais para um repositório remoto.
    - Exemplo:
      ```
      $ git push origin nome-branch      # Envia as alterações do branch local para o repositório remoto
      ```

11. `git pull`:
    - Descrição: Obtém as alterações mais recentes de um repositório remoto e as mescla com o branch local.


    - Exemplo:
      ```
      $ git pull origin nome-branch      # Obtém e mescla as alterações do repositório remoto para o branch local
      ```

12. `git clone`:
    - Descrição: Cria uma cópia local de um repositório remoto.
    - Exemplo:
      ```
      $ git clone https://github.com/seu-usuario/seu-repositorio.git   # Clona um repositório remoto para o diretório local
      ```

13. `git reset`:
    - Descrição: Desfaz alterações, removendo commits ou desfazendo o estado dos arquivos para um commit específico.
    - Exemplo:
      ```
      $ git reset HEAD~1                # Desfaz o último commit, mantendo as alterações locais
      $ git reset --hard commit-hash    # Desfaz todos os commits até o commit especificado, descartando as alterações locais
      ```

14. `git log`:
    - Descrição: Exibe o histórico de commits do repositório.
    - Exemplo:
      ```
      $ git log                         # Exibe o histórico de commits
      ```

15. `git diff`:
    - Descrição: Mostra as diferenças entre diferentes versões dos arquivos.
    - Exemplo:
      ```
      $ git diff                        # Mostra as diferenças entre o último commit e o diretório de trabalho
      $ git diff commit-anterior        # Mostra as diferenças entre um commit específico e o diretório de trabalho
      ```