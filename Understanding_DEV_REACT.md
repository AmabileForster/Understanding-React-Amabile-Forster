## Anotações das aulas do curso Entra21 React

### Dicas de estudo
  
Aqui temos algumas dicas de coisas a se fazer e também a serem evitadas para melhora sua rotina de estudos. 

- Manter o foco, a determinação e a disciplina;
- Criar uma boa rotina de sono;
    - O sono é uma parte importante para o nosso dia a dia, se não tivermos uma boa rotina e não dormimos a quantidade necessária de horas, ou não ter um horario fixo para dormir e acordar, isso acaba deixando nosso corpo cansado e não temos energia para fazer as coisas necessárias para o dia a dia.
- Estudar todos os dias;
    - Precisamos estudar todos os dias, até mesmo durante viagens e finais de semana, para não perdemos o contato com o assunto que estamos aprendendo. Obviamente, nem todos os dias precisam ser horas e horas de estudos, mas também temos que ter a ciência de que se ontem eu estudei por 30 minutos, em algum outro dia eu preciso compensar o tempo faltante.
- Revisar aulas/conteudo antes de dormir;
    - Revisão antes de dormir é muito importante para as memórias a longo prazo, pois é durante o sono que memórias de curto prazo viram de longo prazo. Então tirar uns 30 a 40 minutos antes de dormir para revisar algum conteúdo importante, ou tópicos dos conteúdos.

### Git
  
Git é uma ferramenta de versionamento de código. Existem dois tipos de VCS (Version Control System) o centralizado e o distribuído.

<img src="/assets/images/Centralizado.png" height="250px">
<img src="/assets/images/Distribuído.png" height="250px">  
  
**Principais utilidades do git:**

- Controle de histórico (versionamento);
- Trabalho em equipe;
- Ramificação de projetos;
- Segurança;
- Organização;

### GitHub

Github é uma plataforma de hospedagem de arquivos com controle de versão através do uso do git. Usado principalmento por programadores para guardar códigos de projetos e também muito utilizado como um portifólio.

---

**Principais comandos git e o que fazem:**  
  
- `git init`;
    - Cria um repositório local.
- `git clone`;
    - Clona um repositório remoto.
- `git add [nome do arquivo]`;
    - Adiciona o arquivo nominado a staged area;
- `git add .`;
    - Adiciona todos os arquivos, novos ou modificados, a staged area.
- `git status`;
    - Verifica se tem arquivos não rastreados, modificados ou a serem comitados.
- `git commit`;
    - Comita os arquivos adicionados a stage area, pode ser usado `git commit -m "mensagem de commit"` ou `git commit -am "mensagem do commit` sendo o ultimo modelo uma opção que não precisa do comando `git add .`.
- `git push`;
    - Envia os arquivos comitados para o repositório remoto, também usado `git push origin main` `git push origin master`.
- `git pull`;
    - Atualiza o repositório local caso tenha sido enviado algum novo arquivo para o repositório remoto que não tenha no local.


---

**Criando e atualizando um repositório**

1. Criar um repositório no Github;
2. `git clone [link do repositório]` (no prompt de comando);

Após isso o repositório estará salvo na maquina para ser utilizado e modificado.

3. `git add .` ou `git add [nome do arquivo]`;
4. `git commit -m "comentário do commit"`;
5. `git push` ou `git push origin main` (master).