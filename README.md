# Projeto para Programação

## Cenário

Vocês devem desenvolver um sistema multiagente para a simulação de uma eleição de representante discente. Algumas características da simulação devem ser implementadas e são listadas a seguir:

 Quanto aos **Agentes**
 - [ ] uma regra
 - [ ] deve existir troca de mensagens entre os agentes
	 - [ ] três performativas diferentes devem ser utilizadas
 - [ ] três tipos de crenças diferentes
	 - [ ] uma *self*
	 - [ ] uma *percept*
	 - [ ] uma *outroAgente*
	 
Quanto ao **Ambiente**
- [ ] dois artefatos
- [ ] um sinal
- [ ] uma propriedade observável
- [ ] uma operação
- [ ] uma operação linkada
- [ ] uma guarda

Quanto a **Organização**
 - [ ] pelo menos um grupo
 - [ ] três papéis
	 - [ ] aluno
	 - [ ] professor 
	 - [ ] representante
 - [ ] pelo menos um esquema
 - [ ] pelo menos uma norma

 Quanto as **Técnicas**
 - [ ] **um** mecanismo de votação implementado em *Jason*
	 - [ ] Plurality
	 - [ ] Borda COunt
	 
> Ao finalizar algum item acima você pode deixar ele marcado com um [x]


## Quanto ao Funcionamento da Aplicação
Serão duas turmas de alunos, cada turma com 5 agentes alunos. Existirá somente um agente professor, e ele atuará nas duas turmas. O objetivo do sistema é que cada turma escolha o seu respectivo representante discente, e o resultado seja anunciado para todos os agentes do sistema.
No início da simulação o professor anunciará que as eleições para representante discente estão abertas nas duas turmas. Cada aluno que tiver interesse de se candidatar deve anotar seu nome no quadro negro da turma. 
O professor indicará quando os alunos podem votar. O fluxo da votação seguirá o seguinte esquema. 


Encerrada a votação, caberá ao professor contar os votos, comunicar os novos representantes, e publicar o resultado no mural da escola (visível a todos os alunos). Os novos representantes ao receber o comunicado do professor devem adotar o papel de representante da turma.

> **Note:** o fluxo básico deve ser seguido, mas você é livre para escolher como os agentes tomam as decisões, e como você irá implementar cada um dos desafios. Você também pode adicionar características a esse cenário se achar conveniente.
