# 📊 E-commerce Analytics: Desempenho de Vendedores e GMV

Este projeto consiste em uma análise de dados de e-commerce utilizando Python e SQL (via `pandasql`). O objetivo é extrair KPIs estratégicos, como Volume Bruto de Mercadorias (GMV), ticket médio e crescimento trimestral, para identificar os melhores vendedores e o comportamento de descontos na plataforma.

## Como Executar o Projeto

Siga os passos abaixo para configurar o ambiente e rodar as análises em sua máquina:

### 1. Clonar o Repositório

```bash
git clone https://github.com/FerruccioRibeiro/FerruccioRibeiro-Tech-Challenge---Data-Engineer---FIEMG.git
cd FerruccioRibeiro-Tech-Challenge---Data-Engineer---FIEMG
```
### 2. Criar ambiente virtual

```bash
# No Windows:
python -m venv .venv
.\.venv\Scripts\activate

# No Linux/Mac:
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instalar Dependências

```bash
pip install -r requirements.txt
```

### 4. Visualizar as Análises
O projeto foi desenvolvido em um Jupyter Notebook para facilitar a visualização das tabelas e métricas.

* **Pelo VS Code (Recomendado):** Basta abrir o arquivo `resultado.ipynb`. O VS Code solicitará que você selecione o "Kernel" (o interpretador Python). Selecione o Python que está dentro da pasta `venv` que você criou.
* **Pelo Navegador:** Com o ambiente ativo, execute `jupyter notebook` e abra o arquivo `resultado.ipynb`.

> **Nota:** As células já contêm os resultados salvos (outputs), então é possível visualizar as tabelas de GMV e Crescimento mesmo sem executar o código novamente.