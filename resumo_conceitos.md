### Resumo das Fontes

As fontes abordam **conceitos básicos de nuvem** e **como criar uma Instância Gerenciada de SQL do Azure**.

---

### Conceitos de Nuvem

- O módulo 1 do curso AZ-900 cobre conceitos de nuvem.
- Tópico chave: **Tipos de serviço de nuvem**: IaaS, PaaS e SaaS.
- Inclui:
  - Descrição dos modelos IaaS, PaaS e SaaS.
  - Modelo de responsabilidade compartilhada.
  - Casos de uso apropriados para cada tipo de serviço.

---

### Tipos de Serviço de Nuvem

- **IaaS (Infraestrutura como Serviço)**:
  - Criação de infraestrutura de TI sob demanda.
  - Exemplo: aluguel de VMs, redes e armazenamento.
  - Flexibilidade total sobre o ambiente.

- **PaaS (Plataforma como Serviço)**:
  - Ambiente de desenvolvimento e implantação de apps.
  - Sem necessidade de gerenciar a infraestrutura.

- **SaaS (Software como Serviço)**:
  - Uso de aplicativos via internet.
  - Exemplo: Microsoft 365, email e calendários.
  - Pagamento por uso ou assinatura.

---

### Modelo de Responsabilidade Compartilhada

- **Cliente**: sempre responsável por dados, dispositivos e identidades.
- **Responsabilidade varia** conforme o serviço:
  - SaaS, PaaS, IaaS — diferentes níveis de controle do cliente.
- **Provedor de nuvem (ex: Microsoft)**: responsável por hosts físicos, rede e datacenter.

---

### Criar uma Instância Gerenciada de SQL do Azure

- Guia de início rápido disponível.
- Métodos: **Portal do Azure, PowerShell ou CLI do Azure**.
- Pré-requisitos:
  - Assinatura do Azure.
  - Módulo Az.SQL ou CLI atualizados.
  - Permissões adequadas.

- **Teste gratuito disponível**: 720 horas de vCore por 12 meses (instância Uso Geral).

- **Cancelamento da implantação**: possível via Portal, PowerShell, CLI ou API REST.

---

### Passos para Criar no Portal do Azure

1. Entrar no portal do Azure.
2. Ir em **SQL do Azure** no menu esquerdo.
3. Selecionar **+ Criar**.
4. Escolher **Instância única** e clicar em **Criar**.
5. Preencher a guia **Básico** (nome, região, autenticação, etc.).
6. Configurar **Computação + armazenamento**:
   - Camada de serviço, geração do hardware, vCores, armazenamento, licença.
7. Configurar a guia **Rede** (rede virtual, ponto de extremidade público).
8. Manter valores padrão na guia **Segurança**.
9. Opcional: configurar a guia **Configurações adicionais** (fuso horário, replicação, etc.).
10. Adicionar **Tags** (marcas) para organização e relatórios.
11. Revisar e clicar em **Criar**.

---

### Pós-Implantação

- **Monitoramento**:
  - Via notificações do portal ou página da instância.
  - Verificar configurações de rede (roteamento, segurança).

- **Criar banco de dados**:
  - Ir à instância e selecionar **+ Novo banco de dados**.
  - Definir nome e fonte de dados (vazio ou backup).

- **Conexão com a instância**:
  - Recuperar FQDN (nome de domínio totalmente qualificado) na aba de visão geral.

---
