# AEPS – Desbloqueio CUCo

Aplicação Android desenvolvida pela Equipa de Apoio Digital do **Agrupamento de Escolas de Penafiel Sudeste (AEPS)** para facilitar o desbloqueio CUCo dos equipamentos informáticos.

## Funcionalidades

- Leitura do código de barras através da câmara do telemóvel.
- Apresentação e preenchimento automático do número de série na plataforma CUCo.
- Acesso à plataforma CUCo integrada na aplicação através de WebViewer.
- Continuação do processo no website CUCo com os valores CT e UC do equipamento.

## Descarregar e instalar

**Android:** https://aepenafielsudeste.pt/apps/

A instalação fora da Google Play Store pode exigir autorização no Android. Recomenda-se a análise pelo Google Play Protect.

## Como utilizar

1. Abra a aplicação e toque em **LER CÓDIGO DE BARRAS**.
2. Leia o código de barras presente no equipamento.
3. Aguarde a abertura da plataforma CUCo e confirme o número de série.
4. Siga as instruções da plataforma e introduza os valores **CT** e **UC** apresentados no equipamento.

## Código-fonte

O ficheiro [`source/AEPS_DesbloqueioCUCO.aia`](source/AEPS_DesbloqueioCUCO.aia) contém o projeto MIT App Inventor e pode ser importado na plataforma para consulta dos blocos, ecrãs e recursos.

## Privacidade

A análise do projeto não identificou componentes próprios de armazenamento persistente ou de envio HTTP independente. A aplicação usa um **WebViewer** para abrir `https://cuco.inforlandia.pt/ucode/` e preencher o número de série no formulário. O website CUCo pode transmitir e tratar os dados introduzidos de acordo com os seus próprios procedimentos. Consulte [PRIVACY.md](PRIVACY.md).

A disponibilização do código não equivale a uma auditoria ou certificação de segurança.

## Autoria e âmbito

Desenvolvido por **Bruno Ferreira**, no âmbito do AEPS, em 2026. Ferramenta de apoio, independente da entidade responsável pela plataforma CUCo.

## Licença

Ainda não foi definida uma licença de reutilização e redistribuição. O código está disponível para consulta; não se presume autorização para reutilização ou distribuição por terceiros.
