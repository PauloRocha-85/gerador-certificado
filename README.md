# 📄 Gerador de Certificados de Garantia - ED7 Pragas

Este é um sistema web responsivo e dinâmico desenvolvido para simplificar a emissão de Certificados de Garantia de controle de pragas urbanas da **ED7 Pragas**. O projeto gera documentos em formato A4 perfeitamente alinhados diretamente no navegador do cliente, sem necessidade de processamento no servidor (Serverless).

---

## 🚀 Funcionalidades

*   **Edição Dinâmica:** Altere a placa do veículo e a data de emissão e veja o PDF atualizar em tempo real.
*   **Visualizador Integrado:** Simulador de leitor de PDF nativo (com miniaturas e zoom) para conferência antes da exportação.
*   **Ações Rápidas:**
    *   **Gerar/Visualizar:** Atualiza instantaneamente a tela de conferência.
    *   **Imprimir:** Abre a caixa de diálogo nativa de impressão do sistema operacional.
    *   **Baixar PDF:** Realiza o download imediato do arquivo nomeado dinamicamente com a placa informada (ex: `certificado-EFW4234.pdf`).
*   **Fidelidade Visual:** Respeita milimetricamente o layout físico do certificado original, incluindo tabelas de princípios ativos, dados regulatórios (CEATOX, Vigilância Sanitária) e assinaturas autorizadas.

---

## 🛠️ Tecnologias Utilizadas

*   [Tailwind CSS](https://tailwindcss.com/) - Para uma interface moderna, limpa e totalmente responsiva.
*   [jsPDF](https://github.com/parallax/jsPDF) - Biblioteca JavaScript principal para renderização de vetores e textos no formato PDF.
*   [FontAwesome](https://fontawesome.com/) - Ícones intuitivos para botões de ação e barra de ferramentas.
*   [GitHub Pages](https://pages.github.com/) - Hospedagem estática gratuita e instantânea.

---

## 📦 Como Usar Localmente

Se quiser rodar ou testar o projeto em sua máquina:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
