# Pauta Solo

Planejador de conteúdo para pequenos negócios. A partir do nome do negócio, do público, da oferta e do tom de voz, o aplicativo prepara sete pautas editáveis, com datas, objetivos e controle de revisão.

[Abrir o aplicativo](https://pauta-solo-beatrix.beatrizfpedroso1.chatgpt.site)

## Funcionalidades

- Criar sete pautas para dias consecutivos.
- Editar títulos e textos e marcar as pautas revisadas.
- Filtrar o planejamento por situação de revisão.
- Exportar CSV e imprimir o plano.
- Salvar, restaurar e apagar uma cópia opcional no navegador.

## Implementação e limites

O aplicativo foi desenvolvido em HTML, CSS e JavaScript, com assistência do Codex, e publicado pela ferramenta Sites. O Lovable não carregou nesta sessão; por isso, esta implementação usa uma ferramenta diferente da indicada no desafio da DIO.

A geração usa modelos de conteúdo locais, sem chamadas a uma IA generativa. Os textos precisam de revisão antes da publicação. O aplicativo não publica nas redes sociais, não oferece cadastro e não processa pagamentos.

Os dados do planejamento são processados no navegador. O salvamento é opcional e não sincroniza dispositivos. Evite incluir dados pessoais de clientes.

## Proposta do negócio

A hipótese do MVP é que uma estrutura simples reduz o esforço de planejar uma semana de conteúdo. Ainda não houve entrevistas com clientes nem validação comercial.

### Business Model Canvas

| Bloco | Hipótese a validar |
| --- | --- |
| Clientes | Profissionais que criam conteúdo para o próprio negócio |
| Proposta de valor | Uma semana de pautas editáveis a partir de uma oferta |
| Canais | Demonstrações, indicações e comunidades locais |
| Relacionamento | Teste gratuito e acompanhamento manual no piloto |
| Receita | Personalização paga, sem cobrança nesta versão |
| Recursos | Aplicativo, modelos de conteúdo e atendimento |
| Atividades | Manter modelos, entrevistar clientes e acompanhar o uso |
| Parcerias | Comunidades de empreendedores e profissionais de conteúdo |
| Custos | Hospedagem, manutenção e tempo de atendimento |

### Exercício de dimensionamento de mercado

Os números abaixo são premissas ilustrativas, não resultados de pesquisa. Com preço hipotético de R$ 29 por mês:

- TAM: 10.000 negócios, equivalentes a R$ 3.480.000 por ano.
- SAM: 500 negócios no segmento inicial, equivalentes a R$ 174.000 por ano.
- SOM: 20 clientes iniciais, equivalentes a R$ 6.960 por ano.

O público, o preço e a disposição para pagar precisam ser validados. Uma oferta futura de personalização poderia começar com atendimento manual.

## Prompt de criação

Crie um planejador de conteúdo em português brasileiro. Receba negócio, público, oferta, data inicial e tom de voz. Prepare sete pautas com objetivos diferentes: descoberta, educação, processo, perguntas, oferta, conversa e revisão. Permita editar títulos e textos, marcar revisões, filtrar, exportar CSV e imprimir. Não invente depoimentos, preços ou resultados. Ofereça um exemplo fictício e salvamento opcional no navegador, com restauração e exclusão da cópia local. Explique o tratamento dos dados. Use uma interface responsiva, com rótulos acessíveis e bom contraste.

## Validação realizada

Foram verificados a sintaxe JavaScript, a resposta HTTP 200, a geração de sete datas consecutivas, a edição de um título, a marcação de revisão e o salvamento e a restauração após recarregar a página. A impressão recebeu uma saída própria para evitar cortes nos campos.

A abertura do CSV e a saída de impressão/PDF ainda precisam de conferência manual. Não houve teste com clientes reais.

## Executar

Abra `index.html` no navegador ou sirva a pasta com um servidor estático já disponível. Por exemplo, se Python estiver instalado:

```sh
python -m http.server 8000
```

Acesse http://localhost:8000. O projeto não exige instalar dependências.

## Arquivos

- `index.html`: interface do planejador.
- `style.css`: apresentação e impressão.
- `app.js`: geração, edição, exportação e armazenamento local.
