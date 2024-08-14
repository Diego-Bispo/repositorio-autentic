# repositorio-autentic

Meu repositório de autenticações - DIO

teste de autenticação 

✅Geral sobre Autenticações do Github
====================================

A baixo, veremos as formas de autenticação do github.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#autenticacao-do-github)

Autenticação do Github

**>> NOME DE USUÁRIO E SENHA**

Existem diferentes maneiras de se autenticar no GitHub. Uma delas é usando nome de usuário e senha, mas essa opção é considerada arriscada para informações sensíveis. Recomenda-se explorar outras opções mais seguras disponíveis.

**>> TOKENS DE ACESSO PESSOAL**

Os PATs (Tokens de Acesso Pessoal) são como senhas especiais que substituem o uso da senha normal ao acessar o GitHub pela API ou pela linha de comando. Você cria esse token nas configurações do GitHub e decide quais ações ele pode realizar em um repositório ou organização. Quando você usa a linha de comando do Git para trabalhar no GitHub, em vez de digitar seu nome de usuário e senha, você insere esse token para se autenticar. Isso torna a interação mais segura e prática.

**>> CHAVES SSH**

Chaves SSH são como chaves especiais que ajudam as pessoas a se conectarem a computadores remotos de forma segura, sem precisar sempre digitar senha ou token.

Ao configurar o SSH, as pessoas criam uma chave especial e a adicionam ao seu perfil no GitHub. Essa chave é protegida por uma "frase secreta" para garantir ainda mais segurança. Elas podem configurar seu computador para usar essa chave automaticamente, ou digitar a "frase secreta" quando necessário.

É possível até usar essas chaves em organizações que usam uma forma avançada de login. Se a organização fornece certificados especiais, as pessoas podem usá-los para acessar os repositórios sem precisar adicionar nada à sua conta no GitHub. Resumindo, as chaves SSH tornam as interações com o GitHub mais seguras e convenientes.

**>> CHAVES DE IMPLEMENTAÇÃO**

Chaves de implantação são como chaves especiais que permitem acesso a apenas um lugar específico no GitHub, como um cofre digital. No GitHub, a parte da chave que todos podem ver é conectada diretamente ao local desejado (um repositório), enquanto a parte secreta fica guardada no seu próprio computador.

Essas chaves são configuradas para permitir apenas leitura por padrão, o que significa que você pode ver o que está dentro, mas não modificar nada. No entanto, se quiser também fazer alterações, você pode configurar essas chaves para ter permissão de escrita, adicionando-as ao local específico (repositório). Resumindo, são como chaves digitais que abrem a porta para um lugar específico no GitHub, e você decide se só quer olhar ou também mexer nas coisas.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#opcoes-de-segurancas-adicionais)

Opções de seguranças adicionais

**>> Autenticação de dois Fatores - 2FA**

A autenticação de dois fatores (2FA) é como adicionar uma camada extra de segurança quando você entra em sites ou aplicativos. Além de digitar seu nome de usuário e senha, você precisa fornecer mais uma prova de que é realmente você.

No caso do GitHub, essa prova extra geralmente é um código gerado por um aplicativo no seu celular ou enviado por mensagem de texto. Depois de ativar a 2FA, sempre que alguém tenta entrar na sua conta, o GitHub pede esse código adicional. Ou seja, para entrar, a pessoa precisa não só da senha, mas também do código enviado para o celular.

Os donos de organizações no GitHub podem pedir que todos, membros ou colaboradores, ativem a 2FA em suas contas pessoais. Isso dificulta para pessoas mal-intencionadas acessarem informações importantes.

Além disso, em empresas, os donos podem impor regras de segurança para todas as organizações vinculadas a uma conta corporativa, garantindo uma proteção adicional para todos os envolvidos. Resumindo, é uma maneira de deixar as coisas mais seguras na internet.

**>> SSO do SAML**

SSO do SAML é uma forma de segurança no GitHub que permite controlar o acesso aos recursos da organização de maneira centralizada. Em vez de usar senhas, os usuários são redirecionados para um sistema central de login (IdP), como o Microsoft Entra ID ou Okta. Após autenticados lá, eles retornam ao GitHub com acesso aos recursos da organização.

