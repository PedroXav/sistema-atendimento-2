# sistema atendimento 2
# Implementar a versão 2.0 do sistema de atendimento já realizado, agora com a oferta de 5 opções através de um seletor:

# 0. Sair
# 1. Gerar senha
# 2. Abrir guichê
# 3. Realizar atendimento
# 4. Listar senhas atendidas
# A opção 1 deverá incrementar o controle de senhas, gerando e enfileirando a senha gerada na fila "senhasGeradas"
# A opção 2 deverá adicionar, em uma estrutura do tipo Lista, um objeto (struct) contendo o id do guichê e uma fila (senhasAtendidas) para o armazenamento das senhas atendidas por ele

# A opção 3 deverá solicitar a digitação do id do guichê que está chamando a senha "da vez", enfileirando-a na fila "senhasAtendidas" do respectivo guichê


# A opção 4 deverá solicitar a digitação do id do guichê e, na sequência, listar todas as senhas que foram atendidas por ele

# Sempre que o seletor for exibido, informar a quantidade de senhas ainda aguardando atendimento e o número de guichês abertos para atendimento.

# O programa só poderá ser encerrado quando a fila "senhasGeradas" estiver vazia. Ao encerrar, informar a quantidade de senhas atendidas.
