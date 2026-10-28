# Communica — firmware

Distribuição oficial de pacotes para **JC3248W535C_I_Y**, nos papéis Pulpit e Cabin.
O código-fonte permanece em repositório privado. Aqui são publicados apenas os
firmwares compilados, o catálogo, a assinatura e a chave pública.

Consulte a [última versão](https://github.com/MrDobler/communica-firmware-releases/releases/latest).
Os downloads ficam disponíveis após a primeira publicação.

Cada versão contém dois binários de aplicação, `manifest.json`, `manifest.sig`,
`publisher-key.json` e `SHA256SUMS`. Confira modelo e papel antes de atualizar.
A assinatura é Ed25519; a chave confiável deve vir do aplicativo ou de um canal
previamente confiável, não ser aceita automaticamente do pacote baixado.

API pública para o Communica Desktop:

`https://api.github.com/repos/MrDobler/communica-firmware-releases/releases/latest`

A instalação pelo Desktop será disponibilizada em uma etapa posterior. Os
pacotes não incluem bootloader, NVS ou imagem de dados e não autorizam apagar
a memória inteira da placa.
