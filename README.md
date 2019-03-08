# Projeto para Programação

### Sumário
1. [Cenário](#cenario)
	- 1.1 [Agentes](#agentes)
	- 1.2 [Ambiente](#ambiente)
	- 1.3 [Organização](#org)
	- 1.4 [Técnica](#tecnica)
2. [Funcionamento da Aplicação](#funcionamento)
3. [Avaliação](#avaliacao)

## Cenário <a name="cenario"></a>

Vocês devem desenvolver um sistema multiagente para a simulação de uma eleição de representante discente. Algumas características da simulação devem ser implementadas e são listadas a seguir:

 Quanto aos **Agentes**<a name="agentes"></a>
 - [ ] uma regra
 - [ ] deve existir troca de mensagens entre os agentes
	 - [ ] três performativas diferentes devem ser utilizadas
 - [ ] três tipos de crenças diferentes
	 - [ ] uma *self*
	 - [ ] uma *percept*
	 - [ ] uma *outroAgente*
	 
Quanto ao **Ambiente**<a name="ambiente"></a>
- [ ] dois artefatos
- [ ] um sinal
- [ ] uma propriedade observável
- [ ] uma operação
- [ ] uma operação linkada
- [ ] uma guarda

Quanto a **Organização**<a name="org"></a>
 - [ ] pelo menos um grupo
 - [ ] três papéis
	 - [ ] aluno
	 - [ ] professor 
	 - [ ] representante
 - [ ] pelo menos um esquema
 - [ ] pelo menos uma norma

 Quanto as **Técnicas**<a name="tecnica"></a>
 - [ ] **um** mecanismo de votação implementado em *Jason*
	 - [ ] Plurality
	 - [ ] Borda COunt
	 
> Ao finalizar algum item acima você pode deixar ele marcado com um [x]


## Quanto ao Funcionamento da Aplicação <a name="funcionamento"></a>
Serão duas turmas de alunos, cada turma com 5 agentes alunos. Existirá somente um agente professor, e ele atuará nas duas turmas. O objetivo do sistema é que cada turma escolha o seu respectivo representante discente, e o resultado seja anunciado para todos os agentes do sistema.
No início da simulação o professor anunciará que as eleições para representante discente estão abertas nas duas turmas. Cada aluno que tiver interesse de se candidatar deve anotar seu nome no quadro negro da turma. 
O professor indicará quando os alunos podem votar. O fluxo da votação seguirá o seguinte esquema. 


Encerrada a votação, caberá ao professor contar os votos, comunicar os novos representantes, e publicar o resultado no mural da escola (visível a todos os alunos). Os novos representantes ao receber o comunicado do professor devem adotar o papel de representante da turma.

> **Note:** o fluxo básico deve ser seguido, mas você é livre para escolher como os agentes tomam as decisões, e como você irá implementar cada um dos desafios. Você também pode adicionar características a esse cenário se achar conveniente.

## Quanto a Avaliação <a name="avaliacao"></a>

O trabalho será realizado de maneira individual. O trabalho desenvolvido será avaliado de 0 à 10; 1 ponto extra será atribuído caso o aluno realize um desenvolvimento de dificuldade maior do que o exigido, porém a nota máxima continua sendo 10. 

|Nota|Descrição|
|--|--|
|2.5|fazer o checklist dos agentes|
|2.5|fazer o checklist do ambiente|
|2.5|fazer o checklist da organização|
|2.5|fazer o checklist da técnica especial|

Para cada item **não finalizado** ou **finalizado de maneira não adequada** (segundo julgamento do avaliador) a nota do checklist receberá um desconto proporcional.
