# Flightpath
## Aplicação de demonstração para atendimento de voos



Este aplicativo foi criado para operar 100% offline ou 100% online, dependendo da necessidade do usuário.
Em algumas localidades a internet pode ser precária, por isso criei este aplicativo com esta capacidade. 

Mais informações a serem adicionadas abaixo.

Por enquanto, caso queira testar o aplicativo online, vá para o link (é necessário apenas criar uma conta, sem confirmação de e-mail, para testar): [https://flightpath-demo.herokuapp.com](https://flightpath-demo.herokuapp.com) (o primeiro carregamento deve demorar um pouco, já que o aplicativo hiberna após 30 min de inatividade. Caso ele não abra depois de algum tempo carregando me envie um e-mail que colocarei em funcionamento novamente).<br><br>
[Vídeo no youtube para mostrar funcionalidades básicas](https://youtu.be/AyV9l53ODdU)


### Funciona offline?

Sim, este programa funciona completamente offline. Para isto, entre em contato comigo por e-mail (andre.szlima1@gmail.com / andreszlima@ufrn.edu.br)<br>
Apesar de rodar com um navegador (Google Chrome, por exemplo), o servidor pode ser executado na rede local e acessado por todos os outros usuários da mesma rede sem nenhuma conexão com a internet.

### Tenho que confirmar todas as vezes que for imprimir um cartão de embarque?

Não, para o uso real, em produção, o navegador deve rodar em "kiosk mode", que habilita impressão automática.

### Este programa é gratuito/código aberto?

Não, já que foi criado para que empresas consigam ganhar dinheiro de forma mais rápida e eficiente! O repositório privado, que contém o código (proprietário e fechado) atualizado, está concluído. A versão do link [andreszlima.com.br](http://www.andreszlima.com.br) está atualizada com a última versão

#### Dados técnicos

Linguagens de programação: Ruby, HTML5, CSS3, SCSS, Javascript, Coffeescript<br>
Framework: Ruby on Rails<br>
Banco de dados utilizado: PostgreSQL<br>
Banco de dados de cache utilizado: Redis<br>
A atualização de informações em tempo real é feita através do Redis, que transmite informações para todos os usuários conectados. Estas informações são armazenadas, posteriormente, no banco de dados PostgreSQL, que armazena todas as informações para serem acessadas a qualquer momento futuramente.

## Para mais informações: 

* Autor: André de Souza Lima
* E-mail: andre.szlima1@gmail.com / andreszlima@ufrn.edu.br
* Instagram: www.instagram.com/andreszlima
* Twitter: www.twitter.com/andreszlima
