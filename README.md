# Commands
Comandos de re-uso que tenho usado ao longo do tempo para fins diversos e não tenho muito tempo para re-aprender, então "Re use it"



# Procurar no caminho corrente por arquivos .MOV e copiar para outro diretório de preferencia.

find . -iname \*.mov -print0 | xargs -I{} -0 cp -v {} /e/Imagens/Video/
