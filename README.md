# Criando Temas Com CSS sem utilzar JavaScript. 
A pseudoclasse CSS funcional representa:has() um elemento se algum dos seletores relativos que são passados ​​como um argumento corresponder a pelo menos um elemento quando ancorado nesse elemento. Essa pseudoclasse apresenta uma maneira de selecionar um elemento pai ou um elemento irmão anterior em relação a um elemento de referência, usando uma lista de seletores relativa de perdão como um argumento.

A :has()pseudoclasse assume a especificidade do seletor mais específico em seus argumentos da mesma forma que :is()e :not().

Sintaxe
:has( <forgiving-relative-selector-list> )
O parâmetro relativo da lista de seletores é tolerante . Normalmente em CSS, quando um seletor em uma lista de seletores é inválido, toda a lista é considerada inválida. Quando um seletor em uma :has()lista de seletores falha ao analisar, o seletor incorreto ou sem suporte será ignorado e os outros serão usados.

Observe que, se a :has()própria pseudoclasse não for suportada em um navegador, todo o bloco seletor falhará (a menos que :has()ela própria esteja em uma lista de seletores indulgente, como em :is()e :where()).

A :has()pseudoclasse não pode ser aninhada dentro de outra :has(). Além disso, pseudo-elementos não são seletores válidos em :has(). Isso ocorre porque muitos pseudoelementos existem condicionalmente com base no estilo de seus ancestrais e permitir que eles sejam consultados por :has()pode introduzir consultas cíclicas. Embora :has()e pseudo-elementos não sejam :has()seletores válidos, como a lista de seletores perdoa, eles serão simplesmente ignorados. O seletor não falhará.
  
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/:has">Fonte: MDN Web Docs</a>
  
  <a href="https://www.youtube.com/watch?v=XyTYr07OM7c&t=2404s">Maik Brito da Rocketseat explicando sobre o assunto.</a>
  
  <a href="https://caniuse.com/">Consulte aqui as features antes de sair usando. https://caniuse.com/</a>
