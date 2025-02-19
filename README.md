Trata-se de um plugin gratuito para o ImageJ, desenvolvido para o tratamento e aprimoramento de impressões digitais. Baseado na versão 2.2 do SourceAfis, ele oferece funcionalidades voltadas para a análise forense, permitindo a aplicação de diversos filtros e técnicas de processamento de imagem para melhorar a qualidade e a visibilidade das marcas papilares. Seu uso é indicado tanto para profissionais e pesquisadores da área forense quanto para aqueles que desejam conhecer melhor o funcionamento de um sistema AFIS (Automated Fingerprint Identification System), explorando os princípios envolvidos na análise e comparação de impressões digitais.

Devido à versão 1.8 do Java utilizada pelo ImageJ, algumas limitações estão presentes, pois impactam a compatibilidade com versões mais recentes do SourceAfis.

**Instalação**

Para instalar o plugin corretamente, siga os passos abaixo:

1. Localize a pasta de plugins do ImageJ: No diretório principal do ImageJ, acesse a pasta Image/Plugins.
2. Criação do diretório Digitais: Dentro da pasta Plugins, crie uma nova pasta chamada Digitais.
3. Inserção do plugin: Copie o arquivo Compara_digitais.jar para dentro da pasta Digitais.
4. Execução: Após iniciar o ImageJ, o novo menu de ferramentas será disponibilizado automaticamente dentro do ImageJ.

Ao executar o plugin, a ferramenta disponibiliza as seguintes opções dentro do menu "Digitais ":

Menu - Digitais

| → Compara Digitais – Realiza a comparação entre duas impressões digitais ativas na tela; |
| --- |
| → Extrai Minúcias – Identifica e extrai pontos característicos (minúcias) das digitais, como bifurcações e terminações. |
| → Converte 500 DPI – Ajusta a resolução das imagens para 500 DPI, garantindo compatibilidade com padrões biométricos. O processo utiliza referências inseridas na imagem, exigindo que o usuário, por meio da ferramenta "Straight Line", selecione um segmento de 1 cm para calibração adequada. |
| → Pesquisa Digitais – Permite, a partir de uma impressão digital ativa na tela, realizar a busca por impressões similares em um diretório selecionado pelo usuário (1:N). |

O projeto tem como objetivo desenvolver uma ferramenta de comparação de impressões digitais com foco acadêmico. No entanto, o plugin se torna uma solução prática e eficiente para a análise de impressões digitais, sendo uma ferramenta valiosa também para aplicações forenses.
