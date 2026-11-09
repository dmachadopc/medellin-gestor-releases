# Medellín Gestor — distribuição

Este repositório contém somente um README e arquivos de distribuição do aplicativo Windows. O código-fonte de desenvolvimento não é publicado aqui. Os instaladores contêm os arquivos compilados necessários ao aplicativo.

## Versões

Abra a seção **Releases** deste repositório para obter a versão atual e suas instruções. O feed genérico do aplicativo usa os arquivos da release mais recente.

## Piloto atual

A versão 1.0.1 é um piloto **não assinado com Authenticode**, aprovado para teste controlado. HTTPS e hashes não substituem a assinatura digital do editor. Não desative proteções do Windows para instalar ou atualizar. Havendo bloqueio, registre o aviso e interrompa.

Para quem está na 1.0.0, o arquivo `Iniciar-Gestor-com-Atualizacoes.cmd` inicia o aplicativo existente com o endereço correto do feed somente naquela sessão. Feche o aplicativo normalmente antes de usá-lo. O script não instala, não apaga dados, não encerra processos e não altera o Registro. Sua execução ainda depende de validação na máquina Windows.

A partir da 1.0.1, a área própria fica em **Configurações → Atualizações**, com o botão **Verificar Atualizações**. Downloads ocorrem em segundo plano; instalação/reinício exigem clicar em **Reiniciar e Atualizar**, fora do atendimento. Fechar no X não instala.

## Limites

A homologação de aplicação/reinício e preservação de preferências no Windows da loja está pendente. Correções de impressão e identidade visual seguem em desenvolvimento e não devem ser presumidas nesta versão.

Este repositório não fornece credenciais nem acesso ao painel. Não inclua dados pessoais, senhas ou tokens em relatos de erro.
