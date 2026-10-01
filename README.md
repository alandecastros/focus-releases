# Focus para Windows

Baixe **Focus-Setup.exe** na [versão mais recente](https://github.com/alandecastros/focus-releases/releases/latest)
para instalar o Focus. O instalador usa `%LOCALAPPDATA%\Programs\Focus`, sem pedir
permissão de administrador, e cria um atalho no menu Iniciar. Você pode escolher
criar um atalho na área de trabalho e abrir o aplicativo ao terminar.

Para desinstalar, use **Configurações > Aplicativos > Focus > Desinstalar**.
A preferência de atualização é preservada para uma futura reinstalação.

O arquivo `focus-windows-x64.zip` continua disponível como versão portátil:
extraia e abra `focus.exe`. Versões anteriores à introdução do instalador
disponibilizam apenas o ZIP.

O Focus mostra uma faixa preta no topo de cada monitor. Passe o mouse para abrir.
No painel, ative **Atualização automática** para buscar e baixar novas versões ao
iniciar e a cada hora. Clique em **Reiniciar Focus**, ou feche e abra o aplicativo,
para usar a versão instalada. A preferência começa desativada.

Também é possível usar **Verificar atualização** e instalar manualmente pelo
painel. Não é preciso autenticar no GitHub. Mantenha o executável em uma pasta
onde seu usuário tenha permissão de escrita. A pasta padrão do instalador já
permite isso; não é necessário baixar um novo instalador a cada atualização.

Nas versões **0.1.15 ou superiores**, o atualizador usa o proxy configurado no
Windows, incluindo script PAC e descoberta automática. O HTTPS respeita os
certificados confiáveis do Windows, inclusive os instalados pela TI, e mantém
a validação de certificados ativa. O login integrado segue as políticas da
empresa; o Focus não salva senhas corporativas.

Se a versão anterior não conseguir atualizar na rede corporativa, baixe o ZIP
pelo navegador, feche o Focus e substitua o executável uma vez. Depois use
**Verificar atualização**. Em caso de falha, clique na mensagem do painel para
ver os detalhes de proxy, autenticação ou certificado.

Este repositório distribui somente executáveis para Windows 10/11 x64 e arquivos
de publicação. O código-fonte do aplicativo permanece privado. Os executáveis
ainda não têm assinatura Authenticode. Cada versão inclui `SHA256SUMS` para
verificação de integridade.
