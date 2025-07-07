# 🗄️ Oracle Tuning & Auditoria - SQL Scripts

Este repositório contém um conjunto de scripts SQL para análise de performance, auditoria padrão, criação de políticas FGA (*Fine-Grained Auditing*) e recuperação com RMAN em bancos de dados Oracle. O objetivo é fornecer ferramentas úteis para DBAs e desenvolvedores monitorarem e ajustarem o ambiente de forma prática.  

---

## 📑 Sumário

- [♻️ RMAN (Recovery Manager)](#-rman-recovery-manager)
- [🚀 Como usar](#-como-usar)
- [🛠️ Tecnologias](#-tecnologias)
- [📂 Organização](#-organização)
- [👨‍💻 Autor](#-autor)
- [📝 Licença](#-licença)


---

## ♻️ RMAN (Recovery Manager)

Scripts voltados para operações de recuperação e gerenciamento usando o Oracle RMAN:  

| 📄 Script                                  | 📝 Descrição                                                                 |
|--------------------------------------------|-------------------------------------------------------------------------------|
| `recuperar_tablespace_bdonline.sql`        | Realiza a recuperação de uma tablespace com o banco em modo online.          |
| `restore_tabela_bd_auxiliar.sql`           | Restaura uma tabela específica utilizando banco de dados auxiliar.           |
| `scripts_armazenados.sql`                  | Lista scripts RMAN previamente armazenados no catálogo do banco.             |

