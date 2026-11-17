# Projeto Integrador - Clínica FisioVida & Saúde

## 1. Descrição do Projeto
A **Clínica FisioVida & Saúde** é uma aplicação web interativa voltada para a área da saúde e reabilitação física. O sistema apresenta as especialidades da clínica, horários de atendimento, uma galeria estruturada de mídias e um formulário inteligente de agendamento de consultas com validações em tempo real e relatórios dinâmicos via console.

## 2. Tecnologias Utilizadas
* **HTML5** (Semântica avançada, estruturação de formulários, tabelas e mídias)
* **CSS3** (Variáveis personalizadas no `:root`, Flexbox, Grid Layout e design responsivo)
* **JavaScript Puro (Vanilla)** (Manipulação de DOM, arrays de objetos, estruturas condicionais, laços de repetição, funções e eventos)

## 3. Capturas de Tela
### Versão Desktop
![Print Desktop](images/desktop.png)

### Versão Celular (Responsivo)
![Print Celular](images/celular.png)

## 4. Estrutura de Pastas
```text
clinica-fisio/
├── index.html
├── reset.css
├── style.css
├── script.js
└── images/
    ├── desktop.png
    └── celular.png
```
## 5. Como Executar
1. Certifique-se de ter o editor **VS Code** instalado junto com a extensão **Live Server**.
2. Abra a pasta do projeto no VS Code.
3. Clique com o botão direito no arquivo **`index.html`** e selecione **"Open with Live Server"**, ou abra-o diretamente em seu navegador web preferido.

## 6. Mapa de Requisitos
| Requisito / Item | Arquivo de Implementação | Seção / Detalhes |
| :--- | :--- | :--- |
| **Estrutura HTML5 Válida** | `index.html` | Cabeçalho, metadados e tags semânticas estruturais |
| **Tabela de Dados Reais** | `index.html` | Seção "Horário de Atendimento" (tabela estruturada) |
| **Mídia e Vídeo** | `index.html` | Elemento `<video>` com controles, poster e fontes customizadas |
| **Reset e Box Model** | `reset.css` | Aplicação global de `box-sizing: border-box` |
| **Variáveis CSS e Estilos** | `style.css` | Uso de `:root` para cores e tipografia com unidades em `rem` |
| **Layout Responsivo** | `style.css` | Adaptação para dispositivos móveis via Media Queries e Flexbox |
| **Lógica JS (Dados e Loops)** | `script.js` | Array de objetos `procedimentosFisio`, condicionais e laços `for` |
| **Eventos e Validação** | `script.js` | Submissão de formulário sem reload e validação de contatos |

## 7. Autor
* **Nome:** Lucas Eduardo
* **Curso:** Análise e Desenvolvimento de Sistemas (ADS) — UNIPÊ
