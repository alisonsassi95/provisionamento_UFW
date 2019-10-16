# Provisionamento_UFW

Esta página é referente ao segundo trabalho da disciplina de Redes de Computadores II do curso de Ciência da Computação - Unijuí. Ela está rodando sobre uma máquina virtual provisionada pelas ferramentas Vagrant e Puppet. Está utilizando um firewall UFW que gerencia serviços da máquina para habilitar ou negar acessos.

Nosso trabalho será definido:
					1- Habilitar todo o tráfego na porta 22 (ssh)
					2- Habilitar todo o tráfego na porta 80 (http)

# UFW
O UFW é uma solução de código aberto construída em Python e distribuída sob licença GNU (General Public License). Trata-se de uma versão “amigável” do ferramenta iptables.

					Um endereço IP e uma porta estão incluídos nos cabeçalhos de um pacote, mas qual documento da web está sendo recuperado não. Em vez disso, essa informação é transmitida nos corpos dos pacotes, depois que uma conexão já está estabelecida. O UfW é um firewall simples que controla os cabeçalhos dos pacotes, e portanto não podemos bloquear os sites especificamente, mas sim um serviço ou um IP conhecido.
                    Portanto o UFW não pode ser usado para bloquear ou liberar acesso para páginas específicas em um servidor da web.

# Requisitos:
						Vagrant - programa de provisionamento
						Puppet - linguagem de programação
						Virtual Box - armazenar e executar o provisionamento
						Sublime Text - editor de texto gratuito
