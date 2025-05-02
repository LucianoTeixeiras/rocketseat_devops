# 🛠️ Plano de Implementação DevOps - Empresa Fictícia TECH

## 1. Diagnóstico Cultural (C de CALMS)

**Processo escolhido:** Entrega de código e deploy.

**Descrição do processo atual:**  
Atualmente, após o desenvolvimento de um recurso, o código é empacotado manualmente pelos desenvolvedores e entregue à equipe de operações. Esta realiza o deploy e testes também de forma manual. O monitoramento pós-deploy depende da análise de logs em tempo real.

**Pontos de atrito identificados:**
- Falta de padronização nos pacotes entregues;
- Dependência da equipe de operações para cada deploy;
- Retrabalho frequente em incidentes;
- Comunicação deficiente entre devs e ops.

**Oportunidades de melhoria:**
- Adoção de pipelines CI/CD;
- Padronização do processo de build e testes;
- Feedback mais rápido sobre erros e sucesso do deploy.

---

## 2. Automação (A de CALMS)

**Solução proposta:**  
Implantação de uma pipeline automatizada com GitHub Actions para build, testes e deploy contínuo.

**Plano de implementação:**
1. Configurar pipelines CI/CD com GitHub Actions para:
   - Build e testes automatizados a cada push;
   - Deploy automatizado em staging;
   - Aprovação manual para produção.
2. Containerização das aplicações com Docker.
3. Versionamento de infraestrutura com Terraform (infraestrutura como código).
4. Treinamento das equipes para utilização da nova pipeline.

**Minimização de resistências:**
- Workshops de boas práticas DevOps;
- Suporte técnico durante transição;
- MVP da pipeline implementado inicialmente em um projeto não crítico.

---

## 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

**Métricas propostas:**
- Lead Time de desenvolvimento até produção;
- Taxa de sucesso nos deploys;
- Número de incidentes pós-deploy;
- MTTR (Mean Time to Recovery).

**Plano de compartilhamento:**
- Documentação no Confluence;
- Sessões mensais de compartilhamento de lições aprendidas;
- Reuniões de retrospectiva e melhoria contínua;
- Criação de um canal interno exclusivo sobre DevOps (ex: Slack ou Teams).

---

## 4. As Três Maneiras do DevOps

### Primeira Maneira: Acelerar o Fluxo
- Padronização dos ambientes com Docker;
- Pipelines automatizados de build e deploy;
- Remoção de dependências manuais entre etapas.

### Segunda Maneira: Ampliar o Feedback
- Testes automatizados integrados ao CI;
- Alerts com Prometheus e dashboards com Grafana;
- Canal direto de comunicação entre devs e ops.

### Terceira Maneira: Experimentar e Aprender
- Implantação gradual de novas práticas;
- Avaliações constantes de performance do time;
- Reconhecimento de falhas como parte do processo de evolução.

---

## ✅ Conclusão

Este plano propõe a modernização do fluxo de desenvolvimento da empresa TECH, eliminando gargalos e promovendo uma cultura DevOps baseada em colaboração, automação e aprendizado contínuo. A adoção das práticas propostas contribuirá para entregas mais rápidas, seguras e com maior visibilidade sobre o desempenho das aplicações.

---

> Elaborado por: **Luciano Teixeira**  
> Projeto fictício da formação **DevOps** - Rocketseat 🚀
