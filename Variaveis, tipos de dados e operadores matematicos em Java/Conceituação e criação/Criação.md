##Padrão de definição:

<?visibilidade?><?modificador?>tipo nome<?=valorInicial?>;

V: "public","protected" e "private"
M: "static" e "final"
T: tipo de dado
N: nome que é fornecido a variável
VI: um valor inicial, caso se deseje

##Convenções e regras:

- Não devem começar com números;
- Embora permitido, "$" e "_" devem ser evitados;
- São case-sensitive; (vai diferenciar maiusculas e minusculas)
- Sem espaços;
- Não pode ser as palavras reservadas do Java:
	
	abstract continue for new switch assert default ...

##Exemplos:
- int i;
- int I;
- int 1a; (inválida)
- int_1a;
- int $aq;
- int I = 10;
- int final j = 10;
- int asrn24678md;
- int asrn246 78md; (inválida)
- int asrn2$4678_md = 10;
- int asrn2$46%78_md = 10; (inválida)

##Boas práticas:
- Sempre começar com letra miníscula;
- Nomes expressivos;
- Notação camelo;
- Quando constante(final) maiúscula e
	separada por "_";

Exemplos:
- int quantidadeProduto;
- int QuantidadeProduto; (não é uma boa 	prática)
- int final NUMERO_TENTATIVAS = 5;	(constantes em java)
- int final numeroTentativas = 5; 
	(não é uma boa prática)
- int NUMERO_TENTATIVAS = 5;
	(não é uma boa prática, pois defini 	uma prática da constante em uma 	variável que não é final)
- int qtdProd; (não é uma boa prática)
- int i; 
	(aqui pode ser usada no laço de 	repetição for, vai ser descartado no 	final do laço, então não tem 	problema ser apenas "i".)

##Observação: É importante seguir boas práticas, pois o código é feito para outras pessoas, de fácil entendimento.
