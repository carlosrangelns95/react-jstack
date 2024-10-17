Aula 02:

* Declarativo: descreve o que quer
* Imperativo: Descreve como deve ser feito

* Ex declarativo:
function Title(){
  return (
   <h1 id="title">
      Hello World!
   </h1>
  );
}


* imperativo
const h1 = documentElement('h1');
h1.setAttribute('id', 'title');
h1.innerText = 'hello word!';
document.body.appendChild(h1);

03 intalação:

Instalar o babel com algumas dependências:
npm instal @babel/core @babel/preset-env @babel/cli -D


