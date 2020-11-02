# ansible-playbook

Este playbook será executado no grupo localhost, usando a conexão local e também  informando que será utilizado um outro usuário e que ele deverá ser o root. Dos módulos utilizados nele dois foram apresentados na segunda parte, apt e service, e é possível observar como os parâmetros requeridos por eles foram inseridos dentro do YAML.

Os outros dois módulos são o copy, cuja função é copiar arquivos locais (“src=”) para diretórios específicos (“dest=”) dos nós remotos, e template, com função e parâmetros parecidos com o copy porém realizando a substituição de variáveis dentro do arquivo de origem por valores específicos de cada nó ou definidos no próprio playbook (sim, um copia os arquivos enquanto outro permite personalizá-los a partir de um modelo).
