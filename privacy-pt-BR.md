---
title: Política de Privacidade do Friends Fighters
---

# Política de Privacidade do Friends Fighters

Última atualização: 2026-10-16

Outros idiomas: [English](https://fberbert.github.io/friends-fighters-legal/privacy-en.html) | [Español](https://fberbert.github.io/friends-fighters-legal/privacy-es.html)

Friends Fighters ("o jogo") é um jogo para Android de Fábio Berbert de Paula ("nós"). Esta política explica o que o jogo faz com as fotos e as outras informações que você coloca nele e o que o nosso servidor guarda quando você entra com uma conta Google. Em resumo: suas fotos, recortes de cabeça, máscaras e gravações de voz ficam no seu aparelho e nunca são enviados ao nosso servidor; eles só saem do aparelho quando você decide compartilhar um arquivo de lutador ou um vídeo da luta. O nosso servidor guarda só o necessário para contar suas criações gratuitas e desbloquear o jogo completo: o identificador da sua conta Google, os registros das suas criações e os registros das suas compras. O jogo não tem anúncios nem análises de uso.

## 1. O que o jogo envia pela internet

- O jogo se conecta apenas ao próprio servidor, `api.friendsfighters.automatizando.dev`, e ao Google, para entrar com a conta e para as compras no Google Play. Todas as conexões são criptografadas (HTTPS).
- Os lutadores prontos, todos os modos de jogo e as lutas funcionam offline e sem conta.
- O jogo não tem publicidade, análises de uso, serviço de relatório de falhas nem cópia dos seus lutadores na nuvem.
- O jogo nunca envia fotos, recortes de cabeça, máscaras, gravações de voz ou nomes de lutadores ao nosso servidor ou ao Google. Eles só saem do seu aparelho quando você os compartilha (seção 7).
- Abrir esta política pelos Ajustes inicia o seu navegador.

## 2. Fotos e rostos

- Para criar um lutador, você escolhe uma foto no seletor de fotos do Android ou tira uma com o seu app de câmera. O jogo não pede permissão de armazenamento nem de câmera: o Android entrega ao jogo apenas a foto que você escolheu.
- O jogo copia essa foto, reduzida a no máximo 2048 pixels, para o armazenamento privado dele como uma imagem PNG sem metadados, como dados de localização (GPS).
- A remoção de fundo, que encontra a cabeça na foto, é feita inteiramente no seu aparelho com um modelo do Google MediaPipe incluído no jogo. O jogo não identifica pessoas e não cria dados de reconhecimento facial.
- Para cada lutador, o jogo guarda no seu aparelho a cópia da foto, o recorte da cabeça, as máscaras automática e retocada desse recorte, os seus ajustes de enquadramento e edição, uma pequena imagem de prévia e as gravações de voz, se houver (seção 3).
- Quando você confirma um lutador, o jogo envia ao nosso servidor um código SHA-256 da imagem do rosto confirmado (seção 5). O código é calculado no seu aparelho; não é possível reconstruir a imagem a partir dele, e os códigos nunca são comparados entre contas.
- Use apenas fotos de pessoas que concordaram em virar lutadores e nunca use o jogo para humilhar ninguém. O jogo pede essa confirmação antes da primeira importação de foto.

## 3. Gravações de voz

- Se você gravar uma voz para um lutador, o jogo pede a permissão de microfone nesse momento. Você pode recusar; todo o resto continua funcionando.
- Um lutador pode ter até seis gravações (por exemplo, para um nocaute ou uma vitória). Cada uma dura no máximo 2 segundos e fica na pasta privada do lutador no seu aparelho.
- As gravações nunca são enviadas ao nosso servidor. Elas só saem do seu aparelho dentro de um arquivo de lutador ou de um vídeo da luta que você decide compartilhar (seção 7).
- Você pode revogar a permissão de microfone a qualquer momento nas configurações do Android.

## 4. Informações guardadas no aparelho

- Nomes e aparência dos lutadores; suas configurações (idioma, volumes de efeitos e de música, dificuldade, vibração, controles e redução de movimento); sua resposta à pergunta de consentimento das fotos; a configuração da sua última partida; estatísticas de partidas, inclusive os confrontos diretos entre lutadores; o progresso na Escalada; e as conquistas.
- Quando você entra com a conta: o ID da sua conta no jogo, uma chave de sessão e o registro assinado das suas criações gratuitas e do desbloqueio, além dos registros das suas criações com os códigos dos rostos e dos lutadores que aguardam confirmação.
- Para você identificar a conta Google conectada nos Ajustes, o jogo também guarda o nome e o e-mail fornecidos pelo Google e uma pequena foto de perfil opcional, baixada do Google por HTTPS. Esses dados de exibição ficam no aparelho em um cache local separado e não são acrescentados às solicitações ao nosso servidor. Sair, trocar de conta ou excluir a conta pelo jogo apaga esse cache. Sem foto, o jogo mostra as iniciais; uma sessão existente pode atualizar os dados da conta sem gastar uma criação gratuita. O ID completo da conta no jogo continua disponível nos Ajustes em Informações para suporte.
- Tudo fica no armazenamento privado do jogo, que outros apps não conseguem ler. Esses dados são excluídos dos backups na nuvem do Android e das transferências entre aparelhos.

## 5. Sua conta no jogo

- Você só precisa de uma conta para criar os seus próprios lutadores e para comprar ou restaurar o jogo completo. O jogo pede que você continue com Google na primeira vez que confirma um lutador, e você também pode entrar pelos Ajustes. Você pode recusar e continuar jogando com os lutadores prontos.
- A confirmação de acesso do Google, que o jogo repassa ao nosso servidor, também contém seu nome, endereço de e-mail e foto de perfil. O servidor apenas verifica essa confirmação e guarda o identificador da conta Google; ele nunca guarda seu nome, e-mail ou foto.
- Para a sua conta, o nosso servidor guarda: o identificador da conta Google; um ID aleatório da conta, mostrado nos Ajustes para o suporte; a data de criação da conta; as suas sessões, como códigos SHA-256 das chaves de sessão; os registros das suas criações (data, tipo de criação: lutador novo, duplicação ou troca de rosto, e o código SHA-256 da imagem do rosto confirmado); a quantidade de criações gratuitas concedidas e usadas, inclusive as criações extras concedidas pelo suporte; a situação do desbloqueio e as datas do registro assinado dela; e os registros das suas compras (seção 6).
- O seu endereço IP chega ao servidor apenas para limitar a quantidade de pedidos, na memória. O servidor não o guarda nem o registra.
- Usamos esses dados apenas para as criações gratuitas, a trava do rosto e o desbloqueio, para restaurar a sua compra, para evitar abusos das criações gratuitas e para responder ao suporte. Não vendemos esses dados, não os usamos para publicidade e não os compartilhamos com ninguém além dos prestadores de serviço da seção 8.

## 6. Compras e Google Play

- O jogo é gratuito para baixar. O desbloqueio completo é uma compra única e opcional no Google Play. O Google processa o pagamento conforme a Política de Privacidade do Google (https://policies.google.com/privacy); nós nunca recebemos os dados do seu pagamento.
- Na compra, o jogo informa ao Google Play o ID aleatório da sua conta no jogo, para que a compra fique vinculada a ela. O jogo não envia ao Google Play seus lutadores nem suas fotos.
- O nosso servidor recebe do Google Play o registro da compra do desbloqueio (token da compra, produto, número do pedido, situação, como comprada, pendente, cancelada ou reembolsada, tipo de compra e datas) e o vincula à sua conta no jogo, para que o desbloqueio funcione nos seus aparelhos e volte com Restaurar compras, na tela Desbloqueie o jogo completo.
- O Android e o Google Play podem coletar estatísticas de falhas e diagnóstico conforme as configurações do seu aparelho e as políticas do Google. O jogo em si não envia nada disso.

## 7. Compartilhar é sempre escolha sua

- Cards de compartilhamento: o jogo cria uma imagem do resultado de uma partida só quando você toca em Compartilhar.
- Arquivos de lutador: o jogo exporta um lutador com todos os dados dele, inclusive fotos e gravações de voz, só quando você toca em Exportar lutador. Ele importa apenas um arquivo que você escolhe em Importar lutador ou abre com o jogo.
- Vídeos da luta: o jogo gera um vídeo de uma luta, com os rostos e os sons dos lutadores, só quando você toca em Vídeo da luta e confirma.
- Figurinhas: o jogo oferece o pacote de figurinhas de um lutador ao WhatsApp só quando você toca em Figurinhas para WhatsApp e depois em Adicionar ao WhatsApp; o WhatsApp então lê o pacote no jogo.
- O app que você escolher recebe a imagem, o arquivo ou o vídeo pelo menu de compartilhamento do Android e os trata conforme a política de privacidade dele. Nós não recebemos cópia.

## 8. Prestadores de serviço

- O nosso servidor funciona na Amazon Web Services (EC2), na região de Oregon, Estados Unidos. Por isso, os dados das seções 5 e 6 são armazenados e tratados fora do Brasil, nos Estados Unidos.
- O Google fornece o acesso com a conta, os pagamentos do Google Play, a verificação das compras e os avisos de compra. No seu aparelho, o acesso com a conta usa o Google Play Services (Gerenciador de Credenciais do Android) e as compras usam o Google Play Billing; esses componentes falam diretamente com o Google, conforme as políticas do Google.
- Esses prestadores tratam os dados apenas para nos prestar o serviço.

## 9. Por quanto tempo guardamos os dados

- A sua conta, os registros das suas criações e a situação do desbloqueio: até você excluir a conta.
- Sessões: 30 dias depois de cada acesso.
- Depois que você exclui a conta, guardamos por 365 dias, apenas para evitar abusos das criações gratuitas, a quantidade de criações gratuitas que você usou, com o ID aleatório da conta e as datas de criação e de exclusão da conta, sob um código pseudônimo calculado a partir do identificador da sua conta Google com uma chave secreta. Se você entrar de novo com a mesma conta Google nesse período, a nova conta começa com essa quantidade e esse registro é apagado.
- Registros de compra: 365 dias depois da exclusão da conta, sem vínculo com a sua conta no jogo, para reembolsos e prevenção de fraudes.
- Registros de ações do suporte (por exemplo, uma criação gratuita extra) guardam o ID aleatório da conta, a ação, quem a fez e a data por 365 dias depois da ação; as anotações deles são apagadas quando a conta é excluída.
- As cópias de segurança do banco de dados são apagadas em até 14 dias.

## 10. Como apagar seus dados

- Exclua um lutador na galeria de lutadores para remover do aparelho todos os arquivos dele.
- Desinstalar o jogo, ou limpar o armazenamento dele nas configurações do Android, apaga todos os dados do jogo no aparelho. Como os backups estão desativados, um jogo reinstalado começa vazio.
- Exclua a sua conta no jogo (Ajustes, Conta, Excluir conta) ou na página https://api.friendsfighters.automatizando.dev/delete-account, onde você entra com Google. Essa página carrega o script de login do Google, então o Google recebe seu endereço IP e dados do navegador conforme a Política de Privacidade do Google; o nosso servidor não os registra. Se você não conseguir entrar, escreva para nós com o ID da conta mostrado nos Ajustes. A exclusão remove o identificador da conta Google, as sessões, os registros das criações com os códigos dos rostos e o registro do desbloqueio; a seção 9 lista o que fica guardado. Os seus lutadores continuam no seu aparelho, e a sua compra continua no Google Play: entre de novo e use Restaurar compras.

## 11. Crianças

O jogo é destinado a jogadores com 13 anos ou mais. Ele não é direcionado a crianças menores de 13 anos.

## 12. Seus direitos

Pela Lei Geral de Proteção de Dados (LGPD) e leis semelhantes, você pode nos pedir a confirmação de que tratamos seus dados, o acesso a eles, a correção, a exclusão, a portabilidade e informações sobre os prestadores que os tratam. Envie o pedido com o ID da conta mostrado nos Ajustes; respondemos em até 15 dias. Você também pode excluir a sua conta por conta própria, como descrito na seção 10.

## 13. Mudanças nesta política

Se o jogo mudar a forma como trata dados, atualizaremos esta política, mudaremos a data no topo e descreveremos a mudança nas notas da versão no Google Play.

## 14. Contato

Fábio Berbert de Paula
E-mail: contato@automatizando.dev
