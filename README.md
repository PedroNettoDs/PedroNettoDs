<p align="center">
  <img src="assets/header.svg" width="100%" alt="Pedro Netto — Analista de Infraestrutura II e fundador da AttanoTech. Infraestrutura que pensa — e roda local." />
</p>

<p align="center">
  <a href="https://nettotech.com.br"><img src="assets/links/site.svg" height="34" alt="nettotech.com.br" /></a>
  <a href="https://www.linkedin.com/in/pedronettods/"><img src="assets/links/linkedin.svg" height="34" alt="LinkedIn" /></a>
  <a href="https://youtube.com/@MrNetto"><img src="assets/links/youtube.svg" height="34" alt="YouTube" /></a>
  <a href="https://nettotecnologias.blogspot.com/"><img src="assets/links/blog.svg" height="34" alt="Blog" /></a>
  <a href="mailto:contato@nettotech.com.br"><img src="assets/links/email.svg" height="34" alt="E-mail" /></a>
</p>

### `$ whoami`

Sou **Pedro Netto**, de Bauru/SP. Mantenho infraestrutura de pé como **Analista de Infraestrutura II na Paschoalotto**: incidentes críticos via ServiceNow, mudanças (CHG) em ITIL v4, Active Directory, Microsoft 365 e FortiGate.

