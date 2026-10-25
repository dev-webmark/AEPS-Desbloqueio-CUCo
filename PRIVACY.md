# Privacidade e proteção de dados

## AEPS – Desbloqueio CUCo

A aplicação utiliza a câmara para ler o código de barras do equipamento. O número de série é apresentado na interface e utilizado para preencher o formulário da plataforma CUCo integrada na aplicação.

Na análise do projeto `.aia`, não foram identificados componentes próprios de base de dados, armazenamento persistente, análise estatística ou envio HTTP independente para servidores geridos pela aplicação.

**A plataforma CUCo é aberta no WebViewer em https://cuco.inforlandia.pt/ucode/.** O website pode comunicar com os seus servidores e tratar os dados introduzidos segundo os seus próprios procedimentos e políticas. A aplicação não controla esse tratamento. Assim, não se deve afirmar que não existe qualquer transmissão de dados durante a utilização.

A leitura do código de barras pode exigir acesso à câmara. A instalação do APK pode exigir autorização do Android para aplicações obtidas fora da Google Play Store.

O código-fonte está disponível para consulta. Estas observações baseiam-se na inspeção do projeto e não substituem uma auditoria independente ao APK ou ao comportamento da aplicação em execução.

 
