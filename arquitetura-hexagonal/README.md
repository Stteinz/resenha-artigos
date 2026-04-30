# 📝 Resenha Crítica: Arquitetura Hexagonal (Ports and Adapters)

> **📌 Documento para avaliação:** A resenha principal é o arquivo **`Resenha-Arquitetura-Hexagonal.pdf`** — Resenha crítica sobre Arquitetura Hexagonal (artigo de Alistair Cockburn).

Esta pasta contém os materiais e documentos da resenha crítica do artigo **"Hexagonal Architecture"**, escrito por Alistair Cockburn (2005). O trabalho foi desenvolvido como requisito para a disciplina de **Projeto de Software** do curso de Engenharia de Software da PUC Minas.

## 🎯 Sobre o Conteúdo

O objetivo desta resenha é analisar e sintetizar os conceitos fundamentais da Arquitetura Hexagonal, também conhecida como *Ports and Adapters*, explorando como esse padrão arquitetural promove o isolamento da lógica de negócio em relação a tecnologias externas, favorecendo testabilidade, flexibilidade e manutenibilidade.

## 📄 Documentos Disponíveis

| Arquivo | Descrição |
|---------|-----------|
| [Resenha-Arquitetura-Hexagonal.pdf](Resenha-Arquitetura-Hexagonal.pdf) | **Resenha principal** — Resenha crítica de Arquitetura Hexagonal (Alistair Cockburn) — *Documento para avaliação* |

## 📖 Tópicos Abordados na Resenha

* **Conceito Central:** Separação clara entre o núcleo da aplicação (regras de negócio) e elementos externos (UI, banco de dados, APIs), garantindo independência tecnológica.
* **Portas e Adaptadores:** Comunicação entre o sistema e o mundo externo via *ports* (interfaces abstratas) e *adapters* (implementações concretas para cada tecnologia).
* **Representação Hexagonal:** O hexágono ilustra que o sistema pode ter múltiplas entradas e saídas, superando a limitação das arquiteturas em camadas tradicionais.
* **Testabilidade:** A possibilidade de substituir dependências externas por *mocks* sem alterar o núcleo do sistema representa um avanço significativo frente às arquiteturas tradicionais.
* **Análise Crítica:** A proposta é alinhada a princípios modernos de baixo acoplamento e alta coesão, mas pode aumentar a complexidade inicial, especialmente para equipes menos experientes.

## 👨‍💻 Autor

**Gabriel Lacerda Lemos da Silva** — Engenharia de Software - PUC Minas  
GitHub: [@stteinz](https://github.com/stteinz)

---

📌 Para informações gerais do repositório, consulte o [README principal](../README.md).
