# Focus para Windows

Baixe o ZIP da [versão mais recente](https://github.com/alandecastros/focus-releases/releases/latest), extraia e abra `focus.exe`.

O Focus mostra uma faixa preta no topo de cada monitor. Passe o mouse para abrir.
No painel, ative **Atualização automática** para buscar e baixar novas versões ao
iniciar e a cada hora. Clique em **Reiniciar Focus**, ou feche e abra o aplicativo,
para usar a versão instalada. A preferência começa desativada.

Também é possível usar **Verificar atualização** e instalar manualmente pelo
painel. Não é preciso autenticar no GitHub. Mantenha o executável em uma pasta
onde seu usuário tenha permissão de escrita.

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
