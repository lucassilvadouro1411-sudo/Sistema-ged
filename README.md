# DOXEVRA GED ENTERPRISE

Site institucional e demonstração web do projeto DOXEVRA.

## Publicação web
- Página: `index.html`
- Deploy: GitHub Actions em `.github/workflows/pages.yml`
- Branch de produção: `main`

A URL esperada do GitHub Pages é:
https://lucassilvadouro1411-sudo.github.io/Sistema-ged/

O workflow de deploy foi adicionado. A publicação depende de GitHub Pages estar habilitado nas configurações do repositório. Não foi possível habilitar a configuração de Pages pela integração disponível nesta sessão.

## Funcionalidades desta página
- Site responsivo em português brasileiro.
- Tema claro/escuro.
- Simulador visual de famílias de scanners (não detecta hardware real).
- Seções de GED, OCR, captura, segurança e segmentos.
- Calculadora estimativa de ROI.
- Apresentação de planos sem preços publicados.
- FAQ e prévia visual do portal do cliente.

## Limites desta entrega
Esta é uma página estática. Não contém backend nem serviços de produção para autenticação, clientes, licenças, máquinas, faturas, pagamentos, chamados, API, OCR remoto ou armazenamento em nuvem. Não inserir credenciais ou dados pessoais no portal demonstrativo.

A compatibilidade WIA/TWAIN, o OCR e qualquer assinatura ICP-Brasil precisam ser implementados e testados no aplicativo Windows. O simulador web não representa conexão real a scanners.

## Aplicativo Windows
O código do aplicativo está no repositório privado:
https://github.com/lucassilvadouro1411-sudo/ff-panel

O README desse projeto descreve a fundação C#/WPF e as funcionalidades ainda pendentes. O artefato de teste do GitHub Actions exige acesso ao repositório privado e ainda não é uma Release pública estável:
https://github.com/lucassilvadouro1411-sudo/ff-panel/actions/runs/41549442465

## Próximas etapas para uma edição SaaS de produção
1. Backend hospedado e banco de dados gerenciado.
2. Autenticação segura, recuperação de conta e RBAC.
3. Serviço de licenças e ativação de máquinas.
4. Checkout e faturamento com provedor de pagamentos.
5. API de suporte e upload seguro de laudos.
6. Publicação pública do instalador assinado após testes independentes.
7. Política de privacidade, termos, retenção e plano de resposta a incidentes.
