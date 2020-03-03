Após identificar o endereço do seu pendrive, execute a sua formatação:

mkfs.vfat /dev/sdb
Relembrando que o caminho do pendrive pode variar conforme configuração da sua máquina.

E finalmente, faça a “queima” da sua imagem ISO no pendrive com o comando abaixo:

dd if=local_da_imagem_iso of=/dev/sdb status=progress && sync

Após a finalização, execute o comando abaixo para remover o pendrive com segurança:

umount /dev/sdb

Está feito!
