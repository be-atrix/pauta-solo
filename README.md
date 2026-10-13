# Pauta Solo

Produto digital para profissionais que cuidam do prÃ³prio negÃ³cio e precisam organizar publicaÃ§Ãµes sem partir de uma pÃ¡gina vazia. O app transforma oferta, pÃºblico e tom de voz em sete pautas editÃ¡veis, com revisÃ£o, exportaÃ§Ã£o e salvamento opcional no navegador.

AplicaÃ§Ã£o: https://pauta-solo-beatrix.beatrizfpedroso1.chatgpt.site

## Ferramenta utilizada

O Lovable apresentou um painel vazio apÃ³s o login. Com autorizaÃ§Ã£o da pessoa responsÃ¡vel pelo projeto, o app foi implementado com assistÃªncia do Codex e publicado pela ferramenta Sites. NÃ£o foi gerado nem exportado pelo Lovable. Esta entrega registra a diferenÃ§a em relaÃ§Ã£o Ã  ferramenta indicada no desafio.

O produto usa modelos de conteÃºdo locais. NÃ£o chama um modelo generativo nem posta automaticamente nas redes sociais. Todo texto sugerido deve ser revisado antes de publicar.

## Dor e tese do MVP

A hipÃ³tese Ã© que pequenos negÃ³cios precisam de uma estrutura simples para manter uma rotina de conteÃºdo. A tese inicial Ã© que o usuÃ¡rio consegue gerar e revisar uma semana de pautas com menos esforÃ§o do que organizar tudo do zero. NÃ£o houve entrevista nem validaÃ§Ã£o comercial com clientes nesta etapa.

O MVP prioriza geraÃ§Ã£o, ediÃ§Ã£o e exportaÃ§Ã£o. Cadastro, pagamentos, atendimento e postagem automÃ¡tica ficaram fora do escopo. Uma futura oferta de personalizaÃ§Ã£o poderia ser vendida e atendida manualmente, depois de verificar interesse real.

## Mercado em cenÃ¡rio ilustrativo

Os nÃºmeros sÃ£o premissas para exercitar o raciocÃ­nio, nÃ£o pesquisa de mercado. TAM: 10 mil negÃ³cios a R$ 29 por mÃªs equivalem a R$ 3,48 milhÃµes anuais. SAM: 500 negÃ³cios do segmento inicial equivalem a R$ 174 mil anuais. SOM: 20 clientes iniciais equivalem a R$ 6.960 anuais. Todos os volumes e o preÃ§o precisam ser validados antes de uma decisÃ£o comercial.

## Business Model Canvas

| Bloco | HipÃ³tese |
| --- | --- |
| Clientes | Profissionais que criam conteÃºdo para o prÃ³prio negÃ³cio |
| Proposta de valor | Uma semana editÃ¡vel de pautas a partir de uma oferta |
| Canais | DemonstraÃ§Ãµes diretas, indicaÃ§Ãµes e comunidades locais |
| Relacionamento | Teste gratuito e acompanhamento manual no piloto |
| Receita | PersonalizaÃ§Ã£o paga a testar, sem cobranÃ§a no MVP |
| Recursos | AplicaÃ§Ã£o, modelos de conteÃºdo e atendimento |
| Atividades | Gerar, entrevistar, revisar modelos e acompanhar uso |
| Parcerias | Comunidades de empreendedores e profissionais de conteÃºdo |
| Custos | Hospedagem, manutenÃ§Ã£o e tempo de atendimento |

## Mega prompt

Crie Pauta Solo em portuguÃªs brasileiro: uma landing page com proposta clara e um planejador gratuito. Receba nome do negÃ³cio, pÃºblico, oferta, data inicial e tom de voz. Gere sete pautas com objetivos diferentes: descoberta, educaÃ§Ã£o, processo, perguntas, oferta, conversa e revisÃ£o. Cada pauta deve ter data, tÃ­tulo, texto editÃ¡vel e indicaÃ§Ã£o de revisÃ£o. Nunca invente depoimentos, preÃ§os ou resultados. Permita filtrar pautas revisadas, exportar CSV e imprimir. Salvar deve ser opcional, somente neste navegador, com restauraÃ§Ã£o e exclusÃ£o da cÃ³pia local. NÃ£o crie login fictÃ­cio, integraÃ§Ãµes, cobranÃ§a ou postagem automÃ¡tica. Explique como os dados sÃ£o usados e ofereÃ§a um exemplo fictÃ­cio. Use design responsivo com fundo creme, verde e tipografia legÃ­vel.

## Ajustes e testes

A data inicial foi formatada explicitamente para evitar diferenÃ§as entre configuraÃ§Ãµes regionais. A impressÃ£o recebeu uma saÃ­da de texto prÃ³pria para evitar cortar o conteÃºdo dos campos. O salvamento valida a estrutura dos registros antes de restaurar e mostra que nÃ£o hÃ¡ sincronizaÃ§Ã£o entre dispositivos.

VerificaÃ§Ãµes executadas: sintaxe JavaScript; HTTP 200; geraÃ§Ã£o de sete pautas com datas consecutivas; ediÃ§Ã£o do primeiro tÃ­tulo; marcaÃ§Ã£o de uma pauta revisada; salvamento; recarregamento; restauraÃ§Ã£o do tÃ­tulo editado e do contador de revisÃ£o. NÃ£o foi realizado teste com clientes reais. A abertura do CSV e o PDF devem ser conferidos manualmente antes de uso comercial.

## Executar localmente

Sirva a pasta do repositório com qualquer servidor estÃ¡tico. Por exemplo: `python -m http.server 8000`. Abra http://localhost:8000.

## Arquivos e privacidade

`index.html`, `style.css` e `app.js` contÃªm a aplicaÃ§Ã£o. Os dados sÃ£o processados localmente; nÃ£o hÃ¡ backend, credenciais ou envio de dados a servidores. A cÃ³pia opcional em armazenamento local Ã© limitada ao navegador atual. NÃ£o inclua dados pessoais de clientes nas pautas.

