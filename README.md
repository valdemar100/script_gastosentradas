# script_gastosentradas
Um script criado pra calcular meus gastos e entradas, gera uma planilha no excel e mostra os valores de entrada e gasto na propria interface, logo estarei adicionando uma versão onde poderá ser vizualizado o saldo total do dia 

# 💰 Controle de Gastos Diários – Python com Tkinter e Excel

Este projeto é uma aplicação simples em Python com interface gráfica para registrar entradas e gastos do dia a dia. Os dados são armazenados em um arquivo `.xlsx` (Excel), permitindo o controle financeiro pessoal de forma prática.

---

## 📸 Interface

<img src="![image](https://github.com/user-attachments/assets/25d65ee2-2a74-48ce-b06d-336a47f267af)
" alt="![Captura de tela 2025-06-03 203821](https://github.com/user-attachments/assets/9425451b-dc3c-4967-8a4d-5e68e3a2839c)
" width="300"/>

---

## 🧰 Funcionalidades

- Registro diário de:
  - 📅 Data
  - 📝 Descrição
  - 💸 Tipo (Entrada ou Gasto)
  - 💲 Valor
- Armazenamento automático em um arquivo `gastos.xlsx`
- Cálculo e exibição dos totais de entradas e gastos
- Validação de formato de data e valor
- Interface gráfica com `Tkinter`

---

## 📦 Requisitos

- Python 3.x
- Biblioteca `openpyxl` (instalação abaixo)

```bash
pip install openpyxl

▶️ Como executar
1 Clone o repositório ou baixe o arquivo controle_gastos.py

2 Execute com o Python:
python controle_gastos.py

3 A primeira execução criará o arquivo gastos.xlsx automaticamente.

📝 Como usar
1 Preencha a Data no formato DD/MM/AAAA

2 Descreva o gasto ou entrada no campo "Descrição"

3 Selecione o tipo (Entrada ou Gasto)

4 Digite apenas o valor numérico (exemplo: 8.50)

5 Clique em "Enviar" para salvar o registro

6 Clique em "Ver saldo total" para visualizar o total de entradas e gastos acumulados

📁 Estrutura do Excel
Data	Descrição	Tipo	Valor

03/06/2025	café	Gasto	8.00

03/06/2025	salário extra	Entrada	1200.00

🚀 Melhorias futuras 

Exportação de relatório em PDF

Filtros por mês e ano

Gráficos com matplotlib

Histórico mensal

Interface mais moderna com ttkbootstrap ou PyQt

👤 Autor
Desenvolvido por [Valdemar]
💬 Para sugestões ou melhorias, abra uma issue ou envie um pull request!


