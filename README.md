# Commands
Comandos de re-uso que tenho usado ao longo do tempo para fins diversos e não tenho muito tempo para re-aprender e tô velho pra memorizar, então

"Re use it"


| Comando | Descrição |
|---------|-----------|
| find . -iname \*.mov -print0 \| xargs -I{} -0 cp -v {} /e/Imagens/Video/ | Procurar no diretório corrente arquivo com extenção .MOV e copia-lo para outro diretório  |
