# v1.0.1
- Modo alternativo de tela cheia
- Permite selecionar o diretório onde serão armazenados os prints

# v1.0.2
- A opção "Clique para reabrir" foi substituída por "Recarregar dados salvos"
- Inserido botão (link) para executar uma tentativa de solução da exibição de tela cheia em branco
- Efetuada correção para salvar assunto e descrição quando há edição das informações
- Se as etapas salvas estiverem sendo executadas, não permite a abertura de nenhuma janela da aplicação
- Exibe a mensagem "Etapas em execução" no menu quando as etapas estão em execução

# v1.0.3
- SGRA passa a gravar logs
- Correção de erro que impedia a edição das etapas

# v1.0.4
- Aplicação passa a permitir múltiplas configurações
- Inseridos botões para recolher ou expandir as seções da tela de configuração de etapas
- Uma nova tela principal foi desenvolvida. É possível definir se a aplicação continuará em execução e também definir a ordem de execução das configurações e o tempo de espera até o início da execução automática
- Removida a funcionalidade testar etapas

# v1.0.5
- Correção de erro FormData is not defined
- Ajuste no envio de informação para as janelas
- Verificação de versão do Electron para definição do repositório para atualização automática

# v1.0.6
- Correção de erro ao editar etapas (informações da configuração não eram carregadas)

# v1.0.7
- Inseridas funcionalidades para exclusão de configuração e ação

# v1.0.8
- Ajuste no carregamento das etapas na tela de edição (em alguns casos, o carregamento causava erro e impossibilitava a edição)
- Downgrade de versão do módulo jimp (uso da versão 1.1.4 causou erro "TypeError: Jimp is not a constructor")
- Remoção do modo de compatibilidade

# v1.0.9
- Correção de erro ao cadastrar etapas pela primeira vez (ou quando não há nenhuma configuração existente)
- Correção de erro quando o diretório para salvar os prints não foi definido ou não possui arquivos

# v1.0.10
- Inserido campo para informar observação em cada ação
- Inserido campo para informar múltiplos destinatários de e-mail para cada configuração
- Campos de senha movidos para a tela principal
- Inserida opção para exibir a última etapa executada
- Inserida opção para definir se a senha deve ser solicitada ao iniciar e/ou ao configurar as etapas
- Ajustes na validação das etapas e configurações