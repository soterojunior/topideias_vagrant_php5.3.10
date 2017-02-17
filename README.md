![newwallpaperfacebook logo](newwallpaperfacebook.jpg)

Vagrant Setup
===========

Ubuntu Server 12.04 64 Bits

Ambiente de Desenvolvimento PHP 5.3.10 

###Pacotes Inclusos:

- PHP 5.3.10
- MySQL 5.5
- Git
- PhpMyAdmin 
- Composer
- cURL
- Vim
- Redis


Pré-requisito: 
==============

- Virtualbox - https://www.virtualbox.org/
- Vagrant - http://www.vagrantup.com/
- Git - http://git-scm.com ( Opicional )

Instale o Virtualbox e o Vagrant de acordo com seu sistema operacional.

Instalação
===========

* Clone esse repositório para sua máquina no terminal: `git clone https://github.com/soterojunior/topideias_vagrant_php5.3.10`

* Acesse o repositório e inicie a máquina virtual com o comando: `vagrant up`

O Vagrant irá baixar o sistema operacional ( isso pode demora um pouco ), irá configurar a máquina virtual no VirtualBox e posteriormente baixar, instalar e configurar todos os pacotes do script `setup.sh`.

Quando tudo estiver pronto, um servidor web estará disponível no endereço `http://localhost:8080`, e a instalação do PHPMyAdmin está em `http://localhost:8080/phpmyadmin`, para acessar utilize:

- Login: root
- Senha: vagrant

obs:(A senha padrão para todos os serviços é vagrant).


Coloque seu código no diretório `www` do repositório. Todo o conteúdo dele estará disponível via `http://localhost:8080`. (Como teste, já existe um arquivo index.php que chama a função phpinfo() ).

Para desligar a máquina virtual utilize o comando: `vagrant halt`

Para religar novamente utilize: `vagrant up`

Caso queira destruir a máquina virtual (o conteúdo do www não será excluido): `vagrant destroy`


![logo_top_ideias logo](logo_top_ideias.png)

Top Ideias

[http://www.topideias.com.br](http://www.topideias.com.br)
