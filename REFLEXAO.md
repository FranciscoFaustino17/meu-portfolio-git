# Reflexão Pessoal

## O que foi difícil

Honestly, quase tudo foi difícil no começo. Quando olhei para
o enunciado pela primeira vez, não entendi absolutamente nada.
Palavras como "branch", "commit", "merge" e "Pull Request"
pareciam um idioma completamente diferente. Fiquei olhando para
a tela sem saber nem por onde começar.

A primeira grande dificuldade foi entender a estrutura de pastas
do repositório. Quando fui criar os arquivos pela primeira vez,
acabei criando as pastas uma dentro da outra, formando um caminho
gigante e errado como "exercicios/ex01-commits/exercicios/ex02-branches".
Tive que deletar tudo e começar do zero — o que foi frustrante,
mas também foi onde aprendi de verdade como o GitHub lida com pastas.

Outra coisa que me confundiu muito foi a janela de "Commit changes".
Eu não entendia o que era aquele campo de mensagem, por que ele
existia ou o que eu devia escrever lá. Parecia um detalhe pequeno,
mas travar nessa etapa me fez perceber que cada parte do Git tem
um propósito específico — nada é decoração.

O exercício de conflito também me deixou com o coração na mão.
Quando apareceu aquela mensagem vermelha dizendo que havia um
conflito que precisava ser resolvido, meu primeiro instinto foi
entrar em pânico. Mas quando entendi que eu mesmo tinha criado
aquele conflito de propósito, e que bastava escolher qual versão
manter, ficou muito mais tranquilo.

## O que ficou claro

O que ficou mais claro para mim foi o propósito de cada coisa.
Um commit é como tirar uma foto do seu trabalho naquele momento —
você registra o que fez e escreve uma legenda explicando. Uma branch
é como fazer um rascunho separado sem estragar o original. E um
Pull Request é o momento em que você diz: "terminei meu rascunho,
pode juntar com o principal."

Essa analogia do rascunho foi o que fez tudo se encaixar na minha
cabeça. Antes eu achava que Git era uma ferramenta só para
programadores experientes. Depois desse exercício, percebi que é
basicamente um sistema de organização — como uma pasta bem
organizada com histórico de tudo que você já fez.

Também ficou claro por que as mensagens de commit precisam ser
descritivas. Quando eu olhava o histórico do meu repositório e
via mensagens como "feat(hello-world): adiciona descrição do projeto",
eu sabia exatamente o que tinha sido feito ali. Se estivesse escrito
só "atualização", eu não teria a menor ideia.

## O que ainda é confuso

Ainda não entendo completamente o que acontece "por baixo dos panos"
quando um conflito é gerado. Eu sei o que fazer quando ele aparece
— escolher qual versão manter e confirmar. Mas não entendo bem como
o Git detecta que duas mudanças são conflitantes e não apenas
complementares.

Também tenho dúvidas sobre quando devo criar uma branch nova versus
fazer o commit direto na main. Nesse exercício eu seguia instruções,
então sempre sabia o que fazer. Mas em um projeto real, como sei
a hora certa de abrir uma branch?

Por fim, o conceito de HEAD ainda é um mistério para mim. Vi essa
palavra aparecer algumas vezes durante o exercício, mas nunca
entendi direito o que ela representa ou por que é importante.
Isso é algo que vou precisar entender melhor nas próximas semanas.
