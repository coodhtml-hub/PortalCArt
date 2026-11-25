# Memória de continuidade - Portal do Estudante CART

Este documento guarda as decisões e informações do projeto para orientar as próximas alterações.

## Identidade e estrutura

- Portal do Estudante do Conselho Acadêmico de Representantes de Turma (CART), do IFF Campus Campos Centro.
- Sigla confirmada: CART, como aparece na logo.
- Logo CART no cabeçalho, reduzida; sem logo no rodapé.
- Banner verde original, sem a foto enviada anteriormente.
- O projeto deve ficar plano, sem subpastas: HTML, CSS, JavaScript e imagens lado a lado na raiz.
- Textos e informações escritos diretamente em HTML. CSS separado para estilos; JavaScript separado apenas para busca e menu responsivo.
- `index.html` é a página inicial; `orientacoes-academicas.html` e `historia-if.html` são páginas secundárias.
- `server.js`, `package.json` e `Procfile` iniciam o site no Heroku.

## Conteúdo do portal

- Início acolhedor com o atalho “Sou calouro, e agora?”.
- Busca de informações; ícones Google Material Symbols por tópico.
- Cards: acesso à vida acadêmica; calendário acadêmico; avaliações e frequência; documentos; projetos.
- Convivência e direitos/deveres foram removidos dos cards principais. Direitos/deveres continuam no Manual do Estudante.
- Manual do Estudante: seção para orientações, direitos e deveres; o botão “Consultar o Manual do Estudante” aponta para `manual-do-estudante.pdf`, ainda não recebido.
- Calendário: não inserir datas sem o arquivo ou link oficial. A área do calendário ainda aguarda esse material.
- Página “Conheça a história do IF” criada, com o conteúdo histórico aguardando informações oficiais.
- Rodapé descreve o CART como espaço de representação para compartilhar ideias, participar de reuniões e contribuir com a vida acadêmica por meio dos representantes de turma, porta-vozes dos estudantes.
- Créditos: site desenvolvido durante a Comissão Eleitoral 2026.2, presidida por Ana Luísa, para ajudar calouros a conhecer seus direitos e se orientar na rotina do Instituto Federal. Desenvolvimento: Juan de Jesus, chefe de Relações Públicas. Ana Luísa e Juan de Jesus integram a mesa diretora do CART.

## SUAP e Sistema Acadêmico

- SUAP: criar idIFF em `https://id.iff.edu.br/`, selecionar “Obter idIFF”, informar CPF e dados solicitados, criar a senha institucional. Entrar em `https://suap.iff.edu.br/accounts/login/?next=/` com matrícula e senha institucional ou usar gov.br.
- SUAP permite acompanhar informações do ingresso e trajetória acadêmica, inscrever-se em bolsas e projetos, e acessar recursos como e-mail acadêmico.
- Sistema Acadêmico: `https://academico.iff.edu.br/`, selecionar “Aluno”. Usado para boletim e frequência. As etapas completas de login ainda precisam ser informadas.
- As capturas de referência estão na raiz. Dados pessoais visíveis nas imagens do SUAP foram borrados.

## Rede de apoio

- Coordenação do curso: grade curricular, disciplinas e dúvidas do curso.
- Registro Acadêmico: documentos e requerimentos, boletim e frequência.
- CAE (Coordenação de Apoio Estudantil): acolhimento e orientação com psicólogas e assistentes sociais.
- Em caso de dúvida sobre onde buscar ajuda, começar pela coordenação do curso ou atendimento institucional.
- Avaliação perdida: apresentar requerimento e justificativa plausível; por motivo médico, anexar laudo/documento comprobatório; confirmar local e prazo com o setor responsável.
- Orientação específica sobre professores ficou para definir depois.

## Contato e redes sociais

- Instagram CART: `https://www.instagram.com/_cartiff/`
- Instagram IFF Campus Campos Centro: `https://www.instagram.com/iffcamposcentro/`
- O botão “Ver opções de apoio” foi removido. A área de dúvida mostra os dois perfis do Instagram.

## Itens aguardados

1. PDF do Manual do Estudante.
2. PDF ou link oficial do calendário acadêmico.
3. Números/localização das salas dos setores.
4. Instruções completas de login do Sistema Acadêmico.
5. Informações históricas oficiais para a página do IF.
6. Decidir se o card genérico de professores permanece e completar as orientações.

## Ajustes de conteúdo em andamento (25/11/2026)

- No rascunho visual, o rodapé agora deve dizer “Conheça a história do CART” e abrir `historia-cart.html`.
- Crédito corrigido para Irlan de Jesus; Ana Luísa e Irlan de Jesus integram a mesa diretora do CART, junto com os demais componentes.
- Card “Avaliações e frequência”: texto sobre acompanhar avaliações, frequência e informações do dia a dia pelo Q-Acadêmico, com link para `https://academico.iff.edu.br/`.
- Card de documentos: solicitação de documentos e segunda chamada pelo Sistema de Requerimentos do IFF: `https://requerimentos.centro.iff.edu.br/`. Orientação de login do sistema: CPF e senha do idIFF.
- O texto de Oportunidades será enviado depois e deve permanecer breve.
- Após a revisão do rascunho, sincronizar o pacote Heroku plano (HTML, CSS e JavaScript e imagens na raiz).

## Revisão do guia de calouros (25/11/2026)

- Removido o card superior “Projetos e oportunidades”; a orientação permanece como FAQ “Quero participar de um projeto. Como faço?”. Resposta: seguir canais de comunicação CART/IFF, conversar com professores e setores de ensino/pesquisa/extensão, e consultar o SUAP para bolsas e novas oportunidades.
- Substituída a FAQ sobre localização/função de setor por “Preciso localizar um setor ou saber a quem procurar?”. A resposta cita canais CART/IFF, Registro Acadêmico e CAE com psicólogas e assistentes sociais; referência ao Grêmio removida.
- Resposta sobre perder avaliação está aguardando aprovação da leitura da pessoa usuária.

## Materiais visuais/documentais para a história do CART (25/11/2026)

- Incluir na página da história uma seção com documentos históricos anexados para os visitantes consultarem.
- Planejar uma foto do espaço do CART, entendido como a sala B-004 no Bloco B; a foto será feita/enviada depois.
- Integrar documentos e foto na programação final quando os materiais forem fornecidos.
- Antes de disponibilizar documentos publicamente, conferir e ocultar dados pessoais que não devam ser expostos.
