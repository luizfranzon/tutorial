# Inadimplência 

Assumindo O.S de Inadimplência.
IXC ->
1. No painel lateral, selecione a opção "Suporte" -> "Ordem de Serviço"
2. Ao abrir a lista de ordens de serviço, nas opções de filtro por SETOR, pesquise por INTERNO.
3. Ao pegar o equipamento de Inadimplência, terá uma etiqueta identificando de que cliente era esse equipamento. Você irá assumir a O.S com o mesmo nome que estiver na etiqueta do equipamento.
4. Para assumir, selecione a O.S clicando uma vez com o botão esquerdo, então, no menu de ações, clique na opção: Assumir

Roteador/Modem ->
1. Com o equipamento em mãos, restaure as configurações de fábrica.
2. Verifique se ele está atualizado, se não, faça a atualização.
3. Faça as configurações através do arquivo de backup.
4. Após ter configurado o equipamento, autorize o dispositivo pela opção da barra lateral esquerda do IXC: Provedor -> Autorizar ONUs.
5. Clique na opção "Consultar todas", e verifique se o modem com o respectivo MAC, aparece para ser liberado na lista.

Liberando o equipamento no IXC ->
1. Para autorizar o equipamento, precisamos preencher os seguintes campos: 
2. Caixa FTTH: sempre será: 1249 - CTO_BASE_TESTE
3. Porta FTTH: Selecione uma das 8 portas que esteja disponível
4. Login: Será um dos 3 logins "testeequipamento" disponíveis.
5. Perfil: Dependende do equipamento que será autorizado: Integrado: Perfil 18. Em Bridge: Perfil 1.
6. Após preencher todos os campos, clique em Salvar, depois em Integração OLT -> Gravar no dispositivo.

Com o equipamento online, iremos efetuar os testes de velocidade na rede 2.4G, 5G e através de um cabo de rede, sempre registrando o resultado no teste no Router Vault.

1. Com os testes feitos, selecione a O.S que assumimos anteriormente e no menu de Ações -> Finalizar.
2. No campo de mensagem, iremos preencher com o seguinte modelo:

Equipamento testado e apto para uso.
MAC: *mac do equipamento*
Ambos os cordões ópticos que voltaram estão ok
Fonte não devolvida pelo cliente.
