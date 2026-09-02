<p align="center">
  <a href="https://github.com/arthurspk/guiadevbrasil">
    <img src="./images/guia.png" alt="Guia de OpenStack" width="160" height="160">
  </a>
  <h1 align="center">Guia de OpenStack</h1>
</p>

## :dart: O guia para alavancar a sua carreira

> OpenStack é a principal plataforma open source para montar nuvem privada e pública no modelo IaaS: computação (Nova), rede (Neutron), armazenamento em bloco e de objetos (Cinder e Swift), catálogo de imagens (Glance) e orquestração (Heat), tudo integrado por um serviço de identidade central (Keystone). Nasceu em 2010, de uma parceria entre a NASA e a Rackspace, e hoje é mantido pela OpenInfra Foundation, rodando em operadoras de telecom (redes 5G/NFV), bancos, universidades e provedores de nuvem pública como OVHcloud e VEXXHOST. Este guia reúne documentação oficial, cursos, livros, ferramentas de deploy (DevStack, Kolla-Ansible, Charmed OpenStack), o movimento mais recente de rodar OpenStack sobre Kubernetes (operators, VEXXHOST Atmosphere, Red Hat OpenStack Services on OpenShift) e um capítulo dedicado a IA na prática — tudo verificado e organizado para quem quer sair do primeiro `openstack server list` até administrar um cluster de produção.

