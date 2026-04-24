Análise Inicial de Riscos – SNMP

## Observação
O serviço SNMP foi configurado utilizando a versão 2 e uma community
string simples para acesso de leitura.

## Risco Identificado
- Uso de community string padrão ou fraca
- SNMP v2 não utiliza criptografia
- Informações de gerenciamento podem ser expostas

## Impacto
- Divulgação de informações do dispositivo
- Auxílio à fase de reconhecimento em ataques
- Não conformidade com boas práticas de segurança

## Classificação
Gravidade: Baixa a Média  
Tipo: Má configuração / Exposição de informações
