# ArtigoEasySpace

Easy Space — Plataforma Web para Locação de Espaços Ociosos

Sobre o Projeto

O Easy Space é uma plataforma digital desenvolvida para facilitar a locação de espaços ociosos destinados a eventos, reuniões, festas e demais atividades de curta duração. A solução surge diante do crescimento da economia compartilhada e da necessidade de alternativas tecnológicas que conectem proprietários de ambientes a usuários que buscam locais temporários.

O projeto foi construído inicialmente como uma aplicação web utilizando HTML, CSS e JavaScript, com prototipação realizada no Figma. O desenvolvimento considera a transformação digital, o uso consciente de recursos urbanos e a demanda crescente por espaços acessíveis e flexíveis.

---------------------------------------------------------------

Contexto e Fundamentação

Uma pesquisa de mercado realizada antes do desenvolvimento indicou que cerca de 38% dos brasileiros possuem algum tipo de espaço ocioso que poderia gerar renda adicional. Esses espaços incluem cômodos extras, garagens, salões, áreas externas e até imóveis inteiros.
Ao mesmo tempo, há uma demanda em expansão por locais de curta duração para uso social ou profissional.

O Easy Space foi projetado como uma resposta direta a esse cenário, oferecendo uma plataforma especializada que facilita e padroniza o processo de locação de forma rápida, transparente e focada no uso não residencial.

--------------------------------------------------------------

Tecnologias Utilizadas

HTML, CSS e JavaScript

Figma (prototipagem)

JWT (autenticação)

Bcrypt (criptografia de senhas)

Google OAuth 2.0 (login por conta Google)

Mercado Pago API (pagamentos)

StreetMap API (geolocalização)

Metodologia

O desenvolvimento foi baseado em um modelo incremental, seguindo as etapas:

Planejamento conceitual: definição das funcionalidades, estrutura lógica e análise de sistemas semelhantes.

Prototipagem visual: criação das interfaces no Figma com foco em usabilidade.

Implementação técnica: desenvolvimento da aplicação web com práticas de modularidade e segurança.

Validação preliminar: testes com usuários, avaliando clareza visual, navegabilidade e fluxo funcional.

As decisões técnicas foram guiadas por princípios de segurança, acessibilidade e escalabilidade.

----------------------------------------------------------

Funcionalidades Implementadas
Autenticação

Login com e-mail e senha utilizando JWT.

Senhas protegidas com hashing via bcrypt.

Login integrado com Google OAuth 2.0.

Sessões seguras e persistentes.

Cadastro de Espaços

Registro de locais com informações completas (endereço, fotos, descrição e características).

Armazenamento estruturado e anonimização de dados sensíveis.

Indexação automática para otimização de busca.

Edição de Dados

Atualização de informações via requisições PATCH.

Validação individual dos campos alterados.

Registro de logs internos para histórico e rastreabilidade.

Processo de Locação

Busca com filtros detalhados (data, localização, tipo de evento, capacidade).

Verificação de disponibilidade em tempo real.

Criação de reserva com status controlado pelo sistema (pendente, confirmada, rejeitada).

Pagamentos

Integração completa com a API do Mercado Pago.

Geração de Preference e checkout seguro.

Webhook responsável pela atualização automática do status da transação.

Conformidade com padrões de segurança (PCI-DSS).

Geolocalização

Conversão de endereços em latitude e longitude via StreetMap API.

Exibição de mapa interativo.

Redirecionamento para Google Maps quando necessário.

annotated-ArtigoEasySpace5D281%…

Resultados

Os resultados demonstram que o Easy Space apresenta:

Viabilidade técnica comprovada.

Navegação clara e boa percepção de usabilidade.

Estrutura sólida para futura expansão e integração com novas tecnologias.

Aderência às práticas de economia compartilhada e uso consciente de recursos urbanos.

A versão atual serviu como prova de conceito funcional, mesmo sem a inclusão de espaços reais cadastrados.

---------------------------------------------------------------------------

Próximas Etapas

Desenvolvimento da versão mobile.

Implementação de chatbots inteligentes para suporte.

Expansão da base de espaços cadastrados.

Aprimoramento do sistema de pagamento e da infraestrutura de segurança.

Conclusão

O Easy Space se destaca como uma solução inovadora para o mercado de locação de curto prazo, com foco em praticidade, acessibilidade e sustentabilidade. O projeto demonstra potencial para crescimento, reforçando o papel das plataformas digitais na reocupação consciente de espaços urbanos.
