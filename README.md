# Sistema de Gestão das Olimpíadas (SGO)
Repositório para modelagens do Sistema de Gestão das Olimpíadas (SGO). Abaixo seguem as histórias de usuário e visualização das modelagens.

## Histórias de usuário

### 1. Cadastro de Competições  
**Como um** administrador do sistema  
**Eu quero** cadastrar competições informando a modalidade, data, horário, local e atletas inscritos  
**Para que** o evento seja organizado e todas as competições sejam registradas corretamente  

#### Critérios de Aceitação:  
- O administrador deve fornecer o nome da modalidade, data, horário e local.  
- O sistema deve permitir a seleção dos atletas inscritos na competição.  
- O sistema deve validar se o local está disponível no horário informado antes de confirmar o cadastro.  

### 2. Inscrição de Atletas  
**Como um** atleta  
**Eu quero** me inscrever em competições específicas  
**Para que** eu possa participar das Olimpíadas representando meu país  

#### Critérios de Aceitação:  
- O atleta deve fornecer seus dados pessoais e indicar o país que representa.  
- O sistema deve garantir que o atleta não represente mais de um país por modalidade.  
- O sistema deve validar a disponibilidade de vagas na competição antes de confirmar a inscrição.  

### 3. Alocação de Locais para Competições  
**Como um** administrador do sistema  
**Eu quero** alocar locais para cada competição  
**Para que** não haja conflitos de horário e os eventos ocorram de maneira organizada  

#### Critérios de Aceitação:  
- O administrador deve selecionar a competição e o local desejado.  
- O sistema deve verificar se o local está disponível no horário desejado antes de confirmar a alocação.  
- O sistema deve impedir a alocação de dois eventos no mesmo local ao mesmo tempo.  

### 4. Registro de Resultados das Competições  
**Como um** juiz ou administrador  
**Eu quero** registrar os resultados das competições  
**Para que** os vencedores e classificados sejam armazenados corretamente no sistema  

#### Critérios de Aceitação:  
- O administrador deve selecionar a competição e registrar os três primeiros colocados.  
- O sistema deve atualizar automaticamente a contagem de medalhas dos países.  
- O sistema deve permitir a revisão e edição dos resultados antes da confirmação final.  

### 5. Geração de Relatórios de Medalhas  
**Como um** organizador do evento  
**Eu quero** visualizar relatórios de medalhas conquistadas por país  
**Para que** eu possa acompanhar o desempenho de cada nação nas Olimpíadas  

#### Critérios de Aceitação:  
- O sistema deve exibir um ranking de países com base na quantidade de medalhas de ouro, prata e bronze.  
- O relatório deve permitir filtragem por modalidade e período específico.  
- O sistema deve atualizar os dados automaticamente após o registro dos resultados. 

## Diagramas

### Diagrama de Casos de Uso
<img src="https://github.com/lucasgiovine/SGO-Projeto-de-Software/blob/main/Imagens/Use%20Case%20-%20SGO.png"/>

### Diagrama de Classes
<img src="https://github.com/lucasgiovine/SGO-Projeto-de-Software/blob/main/Imagens/Class%20Diagram%20-%20SGO.png"/>

### Diagrama de Componentes
<img src="https://github.com/lucasgiovine/SGO-Projeto-de-Software/blob/main/Imagens/Components%20diagram%20-%20SGO.png"/>

### Diagrama de Implantação
<img src="https://github.com/lucasgiovine/SGO-Projeto-de-Software/blob/main/Imagens/Deployment%20diagram%20-%20SGO.png"/>
