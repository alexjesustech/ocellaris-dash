# Contribuindo para o Ocellaris Dash

Em primeiro lugar, obrigado por reservar um tempo para contribuir!

Segue um conjunto de diretrizes para contribuir com o Ocellaris Dash. Essas são principalmente diretrizes, não regras. Use seu bom senso e sinta-se à vontade para propor mudanças a este documento em uma solicitação de pull.

#### Índice

[Código de Conduta](#código-de-conduta)

[Como posso contribuir?](#como-posso-contribuir)
  * [Relatando Bugs](#relatando-bugs)
  * [Sugerindo Melhorias](#sugerindo-melhorias)
  * [Corrigindo um bug](#corrigindo-um-bug)
  * [Fornecendo Melhorias](#fornecendo-melhorias)
  * [Pull Requests](#pull-requests)

[Guias de Estilo](#guias-de-estilo)
  * [Mensagens de Commit do Git](#mensagens-de-commit-do-git)

## Código de Conduta

Este projeto e todos os que participam dele são regidos pelo [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). Ao participar, espera-se que você cumpra este código. Por favor, reporte comportamentos inaceitáveis para [Alex Jesus](mailto:alexjesus.tech@gmail.com)

## Como posso contribuir?

### Relatando Bugs

Esta seção orienta você a enviar um relatório de bug para o Ocellaris Dash. Seguir estas diretrizes ajuda os mantenedores e a comunidade a entender seu relatório, reproduzir o comportamento, e encontrar relatórios relacionados.

Antes de criar relatórios de bug, verifique os problemas abertos existentes e certifique-se de que o problema que você está relatando já não foi relatado e aberto. Quando estiver criando um relatório de bug, preencha o modelo obrigatório, as informações solicitadas nos ajudam a resolver problemas mais rapidamente.

> **Nota:** Se você encontrar um problema **Fechado** que parece ser o mesmo que você está experimentando, abra um novo problema e inclua um link para o problema original no corpo do seu novo.

#### Como faço para enviar um (bom) relatório de bug?

Os bugs são rastreados como [problemas do GitHub](https://guides.github.com/features/issues/). Explique o problema e inclua detalhes adicionais para ajudar os mantenedores a reproduzir o problema:

* **Use um título claro e descritivo** para identificar o problema.
* **Descreva as etapas exatas que reproduzem o problema** com o máximo de detalhes possível.
* **Se você estiver fornecendo snippets no problema, use [blocos de código Markdown](https://help.github.com/articles/markdown-basics/#multiple-lines)**.
* **Descreva o comportamento que você observou após seguir as etapas** e aponte exatamente qual é o problema com esse comportamento.
* **Explique qual comportamento você esperava ver em vez disso e por quê.**
* **Inclua capturas de tela e GIFs animados** que mostram você seguindo as etapas descritas e demonstrem claramente o problema. Você pode usar [esta ferramenta](https://www.cockos.com/licecap/) para gravar GIFs no macOS e Windows, e [esta ferramenta](https://github.com/colinkeenan/silentcast) ou [esta ferramenta](https://github.com/phw/peek) no Linux.

### Sugerindo Melhorias

Assim como os bugs, as melhorias também podem ser sugeridas como [problemas do GitHub](https://guides.github.com/features/issues/).

#### Como faço para enviar uma (boa) sugestão de melhoria?

* **Use um título claro e descritivo** para a sugestão que você está propondo.
* **Inclua capturas de tela ou GIFs animados relacionados** para melhor clareza.
* **Descreva como seria útil** para os usuários.

### Corrigindo um bug

* Se você estiver pensando em corrigir um problema aberto, comente no problema que você está trabalhando para corrigir o problema e como está planejando corrigi-lo.
* Crie um novo problema se o que você está corrigindo ainda não estiver aberto e, em seguida, comente no problema que você está corrigindo.
* Isso permitirá que os colaboradores saibam que o problema específico está sendo corrigido no momento e devem esperar um pouco antes de tentar corrigir o mesmo problema eles mesmos.

### Fornecendo Melhorias

- Se você estiver planejando propor um novo recurso, abra um problema para a mesma solicitação de recurso antes de começar a trabalhar em um recurso.
- Isso ajudará os colaboradores e mantenedores a fornecer feedback e suporte para a melhoria que você está fornecendo.

### Pull Requests

Por favor, siga estas etapas antes de enviar uma solicitação de pull.

1. Verifique se sua solicitação de pull não é uma duplicata.

2. Se não, certifique-se de que:

    2.1. Você fez suas alterações em uma ramificação separada. As ramificações DEVEM ter nomes descritivos que começam com os prefixos `fix` ou `feature`. Bons exemplos são: `fix-signin-issue` ou `feature-issue-templates`.

    2.2. Você tem uma mensagem de commit descritiva com um título curto (primeira linha).

    2.2. Você criou uma solicitação de pull para apenas um propósito. Crie ramificações separadas e solicitações de pull separadas para cada novo recurso introduzido ou para cada problema corrigido.

    2.3. Você tem apenas um commit (se não, comprima-os em um commit).

3. **Após** essas etapas, você está pronto para abrir uma solicitação de pull.

3.1. Sua solicitação de pull NÃO DEVE direcionar a ramificação `master` neste repositório. Em vez disso, direcione a ramificação da próxima versão. Por exemplo, se a versão estável atual: <https://github.com/alexjesustech/ocellaris-dash/releases/latest> do tema for `2.3.1`, direcione a ramificação para a próxima versão `2.3.2` ou `3.0.0`, se a próxima versão for um lançamento principal. Suas alterações serão mescladas na ramificação principal quando o próximo lançamento ocorrer.

3.2. Dê um título descritivo ao seu PR.

3.3. Forneça uma descrição de suas alterações.

3.4. Coloque `closes #XXXX` em seu comentário para fechar automaticamente o problema que seu PR corrige.


## Guias de Estilo

### Mensagens de Commit do Git

- Use o tempo presente ("Add feature" não "Added feature")
- Use o modo imperativo ("Move cursor to..." não "Moves cursor to...")
- Limite a primeira linha a 72 caracteres ou menos
- Faça referência a problemas e solicitações de pull generosamente após a primeira linha
