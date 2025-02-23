

# 📁 Script de Auditoria de Permissões de Arquivos

### Autor: **Carlos Eduardo Guimarães Prado**  
### Versão: **1.0**

---

## 📋 Descrição

Este script em **PowerShell** foi desenvolvido para **auditar**, **gerenciar** e **corrigir permissões** de arquivos e pastas em sistemas **Windows**. Ele fornece funcionalidades essenciais para administradores de sistemas garantirem que os diretórios estejam devidamente protegidos, minimizando riscos de acessos não autorizados.

---

## 🚀 Funcionalidades

1. **📂 Listar Permissões de uma Pasta**  
   Exibe todas as permissões configuradas em uma pasta de forma clara e detalhada.

2. **⚠️ Identificar Permissões Inseguras**  
   Detecta pastas e arquivos com permissões amplas, como **"Everyone"** com **"Full Control"**, destacando potenciais riscos.

3. **📊 Gerar Relatório em CSV**  
   Cria um relatório detalhado em formato **CSV** contendo informações sobre permissões, herança e usuários.

4. **🔄 Corrigir Herança Quebrada**  
   Restaura as permissões herdadas em pastas onde a herança foi desativada indevidamente.

5. **🚪 Sair**  
   Finaliza a execução do script.

---

## ⚙️ Requisitos

- **Sistema Operacional**: Windows 10/11, Windows Server 2016 ou superior  
- **Permissões**: Execução como **Administrador**  
- **PowerShell**: Versão 5.1 ou superior  
- **Caminho para Logs**: Certifique-se de que o diretório `C:\Logs` existe para armazenar os logs gerados.

---

## 🛠️ Como Usar

1. **Execute o PowerShell como Administrador.**  
2. **Execute o script:**  
   ```powershell
   .\AuditoriaPermissoes.ps1
   ```

3. **Siga o menu interativo:**  
   - **Escolha a opção desejada (1-5)**.  
   - **Informe os caminhos de pastas/arquivos** quando solicitado.

4. **Logs:**  
   - Todas as ações são registradas no arquivo:  
     ```plaintext
     C:\Logs\AuditoriaPermissoes.log
     ```

---

## 📝 Exemplo de Uso

**Listar permissões de uma pasta:**  
```powershell
1. Listar permissões de uma pasta  
Digite o caminho da pasta: C:\Projetos  
```

**Gerar um relatório em CSV:**  
```powershell
3. Gerar relatório em CSV  
Digite o caminho da pasta: C:\Projetos  
Digite o caminho do arquivo CSV: C:\Relatorio_Permissoes.csv  
```

---

## ⚡ Melhorias Futuras

- Integração com Active Directory para auditorias de usuários específicos.  
- Relatórios em formato PDF com visual mais amigável.  
- Interface gráfica básica usando PowerShell GUI.  

---

## 📄 Licença

Este projeto está sob a licença **MIT**.  
Sinta-se à vontade para modificar, distribuir ou usar conforme necessário.

---
