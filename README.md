Curso de Férias: Introdução ao Ruby on Rails '18

Prof. Alex Kutzke

SEPT/UFPR

---

# Material das aulas

* [Aula 01 - Introdução](01.md)
* [Aula 02 - Passo-a-passo do Rails Guides](02.md)
* [Aula 03 - Uma primeira aplicação](03.md)
* [Aula 03 - Ajax e login](04.md)

# Sobre o Curso

*Introdução ao Ruby on Rails* tem a intenção de ser um curso direto e flexível sobre os tópicos mais importantes no desenvolvimento de aplicação Web com o framework Ruby on Rails.

Para tanto, desde os princípios básicos de instalação do Ruby até conceitos importantes como deploy e internacionalização são abordados.

# Ambiente de trabalho

Embora o Rails esteja apto a ser executado em qualquer plataforma (melhor em algumas do que outras), durante o curso será feito uso de uma máquina virtual simples. Assim, todos os alunos terão condições de compreender e executar os principais passos na configuração de um ambiente de desenvolvimento (e produção) Ruby on Rails.

Nesse sentido, para que tudo corra como planejado, é importante que todos os participantes que utilizarão suas próprias máquinas no curso tenham instalados e configurados os seguintes softwares:

* [VirtualBox]
* [Git]
* [Vagrant]
* Editor de texto como [Sublime Text], [Atom] ou Vim! :)

## Instruções para instalação

Os softwares citados possuem guias de instalação para cada tipo de plataforma.

Para ambientes GNU-linux e macOS, a instalação é, em geral, bem documentada.
Por favor, para tais plataformas, consulte guias de instalação disponíveis na internet.

A seguir, são apresentados links para os arquivos de instalação para plataforma Windows. Em todos eles, basta seguir o processo normal de instalação.

### VirtualBox

https://www.virtualbox.org/wiki/Downloads

### Git

https://git-scm.com/download/win

### Vagrant

https://www.vagrantup.com/downloads.html

É provável que a instalação do Vagrant solicite que o computador seja reiniciado.

### Primeiro teste com Vagrant

Siga os passos a seguir para averiguar se a instalação dos componentes foi realizada com sucesso:

1) Caso esteja em ambiente Windows, execute a aplicação "git bash" (o qual foi instalado juntamente com o Git). Para outras plataformas, utilize a aplicação de terminal de comandos de sua preferência.

2) No terminal aberto, digite os seguintes comandos.

```bash
$ mkdir vagrant
$ cd vagrant
$ mkdir trusty32
$ cd trusty32
$ vagrant init ubuntu/trusty32
$ vagrant up
$ # Esse processo exige internet e pode levar alguns minutos
$ vagrant ssh
```

Caso, após os comandos acima, um terminal de uma máquina virtual Ubuntu esteja disponível, como no exemplo a seguir, então sua instalação foi realizada com sucesso.

> Se tiver problemas, tente a box "hashicorp/precise32".

```bash
$ vagrant ssh
Welcome to Ubuntu 12.04 LTS (GNU/Linux 3.2.0-23-generic-pae i686)

 * Documentation:  https://help.ubuntu.com/
New release '14.04.5 LTS' available.
Run 'do-release-upgrade' to upgrade to it.

Welcome to your Vagrant-built virtual machine.
Last login: Fri Sep 14 06:22:31 2012 from 10.0.2.2
vagrant@precise32:~$
```

Os comandos executados criaram uma pequena máquina virtual utilizando o Vagrant. A imagem utilizada foi de um Ubuntu "limpo" de 32bit, nomeada "trusty32" pela equipe do Vagrant. Essa será a máquina virtual utilizada durante o curso.

O mais interessante do uso do Vagrant é que, para desenvolver suas aplicações, você poderá utilizar seu próprio ambiente nativo. Apenas as aplicações Rails desenvolvidas irão rodar na máquina virtual.

Sugiro uma rápida leitura em materiais sobre Vagrant disponíveis na internet como, por exemplo, a página oficial do projeto: https://www.vagrantup.com/

## Outras informações

Estarei sempre disponível para contato através de email: alex at kutzke dot com dot br

Sugiro a todos aqueles que ainda não possuem uma conta no serviço [GitHub], que criem a sua até início do curso.

[VirtualBox]: https://www.virtualbox.org/wiki/Downloads
[Git]: https://git-scm.com/downloads
[Vagrant]: https://www.vagrantup.com/
[Sublime Text]: https://www.sublimetext.com/
[GitHub]: http://www.github.com
[Atom]: https://atom.io
