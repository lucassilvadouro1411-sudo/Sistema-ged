# DOXEVRA SOURCE GUARD — Downloads

Portal público de informações e distribuição do **DOXEVRA SOURCE GUARD** para Windows.

## Pacote de teste disponível

O pipeline do repositório privado executou com sucesso as etapas de testes automatizados, compilação WPF e empacotamento. A configuração automática do GitHub Pages foi a etapa que falhou. Portanto, existe um pacote de teste, mas ele ainda não foi validado como versão estável em máquinas Windows independentes.

- [Abrir a execução do Windows Build e seus artefatos](https://github.com/lucassilvadouro1411-sudo/ff-panel/actions/runs/41549442465)
- Artefato: `doxevra-source-guard-windows`
- Tamanho aproximado: 2,18 MB

**Acesso restrito:** o repositório de origem `ff-panel` é privado. O GitHub exige uma conta com permissão para baixar esse artefato. Este endereço não é um download público anônimo.

## Requisitos do pacote atual

- Windows compatível com .NET Framework 4.8.
- O pacote atual é um ZIP com executável e dependências SQLite, não um instalador MSI.
- OCR requer Tesseract e pacotes de idioma instalados.
- Digitalização requer scanner e driver WIA compatível.

## Recursos presentes no código

- Verificação de integridade SHA-256 e manifesto JSON.
- Catálogo documental e persistência SQLite.
- Contas locais e perfis de acesso.
- Versionamento local.
- Assinatura ECDSA com chave protegida pelo DPAPI do Windows.
- Adaptador OCR para Tesseract.
- Digitalização via WIA.
- Leitura de status e histórico Git.
- Testes automatizados no pipeline Windows.

## Limitações conhecidas

- Não há sincronização multiestação nem backup automático.
- Git é somente leitura nesta etapa.
- A assinatura local não equivale a certificado ICP-Brasil.
- OCR e scanners dependem de componentes externos.
- A compatibilidade e o processo de instalação ainda precisam ser validados em máquinas independentes.
- Não há uma Release pública com binário neste repositório.

## Publicação pública

A página HTML está em [index.html](index.html). O código-fonte continua no repositório privado [ff-panel](https://github.com/lucassilvadouro1411-sudo/ff-panel), preservando sua privacidade.

Para que qualquer pessoa baixe o executável diretamente, o ZIP precisa ser publicado como asset de uma Release deste repositório público. A conexão atual consegue editar arquivos de texto, mas não disponibiliza a operação de upload de binários para Releases.

## Estado

Este projeto ainda não deve ser anunciado como sistema completo ou versão estável. A página informa o que foi gerado, quais etapas passaram e quais validações continuam pendentes.
