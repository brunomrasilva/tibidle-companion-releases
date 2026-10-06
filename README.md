# Tibidle Companion — releases

Instaladores e dados do **Tibidle Companion** (companheiro de automação para o Tibidle).
O código-fonte é privado; este repositório só guarda o que o app baixa sozinho.

- **[Baixar a versão mais recente](https://github.com/brunomrasilva/tibidle-companion-releases/releases/latest)**
  (`TibidleCompanion-Setup-*.exe`). Windows 10/11 64 bits.
- O app instalado procura versões novas sozinho e oferece "Atualizar agora" no painel.
- `data/`: seletores do jogo, caçadas e Elites. O app atualiza esses arquivos sozinho (até 1 h) quando o jogo
  muda, sem precisar de um instalador novo.

O instalador é assinado por **Bruno Moreira** (certificado próprio). O Windows pode mostrar "editor
desconhecido": para confiar no editor, importe `BrunoMoreira-assinatura.cer` (anexo de cada release) em
"Autoridades de Certificação Raiz Confiáveis".

Comprar a licença (versão PRO): <https://tibidle-webhook.vercel.app/api/create-payment-link?product=tibidle>
