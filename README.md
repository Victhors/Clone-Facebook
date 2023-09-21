Declaração de Finalidade:

Este projeto tem como objetivo exclusivamente fins educacionais e de pesquisa de segurança cibernética. Todas as atividades realizadas aqui são conduzidas de acordo com os princípios de "hacker ético", com o objetivo de aumentar a conscientização sobre ameaças cibernéticas e testar a segurança de sistemas com permissão explícita. Qualquer uso indevido ou ilegal das informações ou ferramentas aqui apresentadas é estritamente proibido e desencorajado. Respeite todas as leis e regulamentos locais e obtenha a devida autorização antes de realizar atividades de segurança cibernética.

Ferramentas Utilizadas

    Kali Linux
    setoolkit

Configurando o Phishing no Kali Linux
Passo 1: Acesso como root

Para iniciar o processo de phishing, é necessário ter privilégios de root. Use o comando abaixo para acessar a conta root:

`bash
sudo su`

Passo 2: Iniciando o setoolkit

Execute o seguinte comando no bash: 

`setoolkit`


Iniciando o setoolkit:

![](https://thumbs2.imgbox.com/63/2c/0gbEK0iZ_t.png)

Passo 3: Configurando o Ataque

**Configurando o Clone**

Passo 4: Obtendo o Endereço da Máquina

Para clonar o site do Facebook, é preciso colocar o ip da máquina. Use o comando abaixo para obter esse endereço em máquinas linux:

`ifconfig`

Passo 5: Configurando a URL para Clonagem

Após obter o endereço IP da máquina, a ferramenta setoolkit solicitará a URL para clonagem. Neste exemplo, usaremos: 

`http://www.facebook.com`

![](https://images2.imgbox.com/92/35/9H06xHy5_o.png)

Agora, a ferramenta estará configurada para clonar o site do Facebook. Ela registrará cada entrada no site, seja através de métodos POST ou métodos GET ou até mesmo o IP da Máquina. Conforme os usuários digitarem seus e-mails/telefones e senhas, essas informações serão registradas no terminal.

![](https://images2.imgbox.com/c6/63/7l6ilMwt_o.png)

