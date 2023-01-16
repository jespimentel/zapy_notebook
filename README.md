# **zapy_notebook**
José Eduardo de Souza Pimentel (2022)
- - - 

### Ferramenta forense para a análise de metadados do WhatsApp

### Introdução

O WhatsApp fornece por e-mail os metadados das comunicações realizadas pelo app, em atendimento à ordem judicial de afastamento do sigilo telemático.

O programa lê os e-mails que contêm tais metadados e organiza toda a informação numa planilha Excel e em gráficos para facilitar a análise pelo investigador. 

Também consulta a api IPAPI (https://ipapi.com) para a obtenção de informações adicionais relacionadas aos IPs coletados, tais como 'hostname', 'latitude', 'longitude', 'cidade' e 'região', podendo plotá-las no mapa (Folium).

### Uso

1. Mova para os arquivos 'eml' para a pasta de trabalho ('/content/').
    > Opcionalmente, com o uso do MS Outlook, exporte um lote de emails no formato 'txt' (importante: codificação *ASCII*). O programa dará preferência à leitura desse tipo de arquivo.
    > Certifique-se de que o arquivo txt gerado ou os e-mails carregados dizem respeito ao mesmo alvo.
1. Rode a aplicação.
- O programa perguntará:
    - se você deseja restringir a consulta da API; e
    - se você deseja gerar gráficos para análise dos dados coletados.

### Observações

- As sugestões para o aprimoramento do programa são muito bem-vindas.
- Encontre a versão em script em: github/jespimentel
