# Symfony 4: Vamos lançar!

Olá pessoal! Sim! Está na hora de Symfony 4! Eu estou muito animado. Por quê? Porque *nada*
me deixa mais feliz do que sentar para trabalhar dentro de um framework onde a codificação é realmente
*divertida*, e onde eu posso criar recursos rapidamente, mas *sem* sacrificar qualidade. 
Bem, talvez eu fosse *até* mais feliz fazendo tudo isso em uma praia... com, que sabe talvez, uma bebida gelada?

De qualquer forma, o Symfony 4 re-imaginou completamente a experiência do desenvolvedor: você vai criar 
melhores recursos, mais rápido do que nunca. *E*, Symfony tem um *novo*, único
super poder: ele se inicia como um microframework, e então escala automaticamente em tamanho de acordo 
com o crescimento do seu projeto. Como? Mantenha-se ligado...

Ah, e eu mencionei que o Symfony 4 é a versão mais rápida de todos os tempos? E que é o mais rápido
Framework PHP? Honestamente, *all* frameworks são rápidos o bastante de qualquer forma, mas o ponto
é este: você está programando sob uma base sólida e incrível.

***TIP
Veja http://www.phpbenchmarks.com para saber mais sobre as estatísticas de benchmark!
***

## Prep: Download & Update Composer

Ok, vamos começar agora! Abra um novo terminal e vá para qualquer diretório
para o seu novo projeto. Certifique-se de que você já tenha [Composer] (https://getcomposer.org/) instalado
globalmente para que você possa simplesmente invokar `composer`. 
Se você tiver alguma dúvida, você pode perguntar nos comentários!

E *claro"*, certifique-se de ter última versão: 

```terminal-silent
composer self-update
```
Isso importante: O Composer recente tem correções de erros do Symfony.

## Instalando o Symfony!

Para fazer download de um novo projeto Symfony, voc deve executar `composer create-project symfony/skeleton`
vamos aproveitar e criar um novo diretorio chamado de `the_spacebar`.

```terminal-silent
composer create-project symfony/skeleton the_spacebar
```
Esse é o nome do nosso projeto! "The Spacebar" será *o* lugar para pessoas de
toda a galáxia para se comunicarem, compartilharem notícias e discutirem sobre as celebridades e
BitCoin. Isso vai ser incrível!

Este comando executado clona o projeto `symfony/skeleton` e depois executa `composer install`
baixando assim todas as suas dependências.

Mais abaixo, há algo *especial*: algo sobre "recipes (receitas)". OooOOO.
As Recipes são um conceito novo e muito importante. Falaremos sobre eles em alguns minutos.

## Iniciando (Starting) seu Servidor Web

OK! Muito bem! Symfony vai nos dar instruçes claras sobre o que devemos fazer agora.
Mas primeiro acesse o novo diretório criado:

```terminal-silent
cd the_spacebar
```

Evidentemente, podemos executar nosso aplicativo imediatamente executando:

```terminal
php -S 127.0.0.1:8000 -t public
```
Este comando inicia o servidor web PHP embutido, que é *excelente* para desenvolvimento. 
`public/` é a pasta raiz do nosso projeto - veremos mais sobre isso em breve!

***TIP
Você também pode usar o Ngingx ou Apache para o desenvolvimento loca! Veja:
http://bit.ly/symfony-web-servers.
***

É hora de explodir! Acesse o seu navegador no link `http: // localhost: 8000`. 
E vamos dizer um olá para o seu novo aplicativo Symfony!

## Nosso pequeno projeto

De volta ao terminal, vou criar uma nova aba. 
Symfony *está pronto* para rodar, já com um novo repositório Git também preparado, o framework já nós *deu* um arquivo perfeito o 
`.gitignore`. Obrigado Symfony!
Isso significa que podemos criar nosso *primeiro* commit bastando confirmar com o comando:

```terminal
git add .
git commit
```
Crie uma mensagem de confirmação calma e bem pensada.

```terminal-silent
# Woohoo! OMG WE ARE USING SYMFONY4
```

Woh! Verifique a saida dos dados: the entire project  - *incluindo* Composer e `.gitignore`
stuff - são apenas 16 arquivos! Nosso aplicativo é pequenino!

Vamos aprender mais sobre o nosso próximo projeto *e* configurar o nosso editor para fazer um desenvolvimento 
em Symfony *incrível*!
