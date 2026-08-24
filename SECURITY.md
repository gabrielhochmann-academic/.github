# Política de Segurança

## Escopo

Esta organização armazena trabalhos acadêmicos e colaborativos. Trate **credenciais, configurações de acesso, informações pessoais, trabalhos acadêmicos não publicados e documentos internos como informações sensíveis**.

## Comunicação de preocupações

Não abra uma *issue* pública contendo **tokens, links privados, informações pessoais, detalhes de vulnerabilidades ou trabalhos acadêmicos confidenciais**. Utilize um canal privado já existente do projeto para entrar em contato com o proprietário do repositório ou com o responsável pelo projeto.

Se uma credencial for exposta, **revogue-a ou altere-a imediatamente** antes de compartilhar qualquer detalhe para diagnóstico.

## Práticas básicas para contribuições seguras

- Utilize **Secrets do repositório** para credenciais usadas em automações.
- Mantenha as **permissões dos workflows no nível mínimo necessário**.
- Quando exigido, fixe as **GitHub Actions de terceiros em SHAs completos de commit**.
- **Nunca envie credenciais** para o controle de versão, *issues*, *pull requests* ou documentação.
