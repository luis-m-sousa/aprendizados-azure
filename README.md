# aprendizados-azure -> Repositório criado para compartilhar conhecimentos adquiridos no bootcamp da XP

# O que é nuvem?
Assim como no curso, onde o Felipe Aguiar utilizou uma analogia à máquinas de lavar roupas, aqui vai uma analogia feita por mim ->
A nuvem é como usar um serviço de streaming para assistir filmes: você não precisa comprar DVDs nem manter um aparelho específico, apenas acessa o conteúdo quando quiser. Da mesma forma, com a computação em nuvem, você pode utilizar recursos de processamento, armazenamento e aplicativos diretamente pela internet, sem precisar montar e manter toda uma infraestrutura física própria.

# Como a nuvem funciona?
A nuvem funciona por meio de uma rede de servidores distribuídos que hospedam dados e aplicações, acessíveis pela internet. Esses servidores são gerenciados por provedores de nuvem (como no curso, o Azure), que garantem o funcionamento, a escalabilidade e a segurança dos serviços. O usuário apenas consome esses recursos sob demanda, como se estivesse alugando poder computacional.

# Por que e onde a utilizamos?
Utilizamos a nuvem para garantir flexibilidade, escalabilidade e economia em diferentes cenários, desde o armazenamento pessoal até operações complexas de empresas.

# Existem três tipos de serviço em nuvem ->

# Nuvem pública -> 
  É gerenciada por provedores terceirizados e serve múltiplos clientes, como a Azure ou a AWS; 
# Nuvem Privada -> 
  É usada por uma única organização e hospedada internamente ou por terceiros; 
# Nuvem híbrida -> 
  Combina as duas, permitindo maior controle e ao mesmo tempo escalabilidade e agilidade.

| Tipo de Nuvem   | Pontos Positivos                                                                | Pontos Negativos                                                                   |
|-----------------|---------------------------------------------------------------------------------|----------------------------------------------------------------------------------- |
| **Pública** (Cloud ou IaaS)    | - Custo mais baixo (paga pelo uso)                                              | - Menor controle sobre a infraestrutura                                            |
|  | - Alta escalabilidade                                                           | - Preocupações com segurança e conformidade                                        |
|                 | - Fácil de acessar e implementar                                                | - Performance pode variar                                                          |
|                 | - Manutenção a cargo do provedor                                                | - Dependência do provedor (lock-in tecnológico)                                    |
| **Privada**  (On-Premise)   | - Maior controle e personalização                                               | - Alto custo de implementação e manutenção                                         |
|   | - Ideal para aplicações sensíveis                                               | - Menor agilidade para mudanças                                                    |
|                 | - Mais segurança e conformidade                                                 | - Escalabilidade limitada                                                          |
|                 | - Performance dedicada e estável                                                | - Requer equipe técnica especializada                                              |
| **Híbrida (Hybrid)**     | - Flexibilidade para alocar recursos                                            | - Implementação e gerenciamento complexos                                          |
|        | - Combina segurança da privada com escalabilidade da pública                    | - Desafios de compatibilidade entre ambientes                                      |
|                 | - Maior controle estratégico                                                    | - Necessita governança e integração eficientes                                     |
|                 | - Otimização de custos e desempenho                                             |                                                                                    |
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Zonas e Regiões em conceitos de Nuvem

| Conceito           | Descrição                                                                   |
|--------------------|-----------------------------------------------------------------------------|
| **Região**         | Área geográfica ampla (ex: us-east-1, southamerica-east1).                |
|                    | Contém múltiplas zonas de disponibilidade.                                |
|                    | Usada para escolher onde os dados e serviços são hospedados.              |
| **Zona (Zone)**    |  Data center individual dentro de uma região.                              |
|                    |  Isolada fisicamente, mas conectada com outras zonas da mesma região.      |
|                    |  Permite distribuir serviços para alta disponibilidade e resiliência.      |
----------------------------------------------------------------------------------------------------

# Benefícios da Nuvem

| Benefício da Nuvem   | Vantagens                                                                                          | Observações                                                                |
|----------------------|----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| **Escalabilidade**   |  Ajuste de recursos conforme a demanda.                                                           |  Pode ser horizontal (mais instâncias) ou vertical (mais potência).       |
|                      |  Suporte ao crescimento do negócio sem reestruturação da infraestrutura.                          |  Evita superdimensionamento e desperdício de recursos.                    |                         
| **Elasticidade**     |  Alocação e desalocação automática de recursos conforme a carga de trabalho.                      |  Garante eficiência operacional e economia de custos.                     |                         
|                      |  Resposta rápida a variações inesperadas na demanda.                                              | Ideal para aplicações com cargas de trabalho variáveis.                  |                         
| **Confiabilidade**   |  Alta disponibilidade dos serviços, mesmo em caso de falhas.                                      |  Redundância e failover integrados garantem continuidade dos serviços.    |                         
|                      |  Menor tempo de inatividade e maior confiança nos sistemas.                                       |  Crucial para aplicações críticas que exigem disponibilidade constante.   |
| **Previsibilidade**  |  Desempenho consistente e estável dos serviços.                                                   |  Facilita o planejamento de capacidade e orçamento.                       |                         
|                      |  Custos operacionais mais controlados e previsíveis.                                              | Auxilia na tomada de decisões estratégicas e financeiras.                |
| **Segurança**        |  Proteção avançada contra ameaças cibernéticas.                                                   |  Inclui criptografia, firewalls e monitoramento contínuo.                 |                         
|                      |  Conformidade com padrões e regulamentações de segurança.                                         |  Responsabilidade compartilhada entre provedor e cliente.                 |
| **Governança**       |  Definição e aplicação de políticas de uso e acesso aos recursos.                                 |  Garante conformidade com normas internas e externas.                     |                        
|                      |  Monitoramento e auditoria contínuos para manter a integridade dos sistemas.                      |  Facilita a identificação e correção de desvios operacionais.             |
| **Gerenciabilidade** |  Ferramentas integradas para gerenciamento eficiente dos recursos.                                | Automatização de tarefas administrativas e operacionais.                 |                         
|                      |  Visibilidade centralizada das operações e desempenho dos serviços.                               |  Suporte à tomada de decisões informadas e estratégicas.                  |                         
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



