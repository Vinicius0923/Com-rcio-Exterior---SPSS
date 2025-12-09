### 📊 Projeto de Análise de Comércio Exterior (SPSS)

Este repositório contém scripts em **SPSS Syntax** para importar, tratar e recodificar dados de exportações brasileiras a partir de arquivos CSV.
---

### 📂 Estrutura do Projeto

- `EXP_2023.csv` → Arquivo de dados de exportações (delimitado por `;`).
- `script.sps` → Código SPSS para:
  - Importar dados
  - Filtrar registros
  - Recodificar variáveis
  - Criar variáveis derivadas
---

### 🚀 Funcionalidades

- **Importação de dados**: leitura de arquivo CSV delimitado por `;`.
- **Filtro temporal**: seleção de registros com `CO_ANO >= 2000`.
- **Recodificação de estados**:
  - Criação da variável `Estados` com foco em unidades da Neoenergia.
  - Criação da variável `UF` com códigos numéricos para todas as UFs.
- **Variáveis binárias**:
  - `Bahia`, `DF`, `PE` → variáveis dummy para análises específicas.
---

### 🛠 Requisitos

- **SPSS Statistics** (versão 25 ou superior recomendada)
- Arquivo de dados `EXP_2023.csv` no diretório especificado:
---

### ▶️ Como Executar

1. Abra o **SPSS Statistics**.
2. Carregue o script `.sps`:
 - `File > Open > Syntax`
3. Ajuste o caminho do arquivo CSV se necessário.
4. Execute o script (`Run > All`).
---

### 📜 Principais Variáveis

| Variável   | Descrição                          |
|------------|------------------------------------|
| `CO_ANO`   | Ano da exportação                  |
| `CO_MES`   | Mês da exportação                  |
| `CO_NCM`   | Código NCM                         |
| `CO_PAIS`  | País de destino                    |
| `SG_UF_NCM`| Unidade da Federação (sigla)       |
| `Estados`  | Recodificação para Neoenergia      |
| `UF`       | Código numérico das UFs            |
| `Bahia`    | Dummy para BA                      |
| `DF`       | Dummy para DF                      |
| `PE`       | Dummy para PE                      |

---

### 🤝 Contribuição

Contribuições são bem-vindas!  
Sugestões de melhorias podem ser feitas via **Issues** ou **Pull Requests**.
---

### 📜 Licença

Este projeto está sob a licença MIT.  
Veja o arquivo [LICENSE](LICENSE) para mais detalhes
---

