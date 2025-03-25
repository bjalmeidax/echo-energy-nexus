## Requisitos

As tabelas a seguir apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicamos uma técnica de priorização e detalhamos como ela foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-------------------------|------------|
|RF-01| Permitir o cadastro de dispositivos elétricos com informações como nome, potência, localização e categoria. | ALTA |
|RF-02| Possibilitar a edição e remoção de dispositivos cadastrados. | ALTA | 
|RF-03| Associar dispositivos a cômodos ou setores dentro de uma residência ou empresa. | ALTA |
|RF-04| Exibir o consumo em tempo real de cada dispositivo cadastrado. | ALTA |
|RF-05| Gerar gráficos e relatórios detalhados sobre o histórico de consumo. | ALTA |
|RF-06| Oferecer filtros por período (dia, semana, mês, ano) e por dispositivos. | MÉDIA |
|RF-07| Apresentar comparativos de consumo por setor, cômodo ou dispositivo. | MÉDIA |
|RF-08| Enviar alertas sobre picos de consumo ou uso excessivo. | ALTA |
|RF-09| Sugerir horários de uso para economia com base no histórico de consumo. | MÉDIA |
|RF-10| Oferecer recomendações personalizadas para redução de consumo. | MÉDIA |
|RF-11| Permitir o estabelecimento de metas de consumo por setor ou dispositivo. | MÉDIA |
|RF-12| Oferecer relatórios preditivos de consumo futuro com base em dados históricos. | MÉDIA |
|RF-13| Implementar controle remoto para desligar dispositivos (se houver suporte a IoT). | BAIXA |
|RF-14| Implementar autenticação de usuário com login e senha. | ALTA |
|RF-15| Permitir login social via Google. | MÉDIA |
|RF-16| Possibilitar a recuperação de senha via e-mail. | MÉDIA |
|RF-17| Permitir exportação de relatórios em PDF, CSV e Excel. | MÉDIA |
|RF-18| Oferecer API para integração com sistemas de terceiros (ERP, Smart Grids, etc.).  | BAIXA |

### Requisitos Não Funcionais

|ID     | Descrição do Requisito  | Prioridade |
|-------|-------------------------|------------|
|RNF-01| O sistema deve suportar até 1.000 dispositivos cadastrados sem perda de desempenho. | ALTA | 
|RNF-02| O tempo de resposta das consultas de consumo deve ser inferior a 2 segundos. | ALTA | 
|RNF-03| A aplicação deve permitir operação offline, sincronizando dados quando online. | MÉDIA | 
|RNF-04| Os dados dos usuários devem ser armazenados de forma criptografada. | ALTA |
|RNF-05| O sistema deve garantir controle de acesso com níveis de permissão para usuários. | ALTA |
|RNF-06| A interface deve ser intuitiva e acessível, seguindo boas práticas de UX/UI. | ALTA | 
|RNF-07| O sistema deve oferecer um tema escuro e um modo de alto contraste para acessibilidade. | MÉDIA | 
|RNF-08| A aplicação deve ser compatível com Windows, macOS e Linux. | MÉDIA | 
|RNF-09| O software deve ser desenvolvido utilizando Java e JavaFX para a interface gráfica. | ALTA | 
|RNF-10| O banco de dados deve ser PostgreSQL ou MySQL para armazenamento de dados. | ALTA | 
|RNF-11| O código deve ser modular e bem documentado para facilitar a manutenção. | ALTA | 
|RNF-12| O sistema deve permitir a atualização automática sem necessidade de reinstalação manual. | BAIXA | 
