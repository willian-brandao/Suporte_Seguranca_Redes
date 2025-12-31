# Metodologias de Diagnóstico e Solução de Problemas

## Processo de Solução de Problemas

A solução de problemas é o processo de identificar, localizar e corrigir problemas. Esse processo envolve a coleta de informações e o uso de um ou mais métodos estruturados de solução de problemas. Depois que o problema na rede é descoberto pela primeira vez, uma das primeiras etapas é coletar informações. 

Segue abaixo a lista de procedimentos para coletar informações:

1. Determinar a natureza do problema
   * Relatórios do usuário final
   * Relatório de verificação sobre o equipamento.
2. Reúna informações relevantes sobre o equipamento
   * Fabricante
   * Marca/Modelo
   * Versão de Firmware
   * Versão do sistema operacional
   * Informações sobre propriedade/garantia
3. Reúna informações de configuração de topologia
   * Topologia Física e Lógica
   * Arquivos de configuração
   * Arquivos de Log
4. Determine se houve problema semelhante anteriormente
   * Passos dados
   * Resultados alcançados
  
## Processo de Solução de Problemas em Sete Etapas

<img width="1020" height="321" alt="image" src="https://github.com/user-attachments/assets/c914572e-745a-46fc-9a39-af472a2f349b" /> </br>


* **Definir o Problema** - O objetivo deste estágio é verificar se há um problema e, em seguida, definir corretamente qual é o problema. Os problemas geralmente são identificados por um sintoma. Os sintomas de rede podem aparecer várias formas diferentes, incluindo alertas do sistema de gerenciamento de rede, mensagens do console reclamações de usuários. Ao reunir os sintomas, é importante fazer perguntas e investigar o problema para localizar o problema em um intervalo menor de possibilidades. 
<br> Exemplo: o problema está restrito a um único dispositivo, um grupo ou a toda a sub-rede ou rede de dispositivos?

    Em uma organização, os problemas são normalmente atribuídos aos técnicos de rede por meio de tickets de problema. Esses tickets são criados usando software de emissão de tickets de problemas que rastreiam o progresso de cada ticket. O software de emissão de tíquetes de problemas também pode incluir um portal de usuário self-service para enviar tickets, acesso a uma base de conhecimento de tickets de problemas pesquisáveis, recursos de controle remoto para resolver problemas do usuário final e muito mais. 

* **Coletar Informações** - Nesta etapa, os alvos a serem investigados devem ser identificados, o acesso aos dispositivos de destino deve ser obtido e as informações coletadas. Durante esta etapa, o técnico pode reunir e documentar mais sintomas, dependendo das características identificadas.

* **Analisar as Informações** - Possíveis causas devem ser identificadas. As informações coletadas são interpretadas e analisadas usando documentação de rede, linhas de base da rede, busca de bases de conhecimento organizacionais, pesquisa na internet e conversa com outros técnicos.
* **Eliminar possíveis causas** - Se várias causas são identificadas, então a lista deve ser reduzida eliminando prograssivamente possíveis causas para eventualmente identificar a causa mais provável. A experiência em solução de problemas é extremamente valiosa para eliminar rapidamente as causas e identificar a causa mais provável.
* **Propor Hipótese** - Quando a causa provável for identificada, uma solução deve ser formulada. Nesta fase, a experiência em solução de problemas é muito valiosa para propor um plano.
* **Testar a Hipótese** - Antes de testar a solução, é importante avaliar e a urgência do problema. Por exemplo, a solução poderia ter um efeito adverso em outros sistemas ou processos? A gravidade do problema deve ser avaliada em relação ao impacto da solução. Por exemplo, se um servidor ou roteador crítico precisar ficar offline por um período significativo, talvez seja melhor esperar até fim do dia de trabalho para implementar a correção. Às vezes, é possível criar uma solução alternativa até que o problema real seja resolvido.
* **Resolva o problema** - Quando o problema for resolvido, informe os usuários e qualquer pessoa envolvida no processo de solução de problemas que o problema foi resolvido. Os outros membros da equipe de TI devem ser informados sobre a solução. é importante documentar adequadamente a causa e a solução, pois isso pode ajudar outros técnicos de suporte a prevenir e resolver problemas semelhantes no futuro.

## Solução de problemas com modelos de camadas

Os modelos OSI e TCP/IP podem ser aplicados para isolar problemas de rede ao solucionar problemas de rede ao solucionar problemas. Por exemplo, se os sintomas sugerirem um problema de conexão física, o técnico pode se concentrar na solução de problemas dos cabos e suas conexões na camada física. 

| Camada                                    | Dispositivo                       |
|-------------------------------------------|-----------------------------------|
| Aplicativo <br> Apresentação  <br> Sessão | Sistema final                     |
| Transporte <br> Rede                      | Roteador/Switch multicamada       |
| Enlace de Dados                           | Switch Padrão                     |
| Física                                    |  Cabos, portas, interfaces        |

Os roteadores e swtiches multicamadas são mostrados na camada 4, a camada de transporte. Embora os roteadores e switches multicamada geralmente tomem decisões de encaminhamento na camada 3, as ACLs nesses dispositivos podem usar as informações da camada 4 para tomar decisões de filtragem. 

## Métodos Estruturados de Solução de Problemas

Existem vários métodos estruturados de solução de problemas que podem ser usados para resolver problemas de computador e rede. O método de solução de problemas usado varia dependendo do tipo de problema e da experiência pessoal do técnico. 

Um técnico pode escolher um ou mais dos seguintes métodos para resolver problema:

* **De baixo para cima (Bottom-Up)** - Comece com a camada física e os componentes físicos da rede e suba pelas camadas do modelo OSI até que a causa do problema seja identificada.

* **De cima para baixo (Top-Down)** - Comece com os aplicativos do usuário final e desça pelas camadas do modelo OSI até que a causa do problema seja identificada.

* **Dividir para conquista (Divide-and-Conquer)** - Comece com os aplicativos de usuário final e desça pelas camadas do modelo OSI até que a causa do problema seja identificada.

* **Siga o Caminho (Follow-the-Path** - Descubra o caminho do tráfego desde a origem até o destino. Esta abordage, geralmente complementa uma das outras abordagens.

* **Substituição** - Troque fisicamente o dispositivo ou componente problemático por um que esteja funcionando. Se o problema for corrigido, o problema estará no item removido. Se o problema persistir, a causa está em outro lugar.

* **Comparação** - Compare detalhes como configurações, versões de software, hardware ou outras propriedades de dispositivos, links ou processos entre situações de funcionamento e não funcionamento e identifique diferenças significativas entre elas.

* **Suposição** fundamentada - Um método de solução de problemas menos estruturado que usa uma suposição baseada na experiência do técnico e em sua capacidade de resolver problemas.

## Diretrizes para Selecionar um Método de Solução de Problemas

Para resolver rapidamente problemas de rede, selecione  método de identificação e solução de problemas de rede mais eficaz. 

<img width="775" height="699" alt="image" src="https://github.com/user-attachments/assets/034a6f9b-4245-45bd-b080-8139733e00c2" />

Por exemplo, os problemas de software geralmente são resolvidos usando uma abordagem de cima para baixo, enquanto o problema baseado em hardware é resolvido usandoa abordagem de baixo para cima. Novos problemas podem ser resolvidos por um técnico experiente usando o método dividr e conquistar. Caso contrário, pode ser utilizada a abordagem de baixo para cima. 
Solução de problemas é uma habilidade desenvolvia ao fazê-lo. Cada problema de rede que você identificar e resolver é adicionado ao seu conjutno de habilidades. 




 
