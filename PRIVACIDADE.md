# Política de Privacidade — Turbo Downloader TM

**Última atualização:** 10 de novembro de 2026  
**Aplicativo:** Turbo Downloader TM (versão 1.2)  
**Desenvolvedor:** Talison Maurer

## 1. Finalidade

O Turbo Downloader TM é um gerenciador de downloads para Windows. Ele permite que a pessoa usuária informe links HTTP/HTTPS, escolha o nome do arquivo, selecione o local de salvamento e realize downloads, inclusive com conexões paralelas quando o servidor permite.

## 2. Dados utilizados pelo aplicativo

Para executar as funções solicitadas, o aplicativo utiliza localmente:

- **URLs de download** inseridas pela pessoa usuária;
- **Links da área de transferência**, apenas quando o **Modo captura** está ativado, para identificar endereços HTTP/HTTPS e preencher o campo de download;
- **Nome do arquivo, pasta de destino, progresso e mensagens de operação** para gerenciar o download.

URLs podem conter dados pessoais ou credenciais de acesso incorporadas pelo próprio site. Por isso, confira os links antes de iniciar downloads e evite compartilhar links com tokens.

## 3. Comunicação com servidores de download

Ao iniciar um download, o aplicativo conecta-se ao servidor correspondente ao endereço fornecido. Esse servidor poderá receber a solicitação HTTP/HTTPS, o endereço solicitado e informações de conexão necessárias, como o endereço IP público. O tratamento desses dados pelo servidor de destino segue as práticas e a política desse terceiro.

## 4. Coleta, telemetria e compartilhamento pelo desenvolvedor

Na versão 1.2, o aplicativo **não implementa cadastro de contas, publicidade, serviços de análise, telemetria nem envio automático de histórico de downloads ou conteúdo copiado para servidores do desenvolvedor**.

O Modo captura preenche um campo local; copiar um link não inicia automaticamente o download.

## 5. Armazenamento e retenção

Os arquivos baixados e segmentos temporários são salvos na pasta escolhida pela pessoa usuária. Segmentos podem permanecer no dispositivo quando um download é pausado ou interrompido, para possibilitar a retomada quando o servidor oferece suporte.

A pessoa usuária pode apagar esses arquivos pelo Windows. O aplicativo não mantém um banco de dados remoto de usuários.

## 6. Segurança

Os downloads são realizados a partir de endereços informados pela pessoa usuária. O desenvolvedor não controla o conteúdo nem as práticas de segurança dos servidores externos. Recomenda-se baixar somente conteúdos autorizados e de fontes confiáveis.

## 7. Crianças e adolescentes

O aplicativo não é direcionado especificamente a crianças nem solicita informações de idade.

## 8. Alterações nesta política

Esta política poderá ser atualizada para refletir futuras versões e funcionalidades. Alterações serão publicadas nesta página, com nova data de atualização.

## 9. Contato

Dúvidas relacionadas ao aplicativo e à privacidade podem ser encaminhadas pelo repositório público de distribuição:

[TurboDownloader-Releases — GitHub](https://github.com/talisonmaurer/TurboDownloader-Releases)

**Observação:** esta política descreve o comportamento verificado no código-fonte da versão 1.2; futuras versões devem ser reavaliadas antes de sua publicação.
