## KuruGit

<pre>

Seja bem-vindo à ferramenta de download/update para as tools da
Uname Corporation.

  _  __                 ____ _ _
| |/ /   _ _ __ _   _ / ___(_) |_
| ' / | | | '__| | | | |  _| | __|
| . \ |_| | |  | |_| | |_| | | |_
|_|\_\__,_|_|   \__,_|\____|_|\__|
</pre>

## Descrição da Ferramenta

O KuruGit  uma ferramenta que tem por finalidade auxiliar na obtenção das ferramentas desenvolvidas pela equipe da UnameCorporation. Ela automatiza o processo de download e instalação delas no sistema operacional, questionando intuitivamente sobre os processos a serem seguidos.

## Chamada da Ferramenta
> uname@kurupira: kurugit <parâmetros>

## Help

Abaixo você pode conferir o menu help da ferramenta:

<pre>
Ajuda do programa:


-u | --update      Atualiza a lista de ferramentas
-h | --help        Este menu de ajuda
-d | --download    Menu de download de ferramentas
</pre>

## Exemplo de uso

A ferramenta trabalha, atualmente, de forma intuitiva com um menu listando as ferramentas e permitindo ao usurio escolher qual deseja baixar. Por exemplo, um uso comum de download seria:

<pre>
kurugit -d

Seja bem-vindo à ferramenta de download/update para as tools da
Uname Corporation.

  _  __                 ____ _ _
| |/ /   _ _ __ _   _ / ___(_) |_
| ' / | | | '__| | | | |  _| | __|
| . \ |_| | |  | |_| | |_| | | |_
|_|\_\__,_|_|   \__,_|\____|_|\__|


Segue a lista das ferramentas no repositório:

[1] - uname_ctf-tools
[2] - Onion-Checker
[3] - whatcripto
[4] - cryptrsa

Escolha um dos números listados acima para começar o download ou
pressione 0 para sair:

>_

</pre>

Desse ponto, o usuário escolhe o que quer baixar e o processo de download e instalação é iniciado. Vale ressaltar que a lista acima pode estar desatualizada no tempo que você está lendo essa documentação

## Dependências

- curl
- coreutils
- sudo
- git

**Autor:** Jesus santos

**Linguagem utilizada:** Shell Script

**Versão atual:** 0.1 Stable

**Ambiente de testes:** Kali Linux, Ubuntu, KurupiraOS

**Colaboradores:** Equipe de desenvolvimento de ferramentas da UnameCorporation

**Licensa:** GPLv3

## Relatório de bugs:

**GitHub:** https://github.com/unamecorporation/KuruGit

**Bugs:** https://github.com/JesusFromHellz/KuruGit/issues
