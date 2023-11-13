# Diretrizes de solicitação de pull request

Siga estas etapas antes de enviar uma solicitação de pull request.

1. Verifique se sua solicitação de pull request não é duplicada.
2. Caso contrário, certifique-se de que:

   2.1. Você fez suas alterações em uma ramificação separada. As ramificações DEVEM ter nomes descritivos que começam com os prefixos `fix/` ou `feature/`. Bons exemplos são: `fix/signin-issue` ou `feature/issue-templates`.

   2.2. Você tem uma mensagem de commit descritiva com um título curto (primeira linha).

   2.2. Você criou uma solicitação de pull request para apenas um propósito. Crie ramificações separadas e solicitações de pull request separadas para cada novo recurso introduzido ou para cada problema corrigido.

   2.3. Você tem apenas um commit (se não, esmague-os em um único commit).

3. **Após** essas etapas, você estará pronto para abrir uma solicitação de pull request.

   3.1. Sua solicitação de pull request NÃO DEVE ter como alvo a ramificação `master` neste repositório. Em vez disso, vise a próxima ramificação de versão. Por exemplo, se a [versão estável atual](https://github.com/alexjesustech/ocellaris-dash/releases/latest) do tema for `2.3.1`, vise a ramificação para a próxima versão `2.3.2` ou `3.0.0` se a próxima versão for uma versão principal. Suas alterações serão mescladas na ramificação master quando a próxima versão ocorrer.

   3.2. Dê um título descritivo ao seu PR.

   3.3. Forneça uma descrição de suas alterações.

   3.4. Coloque `closes #XXXX` em seu comentário para fechar automaticamente o problema que seu PR corrige.

IMPORTANTE: Por favor, revise o arquivo [CONTRIBUTING.md](../CONTRIBUTING.md) para obter diretrizes de contribuição detalhadas.

**REMOVA ESTE TEMPLATE ANTES DE ENVIAR**