Fora do expediente, construo sistemas que pensam — e que rodam na minha máquina, não na nuvem dos outros. O maior deles é o **[Alfred](https://github.com/PedroNettoDs/Alfred-Pennyworth)**, meu assistente pessoal com LLMs locais. Também fundei a **AttanoTech**, onde o **[SubMAX](https://www.submax.com.br)** já roda em produção.

- Curso **Tecnologia em Redes de Computadores** na FATEC Bauru, com a trilha **CCNAv7** concluída.
- Miro em **CI/CD, LLMs e agentes, automação com Python, cloud e gestão de projetos**.
- Kubuntu é meu daily driver. Sim, vou reclamar do Windows em toda oportunidade.

<p align="center">
  <img src="assets/manifesto.svg" width="100%" alt="Manifesto em três regras: local-first, humano no circuito, tudo como código." />
</p>

### `$ ./alfred --arquitetura`

<p align="center">
  <a href="https://github.com/PedroNettoDs/Alfred-Pennyworth"><img src="assets/alfred.svg" width="100%" alt="Diagrama de arquitetura do Alfred-Pennyworth: e-mail, WhatsApp e web entram na máquina local e passam pelo Inbox Assistant, que usa Ollama, Laya, Shell Executor, Researcher, SearXNG, ChromaDB e Evolution API." /></a>
</p>

O **Alfred** é a prova do que eu defendo: um assistente que lê meu e-mail e meu WhatsApp, pesquisa na web e lembra das coisas — sem mandar nada para uma API de IA de terceiros.

- **Conversa com ferramentas** — executa comandos no host sob whitelist, faz pesquisa profunda e consulta o RAG local (SQLite FTS5 + ChromaDB).
- **E-mail** — lê o Thunderbird, monta um jornal diário das newsletters e cria pendências "vou / não vou". Uma extensão do Thunderbird redige as respostas.
- **WhatsApp** — via Evolution API, transcreve áudios localmente e pergunta *"o que você quer responder?"*. Nada sai sem a minha aprovação.
- **Laya** — classificador ModernBERT local para decisões rápidas e tipadas.
- **Painel web** para aprovar o que ele propõe, memória num vault do Obsidian e o **[Pestinha](https://github.com/PedroNettoDs/pestinha)**, um pet de tela que reage à atividade dele.

`Python` · `FastAPI` · `Ollama` · `Docker` · `systemd` · licença **AGPL-3.0**

### `$ ls ~/projetos`

<p align="center">
  <a href="https://www.submax.com.br"><img src="assets/cards/submax.svg" width="49%" alt="SubMAX — plataforma SaaS para personal trainers, em produção" /></a>
  <a href="https://github.com/PedroNettoDs/Capitaine"><img src="assets/cards/capitaine.svg" width="49%" alt="Capitaine ERP — ERP local com emissão de NF-e" /></a>
  <a href="https://github.com/PedroNettoDs/MatchNetto"><img src="assets/cards/matchnetto.svg" width="49%" alt="MatchNetto — compatibilidade entre currículo e vaga com IA" /></a>
  <a href="https://github.com/PedroNettoDs/LLM-briefing"><img src="assets/cards/briefing.svg" width="49%" alt="LLM-briefing — briefing diário de notícias em Markdown e áudio" /></a>
  <a href="https://github.com/PedroNettoDs/AlexandrIA"><img src="assets/cards/livrolocal.svg" width="49%" alt="LivroLocal — tradução de livros 100% local" /></a>
  <a href="https://github.com/PedroNettoDs/Sentt"><img src="assets/cards/sentt.svg" width="49%" alt="Sentt — motor WhatsApp multi-inquilino" /></a>
  <a href="https://github.com/PedroNettoDs/NF-e-Consolidator"><img src="assets/cards/nfe.svg" width="49%" alt="NF-e Consolidator — consolida XMLs de NF-e numa planilha" /></a>
  <a href="https://github.com/PedroNettoDs/IaC-Fileserver-Fatec"><img src="assets/cards/iac.svg" width="49%" alt="IaC Fileserver — servidor de arquivos da FATEC provisionado com Ansible" /></a>
</p>

<sub>Mais em `ls -a`: [Exchange Retention Manager](https://github.com/PedroNettoDs/Exchange-Retention-Manager) · [lab-http-https](https://github.com/PedroNettoDs/lab-http-https) · [oggtranscritor](https://github.com/PedroNettoDs/oggtranscritor) · [yTubeRaptor](https://github.com/PedroNettoDs/yTubeRaptor) · [Hub-Pessoal](https://github.com/PedroNettoDs/Hub-Pessoal)</sub>

### `$ ls ~/projetos/no-forno`

- **App nativo do SubMAX** — Flutter para iOS e Android, levando o portal do aluno para as lojas.
- **Linker** — plataforma de intermediação de serviços: NestJS + Prisma, Flutter, PostGIS e mapas OpenStreetMap próprios.
- **Oran** — mensageiro privado e self-hosted sobre Matrix, acessível só por VPN.

### `$ cat pilha.osi`

<p align="center">
  <img src="assets/pilha.svg" width="100%" alt="Pilha técnica em camadas: rede, sistemas, observabilidade, nuvem, entrega, aplicação, agentes e IA, pessoas e processo." />
</p>

**Certificações:**
[CCNA: Introduction to Networks](https://www.credly.com/badges/3dee7804-554c-4868-ba70-3f0d0a5bfea8) ·
[CCNA: Switching, Routing, and Wireless Essentials](https://www.credly.com/badges/a6d10622-e238-4ddc-a47a-ecc6c7c61935) ·
[CCNA: Enterprise Networking, Security, and Automation](https://www.credly.com/badges/883eb270-a7eb-44cb-a0f3-19a1f8cfe019) ·
[Cisco IT Essentials](https://www.credly.com/badges/866df61a-2ab3-471e-80d3-f864148e6eab) ·
[Huawei Computer Network](https://www.credly.com/badges/ac3bff27-909e-4aa5-8c35-cb0b2fa37a23) ·
[AWS Knowledge: Cloud Essentials](https://www.credly.com/badges/eaa33ec3-74e7-4784-9e60-d1fd389f5b7f)

### `$ git log --graph carreira`

<p align="center">
  <img src="assets/trajetoria.svg" width="100%" alt="Trajetória como grafo de git: KS2, Linx Sistemas, Paschoalotto, AttanoTech e FATEC." />
</p>

### `$ contato --agora`

> Quer saber como posso ser mais do que um funcionário e virar um **investimento** para a sua empresa? Então é só marcar uma conversa. Mas só vale a pena se a sua empresa realmente **exalar tecnologia** — porque é isso que eu respiro.

[nettotech.com.br](https://nettotech.com.br) · [LinkedIn](https://www.linkedin.com/in/pedronettods/) · [contato@nettotech.com.br](mailto:contato@nettotech.com.br)

<p align="center">
  <img src="assets/rodape.svg" width="100%" alt="now is better than never." />
</p>
