# Copiloto de Vendas com IA - Climatização Corporativa B2B

## 🎯 Desafio Escolhido e Tema
O projeto consiste em um Assistente de Vendas Consultiva especializado em Engenharia Térmica e Climatização Comercial, focado em fechar vendas de ar-condicionado de alta capacidade e eficiência para escritórios e empresas.

## 👤 Usuário Principal
Vendedores de lojas de climatização, engenheiros de vendas e consultores comerciais B2B que precisam calcular rapidamente a carga térmica estimada e responder a clientes exigentes com argumentos altamente persuasivos.

## 🛠️ Problema que a IA Resolve
Vender climatização corporativa exige precisão técnica (cálculo de BTUs baseado em eletrônicos, pessoas e incidência solar) e contorno de objeções de preço elevado. A IA elimina o erro humano na recomendação do aparelho ideal e acelera o fechamento do contrato gerando propostas comerciais irresistíveis e rápidas.

## 🤖 Abordagem Utilizada
**Copiloto de Vendas e Simulador de Fechamento**: O agente interage em formato de chat simulando o framework SPIN Selling (Situação, Problema, Implicação e Necessidade de Solução) e finaliza com a técnica de Fechamento Assumido por Dupla Alternativa.

## 📚 Base de Conhecimento Utilizada
Como inteligência de negócios, o copiloto utiliza uma estrutura de arquivos markdown locais mapeando as dores ocultas do cliente corporativo:
* `knowledge/produtos.md`: Especificações de modelos Inverter Premium e Sistemas VRF de 36.000 BTUs.
* `knowledge/objecoes.md`: Guia de contorno para objeções de preço ("está caro") focando em ROI (Retorno sobre o Investimento) e economia na conta de luz.
* `knowledge/calculo_carga.md`: Regras de negócio de engenharia (fator multiplicador por pessoa, computadores e sol da tarde).

## 💬 Exemplo de Interação Real Gerada pela IA
**Cliente:** "Quero um ar-condicionado para um escritório de 50 m², trabalham 10 pessoas, tem 8 computadores, uma impressora grande e bate sol à tarde."

**IA (Copiloto):**
> *[SISTEMA: ENGENHARIA TÉRMICA CALCULADA]*
> *Com 10 pessoas, 8 computadores e sol da tarde, seu espaço exige entre 30.000 e 36.000 BTUs. Equipamentos comuns vão quebrar e gastar o dobro.*
> 
> * **Opção 1: Inverter Premium High Efficiency (36k BTUs)** - R$ 6.500 a R$ 8.500. Perfeito para anular o sol da tarde sem picos de energia. Operação ultra silenciosa.
> * **Opção 2: Smart VRF Central Compact (36k BTUs)** - R$ 9.000 a R$ 12.000. IA integrada que direciona o fluxo de ar para onde as pessoas estão, zerando o desperdício.
> 
> * **Combo Recomendado:** Automação Wi-Fi com monitoramento de consumo em tempo real por +R$ 400.
> 
> * **Fechamento:** Para blindar o foco da sua equipe, avançamos com o Inverter Premium ou o imbatível Smart VRF?

## 🚀 Melhorias Futuras
1. Integração com APIs de distribuidoras de energia para calcular a economia exata em Reais (R$) na conta de luz do cliente em tempo real.
2. Integração com o WhatsApp Business para envio automatizado da proposta comercial em PDF logo após o fechamento no chat.

