---
name: Erro 403 - Forbidden
about: Empresa com falha ao tentar abrir a tela do SOL pela Internet, Erro 403 - Forbidden
title: '403'
labels: 403, SOL
assignees: ''

---

**Empresa com falha ao tentar abrir a tela do SOL pela Internet, Erro 403 - Forbidden**
- Tipo de erro
         - Erro de autenticação
      - Variações do erro
         - Forbidden – You don’t have permission to access / on this server403
         - Forbidden: Access is denied
         - Error 403 – Forbidden
         - 403 – Forbidden Error – You are not allowed to access this address
         - 403 Forbidden – nginx
      - Causas do erro
          - Arquivo .htaccess corrompido
          - Permissões de arquivo incorretas
          - Problemas com plugins
      - **O que deve ser verificado?**
           - O IP de saída da Internet da empresa foi alterado? (Algumas empresas usam saída ADSL, não é IP fixo)
           - O IP de saída da Internet da empresa está liberado?
      - **A empresa está direcionando a url **_[sol.ativossa.com.br](url)_** para algum endereço específico?**
           - Se sim, deverá retirar o apontamento e orientar que o **_[sol.ativossa.com.br](url)_** deve ser resolvido por DNS público. 
           - Não pode ser direcionado para um endereço específico, porque os endereços IPs dos sistemas da Ativos de Internet são dinâmicos, não tem um range específico.
