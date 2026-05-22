**Sprint 01:**
**Soluções em energias renováveis e sustentabilidade**

**Identificação do problema central**
O problema central na gestão de eletropostos está na ausência de sistemas capazes de monitorar, controlar e otimizar o processo de recarga de veículos elétricos em tempo real. Atualmente, a maior parte dos eletropostos opera com hardwares isolados, sem integração de dados, o que dificulta o acompanhamento do consumo de energia do usuário, a gestão eficiente da carga elétrica disponível e a aplicação de modelos de tarifação mais justos e dinâmicos.

**Solução proposta (baseada no ecossistema GoodWe)**
A solução proposta pelo nosso grupo consiste no desenvolvimento de um sistema de software para gestão inteligente de eletropostos comerciais, desenvolvido com base no carregador GoodWe HCA G2 disponível na FIAP. O sistema será capaz de monitorar e processar dados (como consumo de energia, potência atual e tempo de carregamento) em tempo real durante as sessões de recarga, por meio da coleta da comunicação com o carregador via protocolo MODBUS.
Além disso, o sistema contribui para a previsão de demanda energética, auxiliando no melhor planejamento e controle da infraestrutura elétrica. Dessa forma, a nossa proposta visa tornar o processo de recarga mais eficiente, organizado e controlado.

**Justificativa**
A proposta se justifica pela necessidade de modernização e melhoria da gestão e do controle dos eletropostos, que atualmente não possuem um monitoramento eficiente e em tempo real. Isso gera um uso pouco otimizado da energia, além da falta de previsibilidade da demanda e falta de métodos de cobrança inteligentes. Nossa proposta, além de criar uma experiência mais agradável para o usuário final, ainda auxilia entregando mais controle, eficiência e viabilidade de monetização para a empresa e os operadores.

**impactos esperados**

**Redução de custos:**
Por conta da gestão inteligente será possível evitar multas por consumo excessivo, controlando a potência máxima e evitando gastos desnecessários.

**Lucro:**
Os eletropostos agora terão um modelo de tarifação dinâmica, fazendo com que seja possível a cobrança por recarga de acordo com o uso e diferenças na precificação por conta de tempo de uso, quantidade de carros, energia solar disponível e horários em que as recargas são feitas.

**Sustentabilidade:**
Priorização no uso de energia solar e incentivo aos usuários a utilizar os carregadores quando houver energia solar disponível, implementando um desconto quando for o caso.

**Redução de desperdício:**
Por conta da gestão inteligente, a energia será distribuída entre os pontos de recarga de maneira mais eficaz.

**Tecnologias utilizadas**
HTML e CSS, utilizados para a criação da interface do software.
MODBUS, para estabelecer a comunicação entre o carregador e o sistema de monitoramento.
Python, utilizado para processamento de dados, definição de tarifação e previsão de demanda.
MySQL, banco de dados para armazenar informações sobre sessões de recarga, histórico de consumo e histórico de cobranças.
Django, framework para poder conectar Python, o banco de dados e a interface web.

**Como os princípios de energias renováveis e sustentabilidade fundamentam a solução.**
A solução se fundamenta na promoção do uso mais eficiente da energia nos eletropostos, reduzindo desperdícios e otimizando o consumo, tornando-o mais sustentável. Isso contribui para um aproveitamento mais racional e inteligente dos recursos e se alinha ao uso de fontes de energia mais limpas e renováveis.
Além disso, os carregadores HCA-G2 possuem um modo de priorização de energia solar, focando no uso da energia produzida pelos painéis fotovoltaicos antes de recorrer à rede elétrica, fazendo com que os veículos sejam carregados principalmente com energias limpas e sustentáveis. 
Para incentivar ainda mais o uso da energia solar, em momentos em que há energia solar disponível para carregamento, o sistema irá aplicar tarifas menores, assim encorajando os usuários a realizar as recargas nesses horários.

