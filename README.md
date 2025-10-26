# Automacao_Python
# Automação de Cadastro de Produtos com Python

### Visão Geral
Este projeto demonstra uma **automação prática com Python**, criada durante o curso **Python Digital (Hashtag Treinamentos)**.  
O objetivo é mostrar como o Python pode **substituir tarefas manuais repetitivas**, automatizando o **login e cadastro de produtos** em um sistema web a partir de uma planilha CSV.

A automação foi desenvolvida com foco em **eficiência, clareza e aplicabilidade no mundo real** — ideal para profissionais que desejam explorar o poder da linguagem Python no dia a dia corporativo.

---

## Funcionalidades

✅ Abertura automática do navegador e acesso ao sistema da empresa  
✅ Login automatizado com usuário e senha  
✅ Leitura e manipulação de dados com `pandas`  
✅ Cadastro automático de múltiplos produtos no sistema  
✅ Interação com interface gráfica via `pyautogui`  
✅ Alerta final de sucesso ao concluir o processo  

---

## Tecnologias Utilizadas

| Biblioteca | Finalidade |
|-------------|-------------|
| **PyAutoGUI** | Controle de teclado, mouse e automação da interface |
| **Pandas** | Leitura e manipulação de dados tabulares (CSV) |
| **Time** | Pausas e controle do tempo de execução |
| **OS** | Gerenciamento de arquivos locais |
| **NumPy** | Suporte numérico e tratamento de valores nulos |

---

## 📂 Estrutura do Projeto
📦 Automacao_Cadastro_Produtos
 ┣ 📄 automacao_cadastro.py
 ┣ 📄 produtos.csv
 ┗ 📄 README.md


O arquivo `produtos.csv` contém os dados a serem cadastrados automaticamente no sistema.  
Exemplo de estrutura:


---

## Como Executar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/KrisGregory/Automacao_Cadastro_Produtos.git

2. **Instale as dependências**

pip install pyautogui pandas numpy


3. **Execute o script**

python automacao_cadastro.py

⚠️ Atenção:
Antes de executar:

Ajuste as coordenadas do mouse (x, y) de acordo com a posição dos campos do seu navegador.

Mantenha o arquivo produtos.csv na mesma pasta do script.

Não mova o mouse nem troque de janela durante a automação.

🎯 Demonstração (conceito)

O script realiza automaticamente as seguintes etapas:

1️⃣ Abre o navegador e acessa o sistema
2️⃣ Faz login com usuário e senha
3️⃣ Lê uma base de dados (produtos.csv)
4️⃣ Preenche e cadastra os produtos um a um
5️⃣ Exibe uma mensagem confirmando a conclusão do processo

🧩 Aprendizados-Chave

Durante o desenvolvimento deste projeto, foram aplicados conceitos fundamentais de:

Automação de interface gráfica com PyAutoGUI

Manipulação de dados com Pandas

Estruturação de fluxos automatizados com pausas controladas e validações

Criação de scripts práticos e reutilizáveis para o ambiente de trabalho

👩‍💻 Autora

Krisley Gregory
📍 Data Analytics & Python Automation Enthusiast
📧 kriss_gregory@outlook.com

🔗 LinkedIn - krisley-g-20350213b/
 | GitHub
