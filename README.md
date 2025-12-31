# 🔐 Plano de Auditoria de Data Center

Framework completo para auditoria de infraestrutura de TI, cobrindo segurança da informação, gestão de serviços e compliance com ISO 27001, ISO 20000, COBIT e NIST.

🌐 **[Visualizar Framework Online](https://markuscarneiro.github.io/plano-anual-ti/)**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![ISO 27001](https://img.shields.io/badge/ISO-27001-blue)](https://www.iso.org/isoiec-27001-information-security.html)
[![COBIT](https://img.shields.io/badge/Framework-COBIT-orange)](https://www.isaca.org/resources/cobit)
[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://markuscarneiro.github.io/plano-anual-ti/)

## 🎯 Sobre o Projeto

> **🚀 [Acesse o framework interativo](https://markuscarneiro.github.io/plano-anual-ti/)**

Framework metodológico estruturado para planejamento e execução de auditorias em ambientes de Data Center, desenvolvido com base em standards internacionais (ISO 27001, ISO 20000, COBIT, NIST, CIS Controls) e melhores práticas de auditoria de TI.

**Contexto:** Plano de auditoria para Data Center SWA, abrangendo serviços de hosting e colocation, com foco em confidencialidade, integridade e disponibilidade (Tríade CIA).

### Aplicabilidade

Este framework pode ser utilizado/adaptado para:
- Auditorias internas de infraestrutura de TI
- Avaliações de compliance (ISO 27001, SOC 2, PCI-DSS)
- Due diligence técnica em aquisições
- Preparação para auditorias externas
- Avaliação de fornecedores de cloud/hosting

## 📋 Conteúdo do Framework

### Estrutura Metodológica (9 Etapas)

1. **Identificação dos Riscos**
   - Análise da Tríade CIA (Confidencialidade, Integridade, Disponibilidade)
   - Mapeamento de ameaças e vulnerabilidades
   - Priorização por criticidade

2. **Definição dos Critérios de Avaliação**
   - ISO 27001 (Gestão da Segurança da Informação)
   - ISO 20000 (Gestão de Serviços de TI)
   - COBIT (Governança e gestão de TI)
   - NIST Cybersecurity Framework
   - CIS Controls
   - LGPD (Lei Geral de Proteção de Dados)

3. **Planejamento da Auditoria**
   - Reunião de abertura e alinhamento
   - Coleta de documentação prévia
   - Definição de amostras e escopo detalhado

4. **Definição dos Objetivos**
   - Garantir proteção de dados (confidencialidade/integridade)
   - Assegurar alta disponibilidade e performance
   - Verificar diversificação de soluções

5. **Definição do Escopo**
   - Gestão de Configuração
   - Gestão de Mudança/Implantação
   - Monitoração do Ambiente
   - Backup e Recuperação

6. **Coleta de Informações**
   - Mapeamento de serviços e infraestrutura
   - Levantamento de processos de negócio
   - Análise de contexto organizacional

7. **Execução da Auditoria**
   - Entrevistas com gestores e operadores
   - Testes de controles técnicos
   - Observação de processos operacionais
   - Análise de logs e evidências

8. **Consolidação e Relatório**
   - Análise de evidências
   - Identificação de não conformidades
   - Classificação por criticidade

9. **Entregáveis**
   - Plano de Auditoria detalhado
   - Papéis de trabalho
   - Matriz de riscos e controles
   - Relatório executivo
   - Plano de ação

## 🛠️ Frameworks e Normas Aplicados

### Segurança da Informação
- **ISO/IEC 27001:2022** - Sistema de Gestão de Segurança da Informação
- **NIST CSF** - Cybersecurity Framework (Identify, Protect, Detect, Respond, Recover)
- **CIS Controls** - Controles de segurança críticos

### Gestão de TI
- **ISO/IEC 20000** - Gestão de Serviços de TI
- **COBIT 2019** - Governança e Gestão de TI corporativa
- **ITIL v4** - Práticas de gerenciamento de serviços

### Compliance
- **LGPD** - Lei Geral de Proteção de Dados (Brasil)
- **SOC 2** - Service Organization Control (preparação)

## 📊 Áreas de Controle Auditadas

```
┌─────────────────────────────────────────┐
│  SEGURANÇA FÍSICA                       │
│  - Controle de acesso físico            │
│  - Monitoramento por câmeras            │
│  - Proteção ambiental (clima/energia)   │
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│  SEGURANÇA LÓGICA                       │
│  - Controles de acesso (IAM)            │
│  - Criptografia de dados                │
│  - Segmentação de rede                  │
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│  GESTÃO DE MUDANÇAS                     │
│  - Processos de aprovação               │
│  - Testes e validação                   │
│  - Rollback e contingência              │
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│  BACKUP E CONTINUIDADE                  │
│  - Políticas de backup                  │
│  - Testes de recuperação                │
│  - Plano de Continuidade de Negócios    │
└─────────────────────────────────────────┘
```

## 🚀 Como Utilizar

### Visualização Online (Recomendado)

Acesse: **[https://markuscarneiro.github.io/plano-anual-ti/](https://markuscarneiro.github.io/plano-anual-ti/)**

### Download e Uso Local

```bash
# Clone o repositório
git clone https://github.com/markuscarneiro/plano-anual-ti.git

# Abra o arquivo HTML
cd plano-anual-ti
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Customização para Seu Contexto

O framework pode ser adaptado modificando:
1. **Riscos específicos** - Ajuste conforme perfil de risco da organização
2. **Critérios de avaliação** - Adicione normas específicas do setor
3. **Escopo** - Inclua/exclua processos conforme necessidade
4. **Cronograma** - Adapte prazos à complexidade do ambiente

## 📈 Cronograma de Execução

| Fase | Atividades | Duração | Responsável |
|------|-----------|---------|-------------|
| **Preparação** | Etapas 1-6 (Planejamento completo) | 1 semana | Auditor Líder |
| **Fieldwork** | Etapa 7 (Execução dos trabalhos) | 3 semanas | Equipe de Auditoria |
| **Reporting** | Etapas 8-9 (Consolidação e relatório) | 1 semana | Auditor Líder |

**Duração total:** 5 semanas (35 dias úteis)

## 🎓 Competências Demonstradas

Este projeto evidencia expertise em:

- ✅ **Auditoria de TI** - Metodologia estruturada de auditoria
- ✅ **Frameworks Internacionais** - ISO 27001, COBIT, NIST, CIS
- ✅ **Gestão de Riscos** - Identificação e avaliação de riscos de TI
- ✅ **Compliance** - LGPD, normas setoriais e internacionais
- ✅ **Segurança da Informação** - Tríade CIA aplicada
- ✅ **Gestão de Infraestrutura** - Data Centers e cloud computing
- ✅ **Documentação Técnica** - Elaboração de frameworks e metodologias

## 💼 Aplicações Práticas

### Para Auditores Internos
- Template pronto para auditorias de infraestrutura
- Checklist de verificação de controles
- Referência de melhores práticas

### Para Gestores de TI
- Framework de auto-avaliação
- Guia para preparação de auditorias externas
- Baseline de controles essenciais

### Para Consultores
- Estrutura para assessorias de compliance
- Base para propostas técnicas
- Demonstração de metodologia

## 🔍 Diferenciais Técnicos

- **Multidisciplinar** - Combina segurança, governança e operações
- **Baseado em Standards** - Alinhado com normas internacionais
- **Prático** - Foco em execução, não apenas teoria
- **Escalável** - Adaptável a diferentes portes de infraestrutura
- **Compliance-Ready** - Cobre principais frameworks regulatórios

## 📚 Referências Bibliográficas

- ISO/IEC 27001:2022 - Information Security Management
- ISO/IEC 20000-1:2018 - IT Service Management
- COBIT 2019 Framework - ISACA
- NIST Cybersecurity Framework v1.1
- CIS Controls v8
- LGPD - Lei 13.709/2018

## 📄 Licença

Este framework é disponibilizado sob licença MIT para fins educacionais e profissionais.

## 👤 Autor

**Markus Carneiro**

Senior Internal Auditor | IT Audit & Data Science Specialist

- 💼 LinkedIn: [linkedin.com/in/markuscarneiro](https://linkedin.com/in/markuscarneiro)
- 🐙 GitHub: [@markuscarneiro](https://github.com/markuscarneiro)
- 📧 Contato: [Disponível no LinkedIn]

### Credenciais
- 19 anos de experiência em auditoria
- AUDI TI (IIA Brasil)
- Especialização em Python, SAP, Snowflake
- Mestrado em Energia e Ambiente (UFMA)

### Sobre este framework
Desenvolvido com base em experiência real em auditorias de infraestrutura de TI em empresas de energia e utilities, combinando conhecimento técnico profundo com expertise em compliance e governança.

---

⭐ **Útil para seu trabalho?** Deixe uma estrela!

💬 **Sugestões de melhorias?** Abra uma [issue](https://github.com/markuscarneiro/plano-anual-ti/issues)

🤝 **Quer colaborar?** Pull requests são bem-vindos para expandir o framework!

📖 **Cite este trabalho:** Se utilizar em apresentações ou relatórios, credite o autor.