Essa abordagem facilita o gerenciamento, pois os proprietários da organização controlam quem pode acessar o quê. O GitHub suporta vários provedores populares, como Active Directory, Microsoft Entra ID e Okta. Em resumo, é uma maneira mais segura e eficiente de gerenciar o acesso aos dados no GitHub.

**>>** **LDPA**

O LDAP é um protocolo usado para acessar e organizar informações em diretórios, especialmente em grandes empresas. No contexto do GitHub Enterprise Server, ele permite integrar e gerenciar centralmente o acesso aos repositórios usando contas existentes.

O GitHub Enterprise Server é compatível com vários serviços LDAP conhecidos, como Active Directory, Oracle Directory Server Enterprise Edition, OpenLDAP e outros. Em resumo, o LDAP é uma ferramenta que ajuda na organização e controle de acesso em ambientes corporativos no GitHub.

**Links Importantes:**

[https://support.github.com/](https://support.github.com/)

[Documentação de autenticação - GitHub Docs](https://docs.github.com/pt/authentication)✅Geral sobre Autenticações do Github

A baixo, veremos as formas de autenticação do github.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#autenticacao-do-github)

Autenticação do Github

**>> NOME DE USUÁRIO E SENHA**

Existem diferentes maneiras de se autenticar no GitHub. Uma delas é usando nome de usuário e senha, mas essa opção é considerada arriscada para informações sensíveis. Recomenda-se explorar outras opções mais seguras disponíveis.

**>> TOKENS DE ACESSO PESSOAL**

Os PATs (Tokens de Acesso Pessoal) são como senhas especiais que substituem o uso da senha normal ao acessar o GitHub pela API ou pela linha de comando. Você cria esse token nas configurações do GitHub e decide quais ações ele pode realizar em um repositório ou organização. Quando você usa a linha de comando do Git para trabalhar no GitHub, em vez de digitar seu nome de usuário e senha, você insere esse token para se autenticar. Isso torna a interação mais segura e prática.

**>> CHAVES SSH**

Chaves SSH são como chaves especiais que ajudam as pessoas a se conectarem a computadores remotos de forma segura, sem precisar sempre digitar senha ou token.

Ao configurar o SSH, as pessoas criam uma chave especial e a adicionam ao seu perfil no GitHub. Essa chave é protegida por uma "frase secreta" para garantir ainda mais segurança. Elas podem configurar seu computador para usar essa chave automaticamente, ou digitar a "frase secreta" quando necessário.

É possível até usar essas chaves em organizações que usam uma forma avançada de login. Se a organização fornece certificados especiais, as pessoas podem usá-los para acessar os repositórios sem precisar adicionar nada à sua conta no GitHub. Resumindo, as chaves SSH tornam as interações com o GitHub mais seguras e convenientes.

**>> CHAVES DE IMPLEMENTAÇÃO**

Chaves de implantação são como chaves especiais que permitem acesso a apenas um lugar específico no GitHub, como um cofre digital. No GitHub, a parte da chave que todos podem ver é conectada diretamente ao local desejado (um repositório), enquanto a parte secreta fica guardada no seu próprio computador.

Essas chaves são configuradas para permitir apenas leitura por padrão, o que significa que você pode ver o que está dentro, mas não modificar nada. No entanto, se quiser também fazer alterações, você pode configurar essas chaves para ter permissão de escrita, adicionando-as ao local específico (repositório). Resumindo, são como chaves digitais que abrem a porta para um lugar específico no GitHub, e você decide se só quer olhar ou também mexer nas coisas.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#opcoes-de-segurancas-adicionais)

Opções de seguranças adicionais

**>> Autenticação de dois Fatores - 2FA**

A autenticação de dois fatores (2FA) é como adicionar uma camada extra de segurança quando você entra em sites ou aplicativos. Além de digitar seu nome de usuário e senha, você precisa fornecer mais uma prova de que é realmente você.

No caso do GitHub, essa prova extra geralmente é um código gerado por um aplicativo no seu celular ou enviado por mensagem de texto. Depois de ativar a 2FA, sempre que alguém tenta entrar na sua conta, o GitHub pede esse código adicional. Ou seja, para entrar, a pessoa precisa não só da senha, mas também do código enviado para o celular.

Os donos de organizações no GitHub podem pedir que todos, membros ou colaboradores, ativem a 2FA em suas contas pessoais. Isso dificulta para pessoas mal-intencionadas acessarem informações importantes.

Além disso, em empresas, os donos podem impor regras de segurança para todas as organizações vinculadas a uma conta corporativa, garantindo uma proteção adicional para todos os envolvidos. Resumindo, é uma maneira de deixar as coisas mais seguras na internet.

**>> SSO do SAML**

SSO do SAML é uma forma de segurança no GitHub que permite controlar o acesso aos recursos da organização de maneira centralizada. Em vez de usar senhas, os usuários são redirecionados para um sistema central de login (IdP), como o Microsoft Entra ID ou Okta. Após autenticados lá, eles retornam ao GitHub com acesso aos recursos da organização.

Essa abordagem facilita o gerenciamento, pois os proprietários da organização controlam quem pode acessar o quê. O GitHub suporta vários provedores populares, como Active Directory, Microsoft Entra ID e Okta. Em resumo, é uma maneira mais segura e eficiente de gerenciar o acesso aos dados no GitHub.

**>>** **LDPA**

O LDAP é um protocolo usado para acessar e organizar informações em diretórios, especialmente em grandes empresas. No contexto do GitHub Enterprise Server, ele permite integrar e gerenciar centralmente o acesso aos repositórios usando contas existentes.

O GitHub Enterprise Server é compatível com vários serviços LDAP conhecidos, como Active Directory, Oracle Directory Server Enterprise Edition, OpenLDAP e outros. Em resumo, o LDAP é uma ferramenta que ajuda na organização e controle de acesso em ambientes corporativos no GitHub.

**Links Importantes:**

[https://support.github.com/](https://support.github.com/)

[Documentação de autenticação - GitHub Docs](https://docs.github.com/pt/authentication)✅Geral sobre Autenticações do Github

A baixo, veremos as formas de autenticação do github.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#autenticacao-do-github)

Autenticação do Github

**>> NOME DE USUÁRIO E SENHA**

Existem diferentes maneiras de se autenticar no GitHub. Uma delas é usando nome de usuário e senha, mas essa opção é considerada arriscada para informações sensíveis. Recomenda-se explorar outras opções mais seguras disponíveis.

**>> TOKENS DE ACESSO PESSOAL**

Os PATs (Tokens de Acesso Pessoal) são como senhas especiais que substituem o uso da senha normal ao acessar o GitHub pela API ou pela linha de comando. Você cria esse token nas configurações do GitHub e decide quais ações ele pode realizar em um repositório ou organização. Quando você usa a linha de comando do Git para trabalhar no GitHub, em vez de digitar seu nome de usuário e senha, você insere esse token para se autenticar. Isso torna a interação mais segura e prática.

**>> CHAVES SSH**

Chaves SSH são como chaves especiais que ajudam as pessoas a se conectarem a computadores remotos de forma segura, sem precisar sempre digitar senha ou token.

Ao configurar o SSH, as pessoas criam uma chave especial e a adicionam ao seu perfil no GitHub. Essa chave é protegida por uma "frase secreta" para garantir ainda mais segurança. Elas podem configurar seu computador para usar essa chave automaticamente, ou digitar a "frase secreta" quando necessário.

É possível até usar essas chaves em organizações que usam uma forma avançada de login. Se a organização fornece certificados especiais, as pessoas podem usá-los para acessar os repositórios sem precisar adicionar nada à sua conta no GitHub. Resumindo, as chaves SSH tornam as interações com o GitHub mais seguras e convenientes.

**>> CHAVES DE IMPLEMENTAÇÃO**

Chaves de implantação são como chaves especiais que permitem acesso a apenas um lugar específico no GitHub, como um cofre digital. No GitHub, a parte da chave que todos podem ver é conectada diretamente ao local desejado (um repositório), enquanto a parte secreta fica guardada no seu próprio computador.

Essas chaves são configuradas para permitir apenas leitura por padrão, o que significa que você pode ver o que está dentro, mas não modificar nada. No entanto, se quiser também fazer alterações, você pode configurar essas chaves para ter permissão de escrita, adicionando-as ao local específico (repositório). Resumindo, são como chaves digitais que abrem a porta para um lugar específico no GitHub, e você decide se só quer olhar ou também mexer nas coisas.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#opcoes-de-segurancas-adicionais)

Opções de seguranças adicionais

**>> Autenticação de dois Fatores - 2FA**

A autenticação de dois fatores (2FA) é como adicionar uma camada extra de segurança quando você entra em sites ou aplicativos. Além de digitar seu nome de usuário e senha, você precisa fornecer mais uma prova de que é realmente você.

No caso do GitHub, essa prova extra geralmente é um código gerado por um aplicativo no seu celular ou enviado por mensagem de texto. Depois de ativar a 2FA, sempre que alguém tenta entrar na sua conta, o GitHub pede esse código adicional. Ou seja, para entrar, a pessoa precisa não só da senha, mas também do código enviado para o celular.

Os donos de organizações no GitHub podem pedir que todos, membros ou colaboradores, ativem a 2FA em suas contas pessoais. Isso dificulta para pessoas mal-intencionadas acessarem informações importantes.

Além disso, em empresas, os donos podem impor regras de segurança para todas as organizações vinculadas a uma conta corporativa, garantindo uma proteção adicional para todos os envolvidos. Resumindo, é uma maneira de deixar as coisas mais seguras na internet.

**>> SSO do SAML**

SSO do SAML é uma forma de segurança no GitHub que permite controlar o acesso aos recursos da organização de maneira centralizada. Em vez de usar senhas, os usuários são redirecionados para um sistema central de login (IdP), como o Microsoft Entra ID ou Okta. Após autenticados lá, eles retornam ao GitHub com acesso aos recursos da organização.

Essa abordagem facilita o gerenciamento, pois os proprietários da organização controlam quem pode acessar o quê. O GitHub suporta vários provedores populares, como Active Directory, Microsoft Entra ID e Okta. Em resumo, é uma maneira mais segura e eficiente de gerenciar o acesso aos dados no GitHub.

**>>** **LDPA**

O LDAP é um protocolo usado para acessar e organizar informações em diretórios, especialmente em grandes empresas. No contexto do GitHub Enterprise Server, ele permite integrar e gerenciar centralmente o acesso aos repositórios usando contas existentes.

O GitHub Enterprise Server é compatível com vários serviços LDAP conhecidos, como Active Directory, Oracle Directory Server Enterprise Edition, OpenLDAP e outros. Em resumo, o LDAP é uma ferramenta que ajuda na organização e controle de acesso em ambientes corporativos no GitHub.

**Links Importantes:**

[https://support.github.com/](https://support.github.com/)

[Documentação de autenticação - GitHub Docs](https://docs.github.com/pt/authentication)✅Geral sobre Autenticações do Github

A baixo, veremos as formas de autenticação do github.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#autenticacao-do-github)

Autenticação do Github

**>> NOME DE USUÁRIO E SENHA**

Existem diferentes maneiras de se autenticar no GitHub. Uma delas é usando nome de usuário e senha, mas essa opção é considerada arriscada para informações sensíveis. Recomenda-se explorar outras opções mais seguras disponíveis.

**>> TOKENS DE ACESSO PESSOAL**

Os PATs (Tokens de Acesso Pessoal) são como senhas especiais que substituem o uso da senha normal ao acessar o GitHub pela API ou pela linha de comando. Você cria esse token nas configurações do GitHub e decide quais ações ele pode realizar em um repositório ou organização. Quando você usa a linha de comando do Git para trabalhar no GitHub, em vez de digitar seu nome de usuário e senha, você insere esse token para se autenticar. Isso torna a interação mais segura e prática.

**>> CHAVES SSH**

Chaves SSH são como chaves especiais que ajudam as pessoas a se conectarem a computadores remotos de forma segura, sem precisar sempre digitar senha ou token.

Ao configurar o SSH, as pessoas criam uma chave especial e a adicionam ao seu perfil no GitHub. Essa chave é protegida por uma "frase secreta" para garantir ainda mais segurança. Elas podem configurar seu computador para usar essa chave automaticamente, ou digitar a "frase secreta" quando necessário.

É possível até usar essas chaves em organizações que usam uma forma avançada de login. Se a organização fornece certificados especiais, as pessoas podem usá-los para acessar os repositórios sem precisar adicionar nada à sua conta no GitHub. Resumindo, as chaves SSH tornam as interações com o GitHub mais seguras e convenientes.

**>> CHAVES DE IMPLEMENTAÇÃO**

Chaves de implantação são como chaves especiais que permitem acesso a apenas um lugar específico no GitHub, como um cofre digital. No GitHub, a parte da chave que todos podem ver é conectada diretamente ao local desejado (um repositório), enquanto a parte secreta fica guardada no seu próprio computador.

Essas chaves são configuradas para permitir apenas leitura por padrão, o que significa que você pode ver o que está dentro, mas não modificar nada. No entanto, se quiser também fazer alterações, você pode configurar essas chaves para ter permissão de escrita, adicionando-as ao local específico (repositório). Resumindo, são como chaves digitais que abrem a porta para um lugar específico no GitHub, e você decide se só quer olhar ou também mexer nas coisas.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#opcoes-de-segurancas-adicionais)

Opções de seguranças adicionais

**>> Autenticação de dois Fatores - 2FA**

A autenticação de dois fatores (2FA) é como adicionar uma camada extra de segurança quando você entra em sites ou aplicativos. Além de digitar seu nome de usuário e senha, você precisa fornecer mais uma prova de que é realmente você.

No caso do GitHub, essa prova extra geralmente é um código gerado por um aplicativo no seu celular ou enviado por mensagem de texto. Depois de ativar a 2FA, sempre que alguém tenta entrar na sua conta, o GitHub pede esse código adicional. Ou seja, para entrar, a pessoa precisa não só da senha, mas também do código enviado para o celular.

Os donos de organizações no GitHub podem pedir que todos, membros ou colaboradores, ativem a 2FA em suas contas pessoais. Isso dificulta para pessoas mal-intencionadas acessarem informações importantes.

Além disso, em empresas, os donos podem impor regras de segurança para todas as organizações vinculadas a uma conta corporativa, garantindo uma proteção adicional para todos os envolvidos. Resumindo, é uma maneira de deixar as coisas mais seguras na internet.

**>> SSO do SAML**

SSO do SAML é uma forma de segurança no GitHub que permite controlar o acesso aos recursos da organização de maneira centralizada. Em vez de usar senhas, os usuários são redirecionados para um sistema central de login (IdP), como o Microsoft Entra ID ou Okta. Após autenticados lá, eles retornam ao GitHub com acesso aos recursos da organização.

Essa abordagem facilita o gerenciamento, pois os proprietários da organização controlam quem pode acessar o quê. O GitHub suporta vários provedores populares, como Active Directory, Microsoft Entra ID e Okta. Em resumo, é uma maneira mais segura e eficiente de gerenciar o acesso aos dados no GitHub.

**>>** **LDPA**

O LDAP é um protocolo usado para acessar e organizar informações em diretórios, especialmente em grandes empresas. No contexto do GitHub Enterprise Server, ele permite integrar e gerenciar centralmente o acesso aos repositórios usando contas existentes.

O GitHub Enterprise Server é compatível com vários serviços LDAP conhecidos, como Active Directory, Oracle Directory Server Enterprise Edition, OpenLDAP e outros. Em resumo, o LDAP é uma ferramenta que ajuda na organização e controle de acesso em ambientes corporativos no GitHub.

**Links Importantes:**

[https://support.github.com/](https://support.github.com/)

[Documentação de autenticação - GitHub Docs](https://docs.github.com/pt/authentication)✅Geral sobre Autenticações do Github

A baixo, veremos as formas de autenticação do github.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#autenticacao-do-github)

Autenticação do Github

**>> NOME DE USUÁRIO E SENHA**

Existem diferentes maneiras de se autenticar no GitHub. Uma delas é usando nome de usuário e senha, mas essa opção é considerada arriscada para informações sensíveis. Recomenda-se explorar outras opções mais seguras disponíveis.

**>> TOKENS DE ACESSO PESSOAL**

Os PATs (Tokens de Acesso Pessoal) são como senhas especiais que substituem o uso da senha normal ao acessar o GitHub pela API ou pela linha de comando. Você cria esse token nas configurações do GitHub e decide quais ações ele pode realizar em um repositório ou organização. Quando você usa a linha de comando do Git para trabalhar no GitHub, em vez de digitar seu nome de usuário e senha, você insere esse token para se autenticar. Isso torna a interação mais segura e prática.

**>> CHAVES SSH**

Chaves SSH são como chaves especiais que ajudam as pessoas a se conectarem a computadores remotos de forma segura, sem precisar sempre digitar senha ou token.

Ao configurar o SSH, as pessoas criam uma chave especial e a adicionam ao seu perfil no GitHub. Essa chave é protegida por uma "frase secreta" para garantir ainda mais segurança. Elas podem configurar seu computador para usar essa chave automaticamente, ou digitar a "frase secreta" quando necessário.

É possível até usar essas chaves em organizações que usam uma forma avançada de login. Se a organização fornece certificados especiais, as pessoas podem usá-los para acessar os repositórios sem precisar adicionar nada à sua conta no GitHub. Resumindo, as chaves SSH tornam as interações com o GitHub mais seguras e convenientes.

**>> CHAVES DE IMPLEMENTAÇÃO**

Chaves de implantação são como chaves especiais que permitem acesso a apenas um lugar específico no GitHub, como um cofre digital. No GitHub, a parte da chave que todos podem ver é conectada diretamente ao local desejado (um repositório), enquanto a parte secreta fica guardada no seu próprio computador.

Essas chaves são configuradas para permitir apenas leitura por padrão, o que significa que você pode ver o que está dentro, mas não modificar nada. No entanto, se quiser também fazer alterações, você pode configurar essas chaves para ter permissão de escrita, adicionando-as ao local específico (repositório). Resumindo, são como chaves digitais que abrem a porta para um lugar específico no GitHub, e você decide se só quer olhar ou também mexer nas coisas.

### 

[](https://aline-antunes.gitbook.io/formacao-fundamentos-github/introducao-ao-git-e-github/geral-sobre-autenticacoes-do-github#opcoes-de-segurancas-adicionais)

Opções de seguranças adicionais

**>> Autenticação de dois Fatores - 2FA**

A autenticação de dois fatores (2FA) é como adicionar uma camada extra de segurança quando você entra em sites ou aplicativos. Além de digitar seu nome de usuário e senha, você precisa fornecer mais uma prova de que é realmente você.

No caso do GitHub, essa prova extra geralmente é um código gerado por um aplicativo no seu celular ou enviado por mensagem de texto. Depois de ativar a 2FA, sempre que alguém tenta entrar na sua conta, o GitHub pede esse código adicional. Ou seja, para entrar, a pessoa precisa não só da senha, mas também do código enviado para o celular.

Os donos de organizações no GitHub podem pedir que todos, membros ou colaboradores, ativem a 2FA em suas contas pessoais. Isso dificulta para pessoas mal-intencionadas acessarem informações importantes.

Além disso, em empresas, os donos podem impor regras de segurança para todas as organizações vinculadas a uma conta corporativa, garantindo uma proteção adicional para todos os envolvidos. Resumindo, é uma maneira de deixar as coisas mais seguras na internet.

**>> SSO do SAML**

SSO do SAML é uma forma de segurança no GitHub que permite controlar o acesso aos recursos da organização de maneira centralizada. Em vez de usar senhas, os usuários são redirecionados para um sistema central de login (IdP), como o Microsoft Entra ID ou Okta. Após autenticados lá, eles retornam ao GitHub com acesso aos recursos da organização.

Essa abordagem facilita o gerenciamento, pois os proprietários da organização controlam quem pode acessar o quê. O GitHub suporta vários provedores populares, como Active Directory, Microsoft Entra ID e Okta. Em resumo, é uma maneira mais segura e eficiente de gerenciar o acesso aos dados no GitHub.

**>>** **LDPA**

O LDAP é um protocolo usado para acessar e organizar informações em diretórios, especialmente em grandes empresas. No contexto do GitHub Enterprise Server, ele permite integrar e gerenciar centralmente o acesso aos repositórios usando contas existentes.

O GitHub Enterprise Server é compatível com vários serviços LDAP conhecidos, como Active Directory, Oracle Directory Server Enterprise Edition, OpenLDAP e outros. Em resumo, o LDAP é uma ferramenta que ajuda na organização e controle de acesso em ambientes corporativos no GitHub.

**Links Importantes:**

[https://support.github.com/](https://support.github.com/)

[Documentação de autenticação - GitHub Docs]  (https://docs.github.com/pt/authentication)
