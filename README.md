# Clima em Castro-PR

Painel com a previsão do tempo para os próximos 7 dias em Castro (Paraná), feito a partir do **consenso de várias fontes de previsão** (Open-Meteo/vários modelos, MET Norway, wttr.in, INMET, Climatempo e Simepar quando disponível), incluindo os avisos meteorológicos do INMET para o município.

🔗 **Acesse:** https://conradomaxcruz.github.io/clima-castro/

![Prévia do painel](painel.png)

## Como funciona
- A página (`index.html`) é autocontida: funciona offline, sem dependências externas.
- Para cada dia, as fontes disponíveis são comparadas e é calculada a média de temperatura, chuva e vento, com um indicador de **concordância** entre as previsões (alta, média ou baixa).
- O painel é atualizado automaticamente uma vez por dia.

*Previsões são estimativas e podem mudar. Em caso de alerta, siga as orientações da Defesa Civil.*
