# F-nix EngCalculus-Pro 🏗️
### Sistema Integrado de Quantitativo de Materiais e Controle Permanente
**Fênix Engenharia e Comércio LTDA**

Este é um aplicativo web 100% gratuito, leve e de código aberto, projetado para automatizar o levantamento quantitativo de materiais de engenharia diretamente pelo navegador. Desenvolvido para centralizar fluxos de trabalho e medições técnicas sem a necessidade de infraestruturas de servidores pagas, utilizando o próprio GitHub como hospedagem e banco de dados permanente.

---

## 🔗 Endereço de Acesso Direto
O aplicativo está publicado e pronto para uso no celular ou computador através do link do GitHub Pages:
👉 [https://github.io](https://github.io)

*Nota: O endereço do sistema diferencia letras maiúsculas de minúsculas. Certifique-se de acessar respeitando as maiúsculas de `F`, `E` e `P`.*

---

## 🛠️ Recursos Principais do Sistema

### 1. Modos de Cálculo Flexíveis
*   **m² Global da Casa Inteira:** Permite realizar estimativas macro de insumos inserindo a área total da edificação baseada em índices de consumo global.
*   **Detalhado por Cômodo Individual:** Permite que a equipe faça o levantamento fracionado ambiente por ambiente (ex: Quarto 1, Banheiro Suíte), inserindo as metragens específicas e acumulando os dados organizadamente.

### 2. Categorias Técnicas Integradas
O motor de cálculo está pré-configurado e atende de ponta a ponta as seguintes disciplinas da construção civil:
*   **Construção Civil** (Tijolos, cimento, agregados, blocos estruturais)
*   **Elétrica** (Cabos flexíveis de 2.5mm² a 16mm², disjuntores, infraestrutura)
*   **Rede** (Cabeamento estruturado Cat6, keystones, conectores)
*   **Gás** (Tubulações de cobre, reguladores GLP)
*   **Hidráulica** (Tubos soldáveis de água fria, tubos de esgoto predial)
*   **TV** (Cabos coaxiais digitais, divisores de sinal)

### 3. Gestão Interna Integrada
*   **Cadastro de Materiais:** Permite incluir novos insumos e configurar o consumo base de referência por m² ou ponto fixo.
*   **Equipe & RTs:** Controle de Responsáveis Técnicos assinando as medições com seus respectivos registros profissionais (CREA/CFT).
*   **Cadastro de Clientes:** Vinculação inteligente de múltiplos lotes, condomínios ou reformas comerciais ao histórico de cálculos.

---

## 📂 Estrutura Física do Repositório

O projeto funciona de maneira estática e descentralizada utilizando os seguintes arquivos locais:

*   `index.html`: Arquivo central da aplicação. Contém a interface do usuário (Tailwind CSS), o motor matemático e os scripts de interação.
*   `materiais.json`: Banco de dados fixo com o catálogo técnico de insumos e fatores de consumo padrão.
*   `funcionarios.json`: Registro de engenheiros, encarregados e prestadores de serviço autorizados.
*   `clientes.json`: Listagem permanente de contratos, proprietários e endereços de obras.
*   `historico.json`: Arquivo de logs que armazena as saídas de cálculos e estimativas com margens de perda geradas em campo.

---

## 💡 Como Atualizar a Base de Dados Fixa
Como o aplicativo roda 100% no navegador (Client-Side), os novos cadastros efetuados em tela geram blocos estruturados de texto. Para salvá-los de forma definitiva, basta abrir o arquivo `.json` correspondente aqui no repositório do GitHub e colar os novos blocos gerados dentro dos colchetes principais `[]`.