<sub> <strong>Siga nas redes sociais para acompanhar mais conteúdos: </strong> <br>
[<img src = "https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">](https://github.com/arthurspk)
[<img src = "https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/seixasqlc/)
[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/arthurspk/)
[<img src = "https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white">](https://twitter.com/manotoquinho)
[![Discord Badge](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/NbMQUPjHz7)
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/guiadevbrasil/)
[![Youtube Badge](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCzmXzz_VR0Li8-YOvWN_t3g)
</sub>

## ⚠️ Aviso importante

> Antes de tudo você pode me ajudar e colaborar, deu bastante trabalho fazer esse repositório e organizar para fazer seu estudo ou trabalho melhor, portanto você pode me ajudar das seguintes maneiras:

- Me siga no [Github](https://github.com/arthurspk)
- Acesse as redes sociais do [Guia Dev Brasil](https://linktr.ee/guiadevbrasil)
- Mande feedbacks no [LinkedIn](https://www.linkedin.com/in/arthurspk/)

## 💡 Nossa proposta

> A proposta deste guia é dar uma ideia sobre o atual panorama e guiá-lo se você estiver confuso sobre qual será o seu próximo aprendizado, sem influenciar você a seguir os 'hypes' e 'trends' do momento. Acreditamos que com um maior conhecimento das diferentes estruturas e soluções disponíveis poderá escolher a ferramenta que melhor se aplica às suas demandas. E lembre-se, 'hypes' e 'trends' nem sempre são as melhores opções.

## :beginner: Para quem está começando agora

> Não se assuste com a quantidade de conteúdo apresentado neste guia. Acredito que quem está começando pode usá-lo não como um objetivo, mas como um apoio para os estudos. <b>Neste momento, dê enfoque no que te dá produtividade e o restante marque como <i>Ver depois</i></b>. Ao passo que seu conhecimento se torna mais amplo, a tendência é este guia fazer mais sentido e ficar fácil de ser assimilado. Bons estudos e entre em contato sempre que quiser! :punch:

## 🚨 Colabore

- Abra Pull Requests com atualizações
- Discuta ideias em Issues
- Compartilhe o repositório com a sua comunidade

## 🌍 Tradução

> Se você deseja acompanhar esse repositório em outro idioma que não seja o Português Brasileiro, você pode optar pelas escolhas de idiomas abaixo, você também pode colaborar com a tradução para outros idiomas e a correções de possíveis erros ortográficos, a comunidade agradece.

<img src = "https://i.imgur.com/lpP9V2p.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>English — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/GprSvJe.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Spanish — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/4DX1q8l.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Chinese — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/6MnAOMg.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Hindi — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/8t4zBFd.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Arabic — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/iOdzTmD.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>French — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/PILSgAO.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Italian — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/0lZOSiy.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Korean — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/3S5pFlQ.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Russian — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/i6DQjZa.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>German — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>
<img src = "https://i.imgur.com/wWRZMNK.png" alt="Guia Extenso de Programação" width="16" height="15">・<b>Japanese — </b> [Click Here](https://github.com/arthurspk/guiadeopenstack)<br>

## 📚 ÍNDICE

[🗺️ Roadmap](#️-roadmap) <br>
[📖 Documentação oficial](#-documentação-oficial) <br>
[🔤 Sites e cursos para aprender OpenStack](#-sites-e-cursos-para-aprender-openstack) <br>
[📚 Livros](#-livros) <br>
[🎥 Canais no Youtube](#-canais-no-youtube) <br>
[🛠️ Ferramentas](#️-ferramentas) <br>
[🧪 Projetos práticos e desafios](#-projetos-práticos-e-desafios) <br>
[🤖 IA na prática](#-ia-na-prática) <br>
[💼 Carreira e vagas](#-carreira-e-vagas) <br>
[👥 Comunidades](#-comunidades) <br>
[🎓 Certificações](#-certificações) <br>

## 🗺️ Roadmap

- [Ciclo de releases do OpenStack](https://releases.openstack.org/) — Calendário de todas as versões e dos módulos que compõem cada uma; mostra a versão mais recente, a 2026.1 "Gazpacho".
- [Notas da versão 2026.1 "Gazpacho"](https://releases.openstack.org/gazpacho/) — Detalhamento módulo a módulo do que mudou na versão mais recente do OpenStack.
- [OpenStack Project Navigator](https://www.openstack.org/software/project-navigator/) — Mapa oficial de todos os serviços que compõem o OpenStack (computação, rede, armazenamento, orquestração etc.), ponto de partida para decidir o que estudar primeiro.
- [Architecture Design Guide](https://docs.openstack.org/arch-design/) — Guia oficial para decidir quais componentes usar de acordo com o tipo de nuvem que você quer montar (geral, armazenamento, computação, rede).
- [OpenStack Technical Committee](https://governance.openstack.org/tc/) — Quem decide os rumos técnicos do projeto e como as decisões de arquitetura são tomadas.

## 📖 Documentação oficial

- [Documentação oficial (docs.openstack.org)](https://docs.openstack.org/) — Portal central de toda a documentação, organizada por versão e por projeto.
- [Install Guide](https://docs.openstack.org/install-guide/) — Passo a passo oficial para instalar um ambiente OpenStack mínimo funcional.
- [Operations Guide](https://docs.openstack.org/operations-guide/) — O guia oficial e gratuito de operação de um cloud OpenStack em produção: arquitetura, capacidade, manutenção e troubleshooting.
- [Security Guide](https://docs.openstack.org/security-guide/) — Boas práticas oficiais de segurança para cada serviço do OpenStack.
- [Nova (computação)](https://docs.openstack.org/nova/latest/) — Documentação do serviço que gerencia máquinas virtuais e hipervisores.
- [Neutron (rede)](https://docs.openstack.org/neutron/latest/) — Documentação do serviço de redes virtuais, roteadores, firewalls e balanceamento de carga.
- [Cinder (armazenamento em bloco)](https://docs.openstack.org/cinder/latest/) — Documentação do serviço de volumes persistentes.
- [Swift (armazenamento de objetos)](https://docs.openstack.org/swift/latest/) — Documentação do serviço de object storage, equivalente ao S3 dentro do OpenStack.
- [Glance (imagens)](https://docs.openstack.org/glance/latest/) — Documentação do serviço que cataloga e distribui imagens de disco para as instâncias.
- [Keystone (identidade)](https://docs.openstack.org/keystone/latest/) — Documentação do serviço de autenticação e autorização usado por todos os outros componentes.
- [Heat (orquestração)](https://docs.openstack.org/heat/latest/) — Documentação do serviço de orquestração via templates, equivalente ao CloudFormation.
- [Horizon (painel clássico)](https://docs.openstack.org/horizon/latest/) — Documentação do painel web tradicional do OpenStack.
- [Skyline (painel novo)](https://docs.openstack.org/skyline-apiserver/latest/) — Documentação do novo painel web, mais rápido, que vem substituindo o Horizon.
- [Documentação em português (docs.openstack.org/pt_BR)](https://docs.openstack.org/pt_BR/) — Página oficial de tradução para PT-BR; hoje é sobretudo um convite para voluntários, então a maior parte do conteúdo detalhado ainda está em inglês.
- [OpenStack (Wikipédia em português)](https://pt.wikipedia.org/wiki/OpenStack) — Visão geral enciclopédica do projeto, história e arquitetura, em português.
- [OpenStack (English Wikipedia)](https://en.wikipedia.org/wiki/OpenStack) — Versão em inglês, mais detalhada e atualizada com frequência.

## 🔤 Sites e cursos para aprender OpenStack

> Cursos e tutoriais para aprender OpenStack em Português

- [OpenStack: a solução de nuvem flexível e personalizável (Alura)](https://www.alura.com.br/artigos/openstack) — Artigo gratuito que explica o que é OpenStack, por que usá-lo e como ele se compara a AWS e Azure.
- [Instalando OpenStack no CentOS 7 (Viva o Linux)](https://www.vivaolinux.com.br/dica/Instalando-Openstack-no-CentOS-7) — Tutorial de instalação passo a passo escrito pela comunidade brasileira.
- [DevStack: instale um ambiente OpenStack (Viva o Linux)](https://www.vivaolinux.com.br/dica/DevStack-instale-um-ambiente-Openstack) — Como subir um ambiente OpenStack de desenvolvimento e testes em uma única máquina usando o DevStack.
- [Palestra "Do Zero ao OpenStack" (Viva o Linux, vídeo)](https://www.vivaolinux.com.br/dica/Palestra-do-Zero-ao-Openstack-video) — Palestra em português apresentando os conceitos do OpenStack para quem nunca usou.

> Cursos para aprender OpenStack em Inglês

- [OpenStack Administration: Control Plane Management (Coursera / Red Hat)](https://www.coursera.org/learn/openstack-administration-control-plane-management) — Curso introdutório da Red Hat sobre administração do control plane do OpenStack.
- [Cloudification 101 - OpenStack](https://www.cloudification.io/) — Curso introdutório sobre conceitos e operação básica do OpenStack. Curso pago.
- [Treinamentos OpenStack da Mirantis](https://mirantis.com/training/) — Trilha OS100 (fundamentos), OS220 e OS250 (administração, preparatórios para a certificação COA). Cursos pagos.
- [Treinamento OpenStack da Canonical](https://ubuntu.com/openstack) — Cursos de fundamentos, deploy e operação avançada do Charmed OpenStack, a distribuição da Canonical. Cursos pagos.
- [Treinamentos da Cleura](https://www.cleura.com/) — Provedora nórdica de nuvem OpenStack com cursos de API/CLI e operação. Cursos pagos.
- [Treinamentos da StackHPC](https://www.stackhpc.com/) — Workshops avançados de operação de OpenStack em ambientes de alta performance (HPC/GPU). Cursos pagos.
- [Certified OpenStack Administrator / OpenStack Integrator / Solution Architect (C-DAC)](https://www.cdac.in/index.aspx?id=training) — Trilha de cursos indiana, do básico ao avançado, com preparação para certificação. Cursos pagos.

## 📚 Livros

- [OpenStack Operations Guide](https://openlibrary.org/works/OL37111321W) — Livro oficial e gratuito escrito pela comunidade, cobrindo da arquitetura à operação em produção; também disponível em [docs.openstack.org/operations-guide](https://docs.openstack.org/operations-guide/).
- [Learning OpenStack Networking, 3ª edição (James Denton)](https://openlibrary.org/works/OL19544439W) — A referência mais usada sobre o Neutron, o serviço de redes. Livro pago.
- [OpenStack Cloud Computing Cookbook, 4ª edição (Kevin Jackson, Cody Bunch, Egle Sigler, James Denton)](https://openlibrary.org/works/OL19542549W) — Receitas práticas cobrindo instalação, operação e automação do OpenStack. Livro pago.
- [Mastering OpenStack, 2ª edição (Omar Khedher, Chandan Dutta Chowdhury)](https://openlibrary.org/works/OL19543064W) — Foco em projetar e operar clouds OpenStack de médio a grande porte. Livro pago.
- [OpenStack Swift (Joe Arnold)](https://openlibrary.org/works/OL19547391W) — Livro dedicado ao serviço de armazenamento de objetos Swift: uso, administração e desenvolvimento. Livro pago.

## 🎥 Canais no Youtube

- [OpenInfra Foundation](https://www.youtube.com/@OpenInfraFoundation) — Canal oficial da fundação que mantém o OpenStack: gravações de summits, PTGs e webinars técnicos.
- [OpenStack (canal oficial)](https://www.youtube.com/@openstack) — Canal do próprio projeto, com vídeos institucionais e técnicos.
- [RDO Project](https://www.youtube.com/@RDOproject) — Canal da distribuição comunitária do OpenStack para CentOS/RHEL, com webinars de operação.
- [Canonical](https://www.youtube.com/@canonical) — Vídeos sobre o Charmed OpenStack e a operação de nuvens privadas com ferramentas da Canonical.
- [StackHPC](https://www.youtube.com/@StackHPC) — Palestras e demonstrações técnicas avançadas sobre operação de OpenStack em ambientes de HPC.

## 🛠️ Ferramentas

> Instalar e operar um cloud OpenStack

- [DevStack](https://docs.openstack.org/devstack/latest/) — Script oficial para subir um OpenStack completo em uma única máquina, para aprender e testar.
- [Kolla-Ansible](https://docs.openstack.org/kolla-ansible/latest/) — Deploy do OpenStack inteiro em containers Docker, orquestrado por Ansible; o método mais usado hoje em produção.
- [OpenStack-Ansible](https://docs.openstack.org/openstack-ansible/latest/) — Deploy do OpenStack usando containers LXC e Ansible, alternativa ao Kolla.
- [Kayobe](https://docs.openstack.org/kayobe/latest/) — Automação de ponta a ponta (bare metal + Kolla-Ansible) mantida pela StackHPC.
- [Charmed OpenStack (Canonical)](https://ubuntu.com/openstack) — Distribuição da Canonical baseada em Juju charms, com suporte comercial.
- [MicroStack](https://microstack.run/) — OpenStack empacotado como snap, para instalar em minutos em uma única máquina.
- [RDO Project](https://www.rdoproject.org/) — Distribuição comunitária do OpenStack para Red Hat Enterprise Linux, CentOS Stream e derivados.
- [Packstack](https://github.com/openstack/packstack) — Instalador simples baseado em Puppet, útil para provas de conceito rápidas em cima do RDO.

> Rodar OpenStack sobre Kubernetes (o rumo mais recente do projeto)

- [OpenStack K8s Operators](https://github.com/openstack-k8s-operators) — Operadores Kubernetes oficiais para instalar e operar o OpenStack rodando sobre um cluster Kubernetes.
- [VEXXHOST Atmosphere](https://github.com/vexxhost/atmosphere) — Distribuição open source que empacota o OpenStack inteiro como operadores Kubernetes, com [documentação própria](https://vexxhost.github.io/atmosphere/).
- [Red Hat OpenStack Services on OpenShift (RHOSO)](https://www.redhat.com/en/technologies/linux-platforms/openstack-platform) — Arquitetura da Red Hat que roda os serviços do OpenStack como cargas de trabalho dentro do OpenShift/Kubernetes.

> SDKs, CLI e automação

- [python-openstackclient](https://pypi.org/project/python-openstackclient/) — Cliente de linha de comando oficial e unificado para todos os serviços.
- [OpenStack SDK (Python)](https://docs.openstack.org/openstacksdk/latest/) — Biblioteca Python oficial para automatizar o OpenStack.
- [Gophercloud](https://github.com/gophercloud/gophercloud) — SDK do OpenStack para Go.
- [Terraform Provider for OpenStack](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest) — Provedor oficial da comunidade para provisionar infraestrutura OpenStack como código com Terraform.
- [Coleção openstack.cloud para Ansible](https://galaxy.ansible.com/ui/repo/published/openstack/cloud/) — Módulos oficiais do Ansible para automatizar recursos do OpenStack.

> Integração com Kubernetes e multi-cloud

- [cloud-provider-openstack](https://github.com/kubernetes/cloud-provider-openstack) — Implementação oficial do Kubernetes Cloud Controller Manager para rodar clusters Kubernetes sobre OpenStack.
- [Calico](https://github.com/projectcalico/calico) — Rede e política de rede para Kubernetes e OpenStack lado a lado.
- [Cloudpods](https://github.com/yunionio/cloudpods) — Plataforma open source que unifica a gestão de OpenStack, AWS, Azure e outras nuvens em um só painel.
- [ManageIQ](https://github.com/ManageIQ/manageiq) — Plataforma open source de gestão multi-cloud com suporte nativo a OpenStack.
- [StarlingX](https://www.starlingx.io/) — Distribuição para edge computing e computação distribuída construída em cima do OpenStack.

## 🧪 Projetos práticos e desafios

- [devops-exercises](https://github.com/bregman-arie/devops-exercises) — Banco de exercícios e perguntas de entrevista sobre DevOps/SRE com uma seção dedicada a OpenStack.
- [openstack-ansible-ops](https://github.com/openstack/openstack-ansible-ops) — Repositório oficial com playbooks e labs de exemplo para praticar deploy e operação com OpenStack-Ansible.
- [Nuvem pública da OVHcloud](https://www.ovhcloud.com/en/public-cloud/) — Nuvem pública comercial construída sobre OpenStack; pratique a API e o CLI do OpenStack sem montar seu próprio datacenter.
- [Nuvem pública da VEXXHOST](https://vexxhost.com/) — Outra nuvem pública compatível com as APIs do OpenStack, boa opção para testar o `python-openstackclient` de verdade.

## 🤖 IA na prática

OpenStack é operado majoritariamente por linha de comando, YAML e templates Heat/Ansible — exatamente o tipo de texto estruturado em que assistentes de IA se saem bem. Use isso a seu favor, sem terceirizar o entendimento do que está rodando no seu cluster.

**Para aprender**
- Cole a saída de um comando como `openstack server list` ou `openstack network list` e peça para a IA explicar o que cada coluna significa e o que fazer em seguida.
- Peça para gerar um template Heat (HOT) simples — por exemplo, "uma rede, um roteador e uma instância" — e valide linha a linha comparando com a [documentação do Heat](https://docs.openstack.org/heat/latest/).
- Peça exercícios comparando conceitos do OpenStack com o equivalente em outra nuvem que você já conhece (ex.: "o que é o Neutron comparado a uma VPC da AWS?").

**Para trabalhar**
- Use o [GitHub Copilot](https://github.com/features/copilot), o [Cursor](https://cursor.com/) ou o [Claude Code](https://code.claude.com/docs/en/overview) para escrever e revisar playbooks de [Kolla-Ansible](https://docs.openstack.org/kolla-ansible/latest/) ou [OpenStack-Ansible](https://docs.openstack.org/openstack-ansible/latest/), gerar templates Heat e depurar arquivos de configuração dos serviços (Nova, Neutron, Cinder).
- O [Ansible Lightspeed](https://www.redhat.com/en/technologies/management/ansible/ansible-lightspeed) sugere trechos de playbook Ansible direto no editor — útil para quem automatiza deploys do OpenStack com Ansible.
- Para construir automações e agentes que conversam com a API do OpenStack, uma IA pode ajudar a escrever a integração usando o [OpenStack SDK (Python)](https://docs.openstack.org/openstacksdk/latest/) ou o [Terraform Provider for OpenStack](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest); o [Model Context Protocol](https://modelcontextprotocol.io/) é o padrão emergente para conectar esse tipo de ferramenta diretamente a um assistente de IA.
- Depois de qualquer sugestão aceita, rode o comando primeiro em um ambiente de teste (um [DevStack](https://docs.openstack.org/devstack/latest/) local, por exemplo) antes de aplicar em produção — erros em Nova, Neutron ou Cinder afetam VMs e dados reais de outras pessoas.

**Limites e boas práticas**
- IA erra flags e nomes de parâmetros do CLI `openstack`, principalmente entre versões diferentes: o comportamento muda a cada release semestral, hoje na 2026.1 "Gazpacho". Confirme sempre na [documentação oficial](https://docs.openstack.org/).
- Nunca cole credenciais, arquivos `clouds.yaml` ou tokens do Keystone em ferramentas de IA sem política explícita da sua empresa.
- Templates Heat e playbooks gerados por IA podem criar ou destruir recursos reais (VMs, volumes, redes). Revise o `diff` e rode primeiro em um ambiente de teste antes de aplicar em produção.

## 💼 Carreira e vagas

OpenStack é procurado principalmente em vagas de infraestrutura, SRE e engenharia de nuvem privada — operadoras de telecom (NFV/5G), bancos, universidades e provedores de nuvem que não querem depender de um único hyperscaler. É comum aparecer como requisito ao lado de Linux, Kubernetes, Ansible e Terraform.

- [OpenStack User Survey](https://www.openstack.org/user-survey/) — Pesquisa oficial e periódica sobre quem usa OpenStack, em que escala e para quê; boa leitura para entender onde as vagas existem.
- [Flexera State of the Cloud Report](https://info.flexera.com/CM-REPORT-State-of-the-Cloud) — Relatório anual que mede a adoção de nuvem privada e híbrida nas empresas, incluindo OpenStack.
- [Stack Overflow Developer Survey 2025](https://survey.stackoverflow.co/2025/) — Panorama anual de tecnologias, salários e tendências no mercado de tecnologia.
- [Vagas com "openstack" no Programathor](https://programathor.com.br/jobs?query=openstack) — Vagas de tecnologia no Brasil filtradas pelo termo OpenStack.
- [GeekHunter](https://www.geekhunter.com.br/) — Plataforma brasileira onde empresas fazem propostas a profissionais de infraestrutura e cloud.
- [Coodesh](https://coodesh.com/) — Vagas tech no Brasil com processos seletivos padronizados.
- [Remotar](https://remotar.com.br/) — Vagas 100% remotas para brasileiros, incluindo infraestrutura e DevOps.
- [Vagas de OpenStack no InfoJobs](https://www.infojobs.com.br/vagas-de-emprego-openstack.aspx) — Busca de vagas filtrada por OpenStack no Brasil.

## 👥 Comunidades

- [Ask OpenStack](https://ask.openstack.org/) — Fórum de perguntas e respostas oficial da comunidade, no estilo Stack Overflow.
- [OpenInfra Superuser](https://superuser.openinfra.org/) — Publicação oficial da comunidade com estudos de caso, novidades e entrevistas.
- [OpenInfra Foundation](https://www.openinfra.dev/) — Site da fundação sem fins lucrativos que mantém o OpenStack e outros projetos de infraestrutura aberta.
- [OpenStack no Matrix](https://matrix.to/#/#openstack:matrix.org) — Sala oficial de chat em tempo real da comunidade (sucessora do IRC).
- [Como participar por IRC/Matrix](https://docs.openstack.org/contributors/common/irc.html) — Guia oficial dos canais de chat usados por cada equipe de desenvolvimento.
- [Grupos de Meetup sobre OpenStack](https://www.meetup.com/topics/openstack/) — Encontros presenciais e online sobre o tema ao redor do mundo.
- [OpenStack Brasil (Meetup)](https://www.meetup.com/openstack-brasil/) — Comunidade brasileira, com mais de 1.400 membros, reunindo empresas, usuários e estudantes do projeto.
- [OpenStack Brasil (Google Groups)](https://groups.google.com/g/openstack-brasil) — Lista de discussão histórica da comunidade brasileira, com dúvidas técnicas reais trocadas entre usuários.
- [Time de tradução para português](https://translate.openstack.org/) — Onde qualquer pessoa pode contribuir traduzindo a documentação e a interface do OpenStack para PT-BR.
- [OpenInfra Foundation no X/Twitter](https://x.com/OpenInfraFdn) — Canal oficial de notícias e anúncios da fundação.
- [Organização OpenStack no GitHub](https://github.com/openstack) — Espelho oficial (somente leitura) de todos os repositórios de código do projeto.

## 🎓 Certificações

- [Certified OpenStack Administrator (COA)](https://www.openstack.org/coa/) — A certificação oficial da OpenInfra Foundation, com exame prático administrado pela Mirantis; comprova a capacidade de operar um cluster OpenStack no dia a dia.

Além da COA, alguns dos treinamentos pagos listados acima (Mirantis OS220/OS250, C-DAC) já são desenhados como preparação direta para esse exame — vale considerá-los se o seu objetivo é a certificação, não apenas aprender o básico.
