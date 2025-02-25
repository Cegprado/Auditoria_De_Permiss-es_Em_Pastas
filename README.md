# 🚀 Automatize a Auditoria de Permissões de Arquivos com PowerShell!

Você já se deparou com a necessidade de auditar permissões de arquivos e pastas em um ambiente Windows? Saber quem tem acesso a quê e identificar permissões inseguras pode ser um desafio, especialmente em ambientes com muitos usuários e pastas compartilhadas.

Pensando nisso, desenvolvi um script em PowerShell que simplifica esse processo! 🚀

---

## 📌 O que esse script faz?
✅ **Lista permissões de pastas** de forma organizada e legível.  
✅ **Identifica permissões inseguras**, como "Everyone/Full Control".  
✅ **Gera relatórios em CSV** para análise e documentação.  
✅ **Corrige herança de permissões quebradas**, garantindo a segurança do ambiente.  
✅ **Registra logs detalhados** para auditoria e acompanhamento.  

---

## 🎯 Por que usar?
- **Eficiência**: Automatiza tarefas manuais e repetitivas.  
- **Segurança**: Identifica e corrige vulnerabilidades rapidamente.  
- **Transparência**: Gera relatórios claros para compartilhamento com a equipe ou superiores.  

---

## 🛠️ Como funciona?
O script é modular e fácil de usar, com um menu interativo que guia o usuário pelas funcionalidades. Além disso, ele foi desenvolvido com boas práticas, como validação de entradas, tratamento de erros e suporte a logs detalhados.

### 📖 Manual / Help: Configuração Inicial

Antes de executar o script, é importante definir algumas variáveis essenciais para garantir o correto funcionamento:

### 🔹 Configuração das principais variáveis:

1️⃣ **OU Padrão de Usuários:** Define a unidade organizacional onde os usuários serão cadastrados. Exemplo:
   ```powershell
   $OUUsuarios = "OU=Usuarios,DC=empresa,DC=com"
   ```

2️⃣ **OU Padrão de Computadores:** Define a unidade organizacional onde os computadores serão cadastrados. Exemplo:
   ```powershell
   $OUComputadores = "OU=Computadores,DC=empresa,DC=com"
   ```

3️⃣ **Domínio:** Define o domínio padrão da empresa. Exemplo:
   ```powershell
   $Dominio = "empresa.com"
   ```

### 🏁 Como executar o script?
1. Abra o PowerShell como Administrador.
2. Navegue até o diretório onde o script está salvo.
   ```powershell
   cd C:\Scripts
   ```
3. Execute o script:
   ```powershell
   .\AuditoriaPermissoes.ps1
   ```
4. Siga as instruções interativas no terminal.

---

## 🔗 Confira o código completo no GitHub:
[Link do Repositório](https://github.com/Cegprado/Auditoria_De_Permiss-es_Em_Pastas/blob/main/Auditoria%20de%20permiss%C3%B5es%20em%20pastas.txt)

---

## 📢 Quem pode usar?
- Administradores de sistemas Windows.  
- Profissionais de segurança da informação.  
- Qualquer pessoa que precise gerenciar permissões de arquivos de forma eficiente.  

Se você gosta de soluções que unem **automação**, **segurança** e **eficiência**, este script é para você! 💻🔒

👉 **Dúvidas ou sugestões? Comente abaixo ou entre em contato! Vamos trocar ideias e melhorar ainda mais essa solução.**

#PowerShell #Automação #SegurançaDaInformação #Windows #DevOps #TI #Scripting #GitHub

